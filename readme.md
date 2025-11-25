Place a .env in root, with the following content:

MSSQL_SA_PASSWORD={your desired mssql password}
DB_CONNECTION_STRING={the connectionstring for the database}
DUCKDNS_TOKEN={the token for your duckdns domain}
DOMAIN_URL={your base domain URL}




If you dont use duckdns, then you need to remove the token from the Caddyfile
