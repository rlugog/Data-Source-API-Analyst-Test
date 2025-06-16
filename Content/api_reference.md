# 📚 API Reference – GitHub REST API

This file summarizes the API endpoints and headers used in the GitHub API analysis project.

## 🌐 Base URL
https://api.github.com

GET /users/{username}/repos

- Used to retrieve the list of public repositories for a specific GitHub user.

### 🔹 Get Commits from a Repository

GET /repos/{username}/{repo}/commits

- Used to retrieve recent commit history from a specific repository.

### 🔹 Get Contents of Repository
GET /repos/{username}/{repo}/contents/

- Used to retrieve the list of files and folders in the root directory of a repository.

---

## 🧾 Headers Used

```http
Authorization: token <your_token>
Accept: application/vnd.github+json
X-GitHub-Api-Version: 2022-11-28

These headers ensure secure and consistent access to GitHub’s REST API v3.
GET /repos/{username}/{repo}/contents/

Pagination is not needed for small samples, but for larger responses, you can append:



?per_page=100&page=2

All endpoints used require only public access scope (public_repo).
