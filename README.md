# Traefik Config

create a .env file with

```dotenv
PROVIDERS_GOOGLE_CLIENT_ID=<google client id>
PROVIDERS_GOOGLE_CLIENT_SECRET=<google client secret>
SECRET=<create with openssl rand -hex 16>
DUCKDNS_TOKEN=<token from duckdns>
DOMAINNAME=<your domain>.duckdns.org
ACMEMAIL=<your mail for Let’s Encrypt>
WHITELIST=<comma sperated list of mails of allowed google accounts>
```
