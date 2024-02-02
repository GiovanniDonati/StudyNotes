>**Versão em Português**
# Versionamento de código Git e GitHub
## Comandos

* <code>git init</code>
    >Dá início ao repositório.

* <code>git status</code>
    >Informa a situação do da pasta, com os arquivos e suas alterações.

* <code>git add</code>
    ><code>git add.</code>
    >Adiciona os aquivos a área de stagging.

* <code>git commit</code>
    ><code>git commit -a -m "mensagem"</code>
    >Prepara o código para ser lançado, atraves do Git, para um repositório remoto.
    >*-a* : Significa que todos os arquivos devem ser commitados.
    >*-m* : Significa que estou adicionando uma mensagem.

* <code>git branch</code>
    ><code>git branch -M main</code>
    >Informa que o commit será feito na branch main, tornando-a a branch principal.

    >Apenas *git branch*, mostra todas as branchs do repositório   

* <code>git remote add origin *link do repositório*</code>
    >Para enviar o commit do repositório local para o repositório remoto, indicado pelo o link.

* <code>git push</code>
    ><code>git push -u origin main</code>
    >Faz upload de um repositório local para um repositório remoto, fazendo uma mesclagem das alterações.
    
    ><code>git push --set-upstream origin teste</code>
    >Faz um push para o repositório remoto, criando uma nova branch chamada teste, caso ela já não exista no repositório remoto.


* <code>git checkout</code>
    ><code>git checkout -b "teste"</code>
    >*-b* : Cria uma nova branch para fazer as alterações, sem mudar a branch main(principal), mudando para a branch criada.

    ><code>git checkout main</code>
    >Muda a branch para a main.

    ><code>git checkout .*url do arquivo*</code>
    >Deleta o arquivo selecionado do commit

* <code>git merge</code>
    ><code>git merge teste</code>
    >Une a branch selecionada com o branch atual.

* <code>git pull</code>
    >Faz download de um repósitorio remote para o repositório local.

* <code>git clone</code>
    ><code>git clone *url* **Nome do arquivo**</code>
    >Criar um clone apartir da branch selecionada, através do link selecionado.

* <code>git log</code>
    >Histórico dos commits.

* <code>clear</code>
    >Limpa a tela de código.

>Existe ainda o *Fork*, que gera um clone de um repositório na conta do GitHub, e após ser feito mudanças no mesmo, pode ser solicitado um *Pull Request* ao dono do repositório, sendo que antes é feito uma avaliação para evitar conflitos do código com o repositório original. 


*Por [Giovanni Donati](https://github.com/GiovanniDonati).*