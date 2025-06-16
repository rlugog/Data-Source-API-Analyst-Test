# 🛠 Troubleshooting Guide

This guide documents common issues encountered while working with the GitHub API and how they were resolved.

---

## 🔴 401 Unauthorized

**Problem:**  
Requests return a 401 error indicating that authentication failed.

**Solution:**  
- Confirm that you are using a **Classic GitHub Token** with the correct scopes (`repo` or `public_repo`).
- Ensure the token is active and copied correctly (no extra spaces).
- Fine-grained tokens often require specific repository permission settings and were not suitable for this task.

---

## 🟠 Token Not Working

**Problem:**  
The token does not return data or gives access errors.

**Solution:**  
- Regenerate a Classic Token.
- Select proper scopes (at least `public_repo`).
- Use it in the header: `Authorization: token <your_token>`

---

## 🟡 Rate Limits

**Problem:**  
GitHub limits the number of API calls per hour.

**Solution:**
