# ResolveIt — Issue Intelligence

A responsive, simple issue submission and tracking portal suitable for a third-year CSE software engineering project demonstration.

## Included
- Overview dashboard with issue counts
- Student issue submission form
- Unique tracking ID for each report
- Status lookup by ID
- Teacher panel to review issues and update status
- Responsive dark, purple-accented interface
- Local browser storage for demo persistence

## Run locally
This is a static website. You can open `index.html` directly, or run it with a local static server.

## Deploy to Vercel
1. Upload the contents of this folder to a Git repository.
2. Import the repository in Vercel.
3. Set Framework Preset to **Other**.
4. Set Build Command to empty / disabled.
5. Set Output Directory to `.`.
6. Deploy. The included `vercel.json` routes requests to `index.html`.

## Important limitation
This is a front-end demonstration. Data is saved in the browser's localStorage, so it is not shared between different users, browsers or devices. The teacher panel is not authenticated. A real multi-user release needs a shared backend/database, teacher login and role-based access control, plus server-side validation.
