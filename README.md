# Elementary NFC Participation Proposal

Static Vercel deploy package for the NFC participation proposal.

## Routes

- `/` renders the clickable UX HTML preview.
- `/proposal.pdf` downloads the proposal PDF.
- `/proposal` rewrites to `/proposal.pdf`.

## Vercel Setup

1. Import this GitHub repository in Vercel.
2. Use the default static project settings.
3. Set the project root to the repository root.
4. No build command is required.
5. No output directory is required.

After deployment, use:

- `https://<vercel-project>.vercel.app/` for the UX preview
- `https://<vercel-project>.vercel.app/proposal.pdf` for the PDF download
