# Adding an Existing Codeset

If you have an exisitng codeset and want to add it to a new GitHub repo, follow these steps:

Log in to your [GitHub](https://github.com/) account and create a new repo.

Open your terminal, change the present working directory to your project directory, and then run these commands:

```
git init
git add .
git commit -m "Initial Commit"
git branch -M main
git remote add origin https://github.com/<GITHUT_USERNAME>/<REPO_NAME>.git
git push -u origin main
```

## Tutorial Requirements:

* [GitHub](https://github.com/)

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="100">
</a>
