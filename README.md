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


# :busts_in_silhouette: Colaboradores
[Virgínia Letícia](https://github.com/VLAfonso)

[Lanna C. e S.](https://github.com/LannaCeS)
