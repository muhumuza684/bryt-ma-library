# GITHUB COMMIT GUIDE

Suggested repository destination:

```text
books/rejections-in-monaco/
```

PowerShell from the repository root:

```powershell
New-Item -ItemType Directory -Force .\books\rejections-in-monaco | Out-Null
Copy-Item -Recurse -Force .\REJECTIONS-IN-MONACO_MASTER_EDITION\* .\books\rejections-in-monaco\
git add books/rejections-in-monaco
git status
git commit -m "Add Rejections in Monaco master edition"
git push
```

Keep the editable Markdown files in Git. Treat the ZIP as a release/archive artifact unless you deliberately want the binary committed too.
