# Trabalho_GitHub
📂 Projetos, testes e evolução constante na programação.


## Git – Sistema de Controle de Versões Distribuído
## 6.1 Evolução

O  Git é um sistema de controle de versões distribuído criado para armazenar, organizar e controlar alterações feitas em projetos. Ele foi desenvolvido para facilitar o trabalho em equipe, permitindo que várias pessoas trabalhem no mesmo projeto sem perder informações importantes.

Com o Git, é possível:
* Salvar versões do projeto;
* Recuperar versões antigas;
* Trabalhar em equipe;
* Organizar alterações;
* Acompanhar o histórico do projeto.

Atualmente, o Git é utilizado mundialmente em projetos escolares, profissionais e empresariais.

## 6.2 Comandos Iniciais
## 6.2.1 git init

O comando git init é utilizado para iniciar um repositório Git em uma pasta do computador.

# Como fazer
Passo 1

Criar uma pasta para o projeto.

Passo 2

Abrir o terminal dentro da pasta.

Passo 3

Executar o comando:

git init
# O que acontece?
* O Git começa a monitorar a pasta;
* É criada a pasta oculta .git;
* O projeto passa a possuir controle de versões.
# Exemplo
C:\Projetos\TrabalhoGit> git init
## 6.2.2 git add

O comando git add adiciona arquivos para a área de preparação do Git.

# Como fazer?
* Adicionar um único arquivo
git add index.html
* Adicionar todos os arquivos
git add .
# O que acontece?
* Os arquivos ficam preparados para o commit;
* O Git entende quais arquivos serão salvos.
# Exemplo
git add atividade.txt
## 6.2.3 git status

O comando git status mostra o estado atual do projeto.

# Como fazer?
Executar o comando:
git status
# O que ele mostra?
* Arquivos modificados;
* Arquivos novos;
* Arquivos adicionados;
* Arquivos que ainda não foram preparados.
# Exemplo
git status
## 6.2.4 git config

O comando git config é utilizado para configurar informações do Git.

# Como fazer
* Configurar nome do usuário
git config --global user.name "Nicolas"
* Configurar e-mail
git config --global user.email "email@gmail.com"
# O que acontece?
* O Git salva as informações do desenvolvedor;
* O nome e e-mail aparecem nos commits.
# Exemplo
git config --global user.name "João"
## 6.2.5 git commit

O comando git commit salva oficialmente as alterações do projeto.

# Como fazer
Executar o comando:
git commit -m "Primeiro commit"
# O que acontece?
* O Git cria um histórico da alteração;
* O projeto ganha uma nova versão;
* As alterações ficam registradas.
# Exemplo
git commit -m "Adicionado arquivo principal"
## 6.2.6 git log

O comando git log mostra o histórico de commits realizados.

# Como fazer
#Executar:
git log
# O que acontece?

# O Git mostra:

* Autor do commit;
* Data;
* Horário;
* Código do commit;
* Mensagem da alteração.
# Exemplo
git log
##  Versionamento em Nuvem
## 7.1 Serviços

Os serviços de versionamento em nuvem permitem armazenar projetos online utilizando Git.

## Vantagens
* Backup dos projetos;
* Compartilhamento;
* Trabalho em equipe;
* Segurança;
* Histórico de alterações.
## 7.1.1 GitHub

O GitHub é uma plataforma online utilizada para armazenar repositórios Git.

# Como utilizar
Passo 1

 Criar uma conta no GitHub.

Passo 2

Criar um repositório.

Passo 3

Adicionar arquivos do projeto.

Passo 4

Gerenciar versões do projeto.

# Características
* Repositórios públicos e privados;
* Compartilhamento de projetos;
* Muito utilizado por estudantes e empresas.

## 7.1.2 BitBucket

O Bitbucket é um serviço de hospedagem de repositórios Git criado pela Atlassian.

# Como utilizar
Passo 1

Criar uma conta.

Passo 2

Criar um repositório.

Passo 3

Adicionar membros da equipe.

Passo 4

Controlar versões do projeto.

# Características
* Integração com Jira;
* Ferramentas empresariais;
* Controle de permissões;
* Repositórios privados.


## 7.1.3 Azure Repository

O Azure DevOps Repos é o serviço de repositórios Git da Microsoft.

# Como utilizar
Passo 1

Criar uma conta Microsoft.

Passo 2

Acessar o Azure DevOps.

Passo 3

Criar um projeto.

Passo 4

Criar o repositório Git.

# Características
* Integração com ferramentas Microsoft;
* Controle empresarial;
* Segurança avançada;
* Automação de projetos.
