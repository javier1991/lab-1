# Laboratorio 1
```bash
git init
git add .
git commit -m "commit inicial"
curl -u 'DavSanchez' https://api.github.com/user/repos -d '{"name":"TING-LAB1"}'
git remote add origin git@github.com:DavSanchez/TING-LAB1.git
git push --set-upstream origin master
git add Lab1.md
git commit -m "Segundo commit"
git push
// ...
```