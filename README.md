# Estudo de sala
Projeto de estudo de arquivos do tipo markdown (.md)

Exemplos:
**Trecho em negrito.**

*Trecho em itálico.*

### Markdown
Markdown é uma linguagem simples de marcação. Markdown converte seu texto em HTML válido. Markdown é frequentemente usado para formatar arquivos README, para escrever mensagens em fóruns de discussão online e para criar rich text usando um editor de texto simples. 

<img alt="Logo Markdown" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/800px-Markdown-mark.svg.png" width="30%" height="30%">

### Git
Git é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo.

<img alt="Logo Git" src="https://blog.hostone.com.br/wp-content/uploads/2019/07/blog-git.jpg" width="30%" height="30%">

Clicando <a href="https://git-scm.com/">AQUI</a> você poderá acessar o Git.

### GitHub
GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo.

<img src="https://enotas.com.br/blog/wp-content/uploads/2021/02/GitHub.jpg" width="30%" height="30%">

Clicando <a href="https://github.com/">AQUI</a> você poderá acessar ao GitHub.

### Fluxo de trabalho entre repositório local e remoto

<img src="https://i.stack.imgur.com/1wPcg.png">

* git init: Cria um repositório Git vazio ou reinicializa um já existente.
* git add: Adicione o conteúdo do arquivo ao índice.
* git status: Exibe o a condição da árvore de trabalho.
* git commit: Grava as alterações feitas no repositório.
* git branch: Lista, cria ou exclui ramificações.
* git remote: Gerencie o conjunto dos repositórios monitorados.
* git push:  Atualiza as refs remotas junto com os objetos associados a ela.

### Processo prático

1.Acessar o repositório local e executar o git bash(terminal git)dentro deste diretório.

2.No git bash executar o comando git init.

3.Executar o comando git add.

4.executar o comando git commit -m "first commit".

5.Após a criação do repositório remoto no Github, executar o comando:git remote add origin "url do repositório remoto".

6.Executar o comando git push-u origin main.

**OBS.: Para a realização dos procedimentos anteriores,é necessário a autenticação do usuário do Github no terminal do Git (user.name,user.email,token).
