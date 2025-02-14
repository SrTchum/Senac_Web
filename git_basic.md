# COMANDOS BASICOS DO GIT
git config --global user.name "Seu Nome" -> Inclui a credencial do seu nome
git config --global user.email "seu_email@example.com" -> Inclui a credencial do seu e-mail
git init -> Inicializa o repositório local.
git status -> Exibe se os arquivos/pastas estão adicionados ao repositório.
git add nome_do_arquivo -> Adiciona o arquivo ao repositório local.
git add . -> Adiciona todos os arquivos modificados ou criados no repositório local. 
git branch -M main -> Altera o nome da branch principal de master para main
git commit -m "Mensagem de Atualização" -> Cria u commit para que seja realizado um novo versionamento. 
git log -> Lista todos os commits que foram realizados. 
git log --oneline --graph --decorate -> Forma compacta de exibir os commits. 
git remote add origin https://github.com/SrTchum/Senac_Web.git -> Realiza a sincronizção do repositório local com o remoto. 
git push -u origin main -> envia as informações do repositório local para o remoto. 
