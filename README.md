# Alexandru Albu Portfolio

Static professional portfolio website for Alexandru Albu.

## Local preview

From the repository root:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy on Render (Static Site)

1. Push this repository to GitHub.
2. In Render, choose **New +** → **Static Site**.
3. Connect the GitHub repository.
4. Configure:
   - **Build Command**: *(leave empty)*
   - **Publish Directory**: `.`
5. Click **Create Static Site**.
6. Render will serve `index.html` from the repository root.