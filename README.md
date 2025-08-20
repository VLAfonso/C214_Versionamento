# C214_Versionamento
Repositório destinado à atividade de versionamento da disciplina C214 - Engenharia de Software.
O objetivo é a capacitação no gerenciamento de repositórios, versionamento de código e resolução de conflitos.

# :pencil: Descrição
O projeto apresenta as informações presentes nas 5 primeiras linhas do conjunto de dados South German Credit, obtido do [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/573/south+german+credit+update).

# :gear: Configuração e Execução
1. Clonar o repositório
```bash
git clone https://github.com/VLAfonso/C214_Versionamento.git
cd C214_Versionamento
```
2. Criar Banco de Dados

[Executar](statlog-germancredit.sql) o arquivo `statlog-germancredit.sql` para criar e inserir os dados do conjunto de dados South German Credit.

3. Abrir no IntelliJ

Abrir o IntelliJ, acessar File > Open e escolha a pasta do projeto.

3. Configurar Credenciais

No arquivo `Main.java`, ajuste as as credenciais de conexão.
```Java
String user = "USUARIO";
String password = "SENHA";
```

4. Instalar Dependências
```bash
cd ExercicioDependencias
mvn package
```
5. Executar

No IntelliJ, acesse o arquivo da classe `Main.java` pelo caminho `src\main\java\org\example\Main.java` e clique no botão `Run`.


# :pushpin: Processos realizados

Os processos realizados e seus respectivos commits estão descritos abaixo:

1. Criação do Repositório  
Foi criado o repositório público `C214_Versionamento` para o projeto, com o arquivo .gitignore para Java.  
[Commit a651f19](https://github.com/VLAfonso/S202-Projeto-MongoDB-Neo4j/blob/main/README.md) - Initial commit

2. Adição dos Arquivos do Projeto  
Foi adicionado todos os arquivos do projeto desenvolvido na aula anterior e o arquivo de importação dos dados do MySQL.  
[Commit 82d8197](https://github.com/VLAfonso/C214_Versionamento/commit/82d819712199e7976f466cc3e67406b51bf954c2) - Add exercício de dependências desenvolvido na aula anterior  
[Commit 5d758cf](https://github.com/VLAfonso/C214_Versionamento/commit/5d758cfc7493bbe2f21cef7260163d70fcfbcfc4) - Add arquivo de importação dos dados do MySQL

3. Colaboração e Pull Request  
Foi adicionada ao projeto a colaboradora [Lanna C. e S.](https://github.com/LannaCeS) e realizada uma alteração no limite do número da pesquisa na query.  
[Commit 829f4ff](https://github.com/VLAfonso/C214_Versionamento/commit/829f4ff71d46c6942917c5fe736e92049827af87) - Alteração da restrição de pesquisa no BD para 3  
[Commit fb3b419](https://github.com/VLAfonso/C214_Versionamento/commit/fb3b419208e654510b76de943a513a5c239fd391) -  Alteração do limite da busca no BD para 4  
[Commit 5963aa8](https://github.com/VLAfonso/C214_Versionamento/commit/5963aa8989318176a3d866824b436eeb61587cf1) - Merge pull request #1 from VLAfonso/feature

4. Simulação e Resolução de Conflitos  
Foi realizado o update do `README.md` com os colaboradores e com a configuração e execução em dois commits diferentes sem atualizar o repositório local, causando um conflito. A resolução foi deixar os dois conteúdos, mantendo todas as informações necessárias no arquivo, por meio de um merge, utilizando o VSCode e o terminal.  
[Commit 10da602](https://github.com/VLAfonso/C214_Versionamento/commit/10da6027f0bc8c1573f24fc4f0e449d7496e8db2) - Readme update com colaboradores   
[Commit 4c11de5](https://github.com/VLAfonso/C214_Versionamento/commit/4c11de5d7c7b204334cb34fb2739bfd9205a4bf6) - Add configuração e execução no README  
[Commit 3cfde43](https://github.com/VLAfonso/C214_Versionamento/commit/3cfde437115cc85a0f432bbf7ed10259b64fe8d5) - Merge branch 'main' of https://github.com/VLAfonso/C214_Versionamento

5. Atualizações do README  
Foram adiciondas as informações do `README.md`.  
[Commit 6fb7945](https://github.com/VLAfonso/C214_Versionamento/commit/6fb794592420902a65ecacf8ecf75381f6be310f) - Add descrição ao README   
[Commit 10da602](https://github.com/VLAfonso/C214_Versionamento/commit/10da6027f0bc8c1573f24fc4f0e449d7496e8db2) - Readme update com colaboradores   
[Commit 4c11de5](https://github.com/VLAfonso/C214_Versionamento/commit/4c11de5d7c7b204334cb34fb2739bfd9205a4bf6) - Add configuração e execução no README  
[Commit 3fe8977](https://github.com/VLAfonso/C214_Versionamento/commit/3fe89770c89df2cb39ea5b00dc706abd29c66d3f) - Add emojis ao README

# :busts_in_silhouette: Colaboradores
[Virgínia Letícia](https://github.com/VLAfonso)

[Lanna C. e S.](https://github.com/LannaCeS)
