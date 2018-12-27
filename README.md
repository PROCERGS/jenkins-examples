# Exemplos Jenkins

Exemplos de Jenkinfiles para diversos ambientes.

# PHP

Na pasta `php/` você encontra um exemplo de `Jenkinsfile` utilizando o comando `archive` do composer para criar o pacote. Nos comentários você também pode verificar como criar o pacote manualmente através do Jenkins.

**IMPORTANTE**: o arquivo `sonar-project.properties` precisa estar na raíz do projeto, junto do `Jenkinsfile` e deve ser configurado de acordo com a aplicação. Na maioria dos casos basta configurar a *'project key'*.

# Node.js

Na pasta `node/` você encontra um exemplo de `Jenkinsfile` utilizando *Node.js*.

**IMPORTANTE**: o arquivo `sonar-project.properties` precisa estar na raíz do projeto, junto do `Jenkinsfile` e deve ser configurado de acordo com a aplicação. Na maioria dos casos basta configurar a *'project key'*.
