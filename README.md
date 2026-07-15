# kennylbrown.com

Personal profile / freelance site for **Kenny Brown** — Senior Software Developer & AI Prompt Engineer.

Single static page, served by **GitHub Pages** at <https://kennylbrown.com>. No build step, no dependencies — everything (HTML, CSS, JS) is inline in `index.html`.

## Files
- `index.html` — the whole site (self-contained).
- `CNAME` — custom domain for GitHub Pages (`kennylbrown.com`).
- `404.html` — fallback page for unknown paths.
- `robots.txt` — allows indexing.

## Update the site
Edit `index.html`, then:
```bash
git add index.html
git commit -m "Update content"
git push
```
GitHub Pages redeploys within ~1 minute.

## Contact form
The contact form uses [Web3Forms](https://web3forms.com) (free, no server needed). Paste your
access key into the hidden `access_key` input in the contact `<form>` (search the file for
`YOUR_WEB3FORMS_ACCESS_KEY`). Messages are forwarded to your email without exposing the address
on the page. Until a real key is set, the form shows a LinkedIn fallback message.
