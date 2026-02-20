# World Gutterball

The official site for Gutterball - the game where losing wins!

## Deploying to GitHub Pages

1. Create a GitHub repository named `worldgutterball` (or any name)
2. Push these files to the repository
3. Go to repository Settings > Pages
4. Under "Build and deployment", select "Deploy from a branch"
5. Select your main branch and root directory
6. In the "Custom domain" section, enter `worldgutterball.com`
7. Configure your DNS:
   - Create an A record pointing to `185.199.108.153`
   - Create an A record pointing to `185.199.109.153`
   - Create an A record pointing to `185.199.110.153`
   - Create an A record pointing to `185.199.111.153`
   - Or create a CNAME record pointing to `yourusername.github.io` (if using www)

## Files

- `index.html` - Main site with rules and terms
- `CNAME` - Custom domain configuration for GitHub Pages
- `README.md` - This file