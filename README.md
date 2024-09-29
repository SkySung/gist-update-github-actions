# gist-update-github-actions
Automatic update gist file from a GitHub repo.

---

# How Does it Work?
It uses the GitHub CLI to send a RESTful API request.
https://resources.github.com/learn/pathways/automation/advanced/building-your-first-custom-github-action/

Whenever a GitHub Actions server is initialized, it automatically configures the GitHub CLI (gh command).
Therefore, we can easily update a user's own gist without any permission token, making it safe for most developers.

# Configuratoin
Add proper .env variable to let this GitHub Actions work.
