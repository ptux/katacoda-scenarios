## fork app repo

`hub clone https://github.com/ptux/hello-gitops-app.git ~/hello-gitops-app`{{execute}}

`cd ~/hello-gitops-app && hub fork`{{execute}}

replace username
`GITHUB_USERNAME=ooocamel`{{execute}}

`cd ~/hello-gitops-app && git remote set-url ooocamel https://github.com/$GITHUB_USERNAME/hello-gitops-app.git`{{execute}}

