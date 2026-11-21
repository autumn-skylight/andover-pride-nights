# andoverpridenights.co.uk

andover lgbtq+ social groups website

## Private dates page

The `/dates` page is served by a Vercel function. In the Vercel project settings, add these environment variables for the deployment:

- `DATES_PAGE_PASSWORD`: the password to share with page visitors.
- `DATES_SESSION_SECRET`: a separate, randomly generated secret used to sign login sessions.

The dates are not returned until a visitor enters the password. Login sessions expire after eight hours.
