# Flask API

A small Flask application exposing two REST endpoints.

## Endpoints

### Health Check

`GET /api/v1/healthz`

Returns:

```
OK
```

with HTTP status `200`.

### Application Details

`GET /api/v1/details`

Returns application information as JSON, including hostname and current timestamp.

## Run

```
pip install flask
python app.py
```

The application starts on:

```
python-app-5-dev.test.com
```

## Example

```
curl python-app-5-dev.test.com/api/v1/healthz
curl python-app-5-dev.test.com/api/v1/details
```

**Port:** `8080`  
**Host:** `0.0.0.0`  
**Debug:** Disabled