# Configurando seu git
- Configure o VSCode como seu editor de texto do git padrão com `git config --global core.editor "code --wait"`
- Configure seu nome com `git config --global user.name seu-nome`
- Configure seu email com `git config --global user.email seu-email`
- Gere uma chave SSH com `ssh-keygen -t ed25519 -C "seu-email@dominio.com"` (Caso já tenha feito isso, pode pular esse e os passos seguintes)
- Vá para a pasta em que foi criado seu par de chaves e abra o id_rsa.public que contém a sua chave criptográfica pública no VSCode, e copie o conteúdo dela
- Cola ela na "chave" na página `https://github.com/settings/ssh/new`, o nome dela já deverá ser preenchido automaticamente.

# Exercicios

- Faça o fork desse projeto no GitHub para a sua conta
- Faça o clone do fork do seu projeto
- Crie uma branch com o seu nome utilizando `git branch seu-nome`
- Faça o exercicio da pasta "alunos"


