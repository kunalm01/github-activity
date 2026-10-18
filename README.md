# github-activity

A GitHub Actions workflow that makes 1 to 6 commits to `activity.log` once a day.

## Setup

1. Push this repo to GitHub (public, or private with "Include private contributions" turned on in your profile settings).
2. In the repo, go to Settings > Secrets and variables > Actions > Variables and add:
   - `GIT_AUTHOR_NAME`: your name
   - `GIT_AUTHOR_EMAIL`: an email verified on your GitHub account, or your noreply address
     (`<id>+<username>@users.noreply.github.com`, shown under Settings > Emails)
3. Go to Actions > daily-activity > Run workflow to test it once.

Commits only count on your contribution graph when the author email is linked to your account
and they land on the default branch.
