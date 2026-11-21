# FCC Timestamp Microservice
A timestamp microservice with RESTful API.

## Installation
Clone the repository
```bash
git clone https://github.com/MeBenji/fcc-timestamp-microservice.git
```

Install dependencies
```bash
cd fcc-timestamp-microservice/
npm i
```

## Usage
### Start server
```bash
npm start
```

### Interact \w server
Methods to interact \w the server:
- Open a browser and navigate to http://localhost:8000
- Query the API at http://localhost:8000/api/:date

### Example interaction
To receive a timestamp of the 21st of November 2026 query the API at http://localhost:8000/api/2026-11-21.

**Bash**:
```bash
curl http://localhost:8000/api/2026-11-21
```

**JavaScript**:
```javascript
const result = await fetch("http://localhost:8000/api/2026-11-21").then(response => response.json());
```

## License
This package is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
