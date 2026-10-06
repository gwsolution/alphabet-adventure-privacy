# Alphabet Adventure — Privacy Policy (GitHub Pages)

Public privacy policy for the [Alphabet Adventure](https://github.com/YOUR_GITHUB_USERNAME/abc) Android app. Host this repo on **GitHub Pages** and use the URL in Google Play Console.

## One-time setup

1. Create a new **public** repository on GitHub (for example `alphabet-adventure-privacy`).
2. Push this folder to that repo:

   ```bash
   cd alphabet-adventure-privacy
   git init -b main
   git add index.html README.md
   git commit -m "Add privacy policy for GitHub Pages"
   git remote add origin https://github.com/YOUR_GITHUB_USERNAME/alphabet-adventure-privacy.git
   git push -u origin main
   ```

3. Edit **`index.html`**: replace `REPLACE_WITH_YOUR_EMAIL` with your real support/privacy email (Play Console requires a contact email).

4. Enable GitHub Pages:
   - Repo → **Settings** → **Pages**
   - **Build and deployment** → Source: **Deploy from a branch**
   - Branch: **`main`** / **`/ (root)`**
   - Save

5. After a minute or two, your policy URL will be:

   ```text
   https://YOUR_GITHUB_USERNAME.github.io/alphabet-adventure-privacy/
   ```

   Use that exact URL in Play Console → **App content** → **Privacy policy**.

## Optional: custom domain

In **Pages** settings, add a custom domain (for example `privacy.yourdomain.com`) and configure DNS per GitHub’s instructions.

## Updating the policy

Edit `index.html`, commit, and push. Pages redeploys automatically.
