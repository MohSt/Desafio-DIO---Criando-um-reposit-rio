# Desafio-DIO - Criando um repositório
### Passo a passo de como criar um repositório

##### ETAPA 1

O primeiro passo é entrar no site do GitHub <https://github.com>

Na aba do topo direito clique no botão "+" e em seguida, na opção "New repository"

Complete as descrições necessárias e escolha se público, em que outras pessoas terão acesso, ou privado.

Marque a opção "Add a README file" e no fim da págica clique no botão "Create repository"

##### ETAPA 2

Caso ainda não tenha instalado, baixe e instale o software Git (BASH)
Link para download: https://git-scm.com/download/

Crie uma pasta local no seu computador/dispositivo onde será salvo os arquivos do repositório.

Estando na pasta, clique com o botão direito do mouse na opção: "Git BASH here"
O programa irá abrir e então executaremos nossa próxima etapa com a linguagem do git.

##### ETAPA 3

Na página do seu repositório criado clique no botão verde "code", ele dará acesso aos links de acesso ao repositório. Escolha um link e copie-o.

Uma vez copiado, vamos ao Git BASH.

Digite o comando: git clone link
Esse "link" é o que foi copiado do github.
Ex: git clone https://github.com/MohSt/Desafio-DIO---Criando-um-reposit-rio.git

Após clonado, as modificações feitas na máquina precisarão serem enviadas ao repositório. Fazemos isso com o comando: git add .

OBS: SEMPRE QUE PRECISAR-MOS PODEMOS USAR O COMANDO git status PARA VER SE HÁ ALGUMA MODIFICAÇÃO QUE PRECISA SER ATUALIZADA OU ADICIONADA À PÁGINA DO GITHUB OU À PASTA LOCAL.

Em seguida, usamos o comando: git commit -m ""
Entre os asteríscos deve estar a descrição do que está sendo feito.
Por exemplo: git commit -m "Inclusão das anotações"

E para finalizar e adicionar ao site do github, usamos o comando: git push origin main

Atualize a página e confira se as modificações foram adicionadas.
