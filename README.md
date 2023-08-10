# litestar-oauth-example

To reproduce OPTIONS not working in RC1 with OAuth Middileware

```bash
curl -X 'OPTIONS' \
  'http://localhost:8000/some-path' 

```
>`{"status_code":401,"detail":"No JWT token found in request header or cookies"}`
