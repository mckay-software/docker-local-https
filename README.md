# Local HTTPS proxy

Uses Caddy to proxy all requests to a backend, generating a self-signed TLS
certificate at startup and serving everything over HTTPS. Useful for local
development when HTTPS is needed for e.g. geolocalisation website features.

Simply specify the `BACKEND` env variable to a host or host:port.
