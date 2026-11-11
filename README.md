# yc-shiperr

Simple Go backend with a health endpoint.

## Run

```
go run .
```

Server starts on port 9000.

## Health check

```
curl http://localhost:9000/health
# {"service":"yc-shiperr","status":"ok","time":"..."}
```

## Changelog

### v0.1.0 (2026-11-11)
- Initial Go HTTP server on port 9000
- `GET /health` returns JSON status
