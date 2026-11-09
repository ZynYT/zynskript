# ZynSkripts

A free static website for sharing Minecraft Skript files with GitHub Pages.

## Publish it for free

1. Sign in to GitHub and create a **public** repository named `zynskripts`.
2. Upload `index.html` and `scripts.json` from this folder to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then Save.
6. Wait a minute or two. GitHub will show your website address in Settings → Pages.

## Add a script later

1. Open your live website and choose **Add Script**.
2. Fill in the details and paste your Skript code.
3. Click **Create updated scripts.json**. It downloads the updated file.
4. Open your GitHub repository, upload the new `scripts.json`, and choose to replace the old one.
5. Commit the change. Your website updates after GitHub Pages rebuilds.

Important: GitHub Pages is static hosting. The Add Script form creates the updated data file in your browser; it does not directly publish changes. Never put a GitHub access token or password in a public website.

## Notes

- The two included entries are examples. Replace their demo code with your own scripts.
- Each script is stored in `scripts.json` with `id`, `name`, `category`, `version`, `description`, `code`, and `tags`.
- The site is not affiliated with Mojang or the Skript project.
