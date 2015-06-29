# radar-www2
Front end for simple node app to view issues on github. Communicates with radar API. By default, runs on port 3000
# Environmental variables (optional):
- WWW_PORT: Port used for app (default:3000). Make sure the API gets the change accordingly.
- API_URL: URL for front end to find API (default:localhost:3001)
- API_PORT: Alternative to API_URL, port for front end to find API (default:3001)
- ENVIRONMENT: 'test' or 'dev', sets logging procedure