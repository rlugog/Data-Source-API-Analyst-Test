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

