# Alliance Research Mind Map

This project is a static web page ready to publish.

## Local preview

Run:

```bash
cd "/Users/sipa-120m-go/Documents/New project"
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

## Publish on GitHub Pages

1. Create a new public GitHub repository (for example: `alliance-research-mindmap`).
2. Push this folder to that repository.
3. In GitHub: `Settings -> Pages`.
4. Under **Build and deployment**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Save. Your site will publish at:
   - `https://<your-github-username>.github.io/<repo-name>/`

## Files

- `index.html`: the published page entrypoint.
