# teste-jenkins
  
git remote -v
git remote set-url --add --push origin https://github.com/Hovelacque/teste-jenkins.git
git remote set-url --add --push origin http://192.168.100.4:3080/root/teste.git
git remote set-url --add --push origin http://localhost:3080/root/teste.git
git remote set-url --add --push origin ssh://git@localhost:2222/srv/git/your-repo.git
git remote set-url --add --push origin http://localhost:3000/kapibara/teste.git

git remote set-url --delete --push origin http://localhost:3080/root/teste.git
git remote set-url --delete --push origin ssh://git@localhost:2222/srv/git/your-repo.git