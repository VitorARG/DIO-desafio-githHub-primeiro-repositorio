# git config
Um dos comandos git mais usados ​​é o git config que pode ser usado para definir valores de configuração específicos do usuário como e-mail, algoritmo preferido para diff, nome de usuário e formato de arquivo etc. Por exemplo, o seguinte comando pode ser usado para definir o email:

git config --global user.email sam@google.com
# git init
Este comando é usado para criar um novo repositório GIT. Uso:
git init

# git add
O comando git add pode ser usado para adicionar arquivos ao índice. Por exemplo, o seguinte comando irá adicionar um arquivo chamado temp.txt presente no diretório local para o índice:
git add temp.txt

# git clone
O comando git clone é usado para fins de verificação de repositório. Se o repositório estiver em um servidor remoto, use:
git clone alex@93.188.160.58:/path/to/repository
Por outro lado, se uma cópia de trabalho de um repositório local for criada, use:
git clone /path/to/repository.

# git commit
O comando git commit é usado para confirmar as alterações na cabeça. Tenha em atenção que quaisquer alterações efetuadas não irão para o repositório remoto. Uso:
git commit –m “coloque sua mensagem aqui”

# git status
O comando git status exibe a lista de arquivos alterados juntamente com os arquivos que ainda não foram adicionados ou confirmados. Uso:
git status

# git push 
é outro dos comandos git básicos mais usados. Um simples envio envia as alterações feitas para o ramo mestre do repositório remoto associado ao diretório de trabalho. Por exemplo:
git push origin master

# git remote
O comando git remote permite que um usuário se conecte a um repositório remoto. O comando a seguir lista os repositórios remotos atualmente configurados:
git remote –v