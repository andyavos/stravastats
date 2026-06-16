# Strava Stats
### Strava Year-to-date Dashboard

Connect your Strava account to see your year-to-date cycling stats. Mileage, elevation, ride count, and monthly breakdown.

Uses the Strava API, Strava MCP version coming.

### How to get your access token
1. Go to strava.com/settings/api and create an app (any name/website)
2. Note your Client ID and Client Secret
3. Visit this URL in your browser (replace CLIENT_ID):
https://www.strava.com/oauth/authorize?client_id=CLIENT_ID&redirect_uri=http://localhost&response_type=code&scope=activity:read_all
4. After approving, copy the code= value from the redirect URL
5. Exchange it for a token using the form below (or via curl/Postman)
