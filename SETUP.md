# Setup (5 minutes)

1. Upload everything in this zip to your `Bhargavi2048/Bhargavi2048` repo, including the hidden `.github` folder.
   If drag-and-drop skips `.github`, use Add file > Create new file and type `.github/workflows/profile.yml`, then paste the file contents.
2. If you still have `.github/workflows/snake.yml` or `profile-cards.yml` from earlier, delete them. `profile.yml` replaces both.
3. Settings > Actions > General > Workflow permissions: choose "Read and write permissions", Save.
4. Actions tab > "Profile automation" > Run workflow. Wait about 2 minutes for both jobs to turn green.
5. Hard refresh your profile (Ctrl+Shift+R). The snake and the stat cards fill in on their own.

If the "cards" job fails with "Resource not accessible by integration", create a personal access token, add it as a repo secret, and use it instead of GITHUB_TOKEN in that job.
