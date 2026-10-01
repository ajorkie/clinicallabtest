# Clinical Lab Matching Game

A responsive matching game with eight category/purpose pairs, shuffled cards, attempt tracking, and restart. No installation, build step, or external dependencies. Open index.html directly to play.

## Host with GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html` and this README to the root of the repository, then commit them to `main`.
3. Open the repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/ (root)**, then click **Save**.
6. After deployment completes, open the URL displayed in Pages settings.

Source: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Edit the matching pairs

Find `const pairs =` (or `const pairs=`) inside index.html. Each entry contains a category and its matching purpose. The current game uses eight pairs. If changing the number of pairs, update the hardcoded total of eight in the score and completion checks.

These are category/purpose matches. The source worksheet did not list individual lab test names.
