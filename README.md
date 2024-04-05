# Passos conexão pelo play with docker

Para conectar um repositorio do github pelo play with docker

Passos:

Criar um usuario que não seja root e fazer login nesse usuario

Criar a chave ssh e adicionar a chave ao github

 ssh-keygen

fazer o clone do repositorio do github

 git clone


Para enviar as alterações de volta para o repositorio do github, 
fazr as configurações globais de usurio e email 

  git config --global user.name "<nome-do-usuario-github>"
  git config --global user.name "<email-do-github>"


Para lembrar:

echo "# Instruções para uso do repositorio" >> README.md 
git init 
git add README.md 
git commit -m "primeiro commit" 
git branch -M main 
git remote add origin git@github.com:user/nome-do-repositoriogithub.git
git push -u origem principal
