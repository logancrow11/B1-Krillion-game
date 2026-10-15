# B1-Krillion-game

This project is a static HTML game. Because it runs as plain browser code, it can be shared as a static website.

## Run locally

```bash
cd /workspaces/B1-Krillion-game
python3 -m http.server 8000
```

Then open http://localhost:8000

## Share publicly

### Option 1: GitHub Pages
1. Push this folder to a GitHub repository.
2. Open the repo in GitHub.
3. Go to Settings > Pages.
4. Set Source to "Deploy from a branch".
5. Choose the main branch and the root folder.
6. Save.
7. GitHub will give you a public URL like `https://yourname.github.io/repository-name/`

### Option 2: Netlify
1. Drag the folder into Netlify's deploy area or connect the GitHub repo.
2. Netlify publishes a live public URL automatically.

### Option 3: VS Code port forwarding
1. In VS Code, open the Ports tab.
2. Find port 8000.
3. Click the link for a forwarded URL.
4. Send that URL to friends.

> Note: `localhost` only works on your own machine. For other people, use a forwarded port or a public static host.
