# andoverpridenights.co.uk

andover lgbtq+ social groups website

## Private dates page

The `/dates` page is served by a Vercel function. In the Vercel project settings, add these environment variables for the deployment:

- `DATES_PAGE_PASSWORD`: the password to share with page visitors.
- `DATES_SESSION_SECRET`: a separate, randomly generated secret used to sign login sessions.

The dates are not returned until a visitor enters the password. Login sessions expire after eight hours.

To add updates to a date, edit its `beside` and `underneath` values in `dates-updates.json`. The `beside` text appears next to the date, and `underneath` appears below it. Leave either value empty when not needed. Save and redeploy to publish changes.
