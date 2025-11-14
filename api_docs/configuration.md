# Configuration

For configuring your locally installed version of the EUDIW Issuer Front-end, you need to change the following configurations.

## 1. Service Configuration

Base configuration for the EUDIW Issuer Front-end is located in ```.env```.

Parameters that should be changed:

- `SERVICE_URL` (Base url of the service)
- `FRONTEND_ID` (The front-end id registered in the backend service)
- `ISSUER_URL` (Base url for the back-end service)
- `OAUTH_URL` (Base url for the authorization service)
- `CREDENTIALS_SUPPORTED` (List of credentials supported by this front-end)
- `LOG_DIR` (Log directory)
