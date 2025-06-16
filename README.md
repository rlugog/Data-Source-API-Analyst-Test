# Data Source API Analyst Test

## 📌 Objective
This project is part of a technical assignment to demonstrate my understanding of REST APIs, ability to extract data from GitHub using authentication, handle pagination, and document the process using Google Colab.

## 🚀 Tools Used
- Python
- Google Colab
- GitHub REST API v3
- Requests library

## 🔎 Scope of Data Extraction
I focused on extracting the following reports:
- ✅ List of public repositories for the user `rlugog`
- ✅ List of recent commits from a selected repository (`ab-test-analysis`)
- ✅ List of contents (files and folders) in the root of that repository

## 🔐 Authentication
Authentication was handled via a classic GitHub token using headers:
- `Authorization: token <TOKEN>`
- `Accept: application/vnd.github+json`
- `X-GitHub-Api-Version: 2022-11-28`

## 📂 Project Structure
README.md
├── Content/
│ ├── github_api_script.ipynb
│ ├── api_reference.md
│ └── troubleshooting.md


## 💡 Reflections
This exercise allowed me to strengthen my understanding of RESTful APIs, practice GitHub data extraction, and reinforce error handling and pagination strategies. I chose Google Colab for flexibility and reproducibility.

---

*Prepared by Rodrigo Lugo – GitHub: [@rlugog](https://github.com/rlugog)*


