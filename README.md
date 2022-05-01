# Frontend

#### EBAC

# GIT

## Conceitos de Versionamento
- Histórico 
- Controle de versão
- Quem alterou
- O quê alterou 
- Quando alterou
- Todos os arquivos
- Evolução contínua

Arquivo A | Versão 1 | Versão 2
Arquivo B | Versão 1 | Versão 2

## Instalação do Git

## Criar conta no Github

## Clonar o projeto

## Comits

Informaçao de alteração
- Após testado todo seu código
- git add *
- git commit -m "mensagem"
- git push (enviar alterações para o repositório)
- git pull (puxar alteração do repositório)

## GitFlow
Fluxo do Git
ultima atualização

### Branchs 
são ramificações / versões paralelas

- main/master (vai para produção, quando o projeto paralelo é publicado)
- develop
- DOD Definition of Done: critérios de aceite
- versionamento 1.0.0

git checkout -b dev (criar uma branch)
git checkout martes (mudar de branch)

### Merge
Mescla de branchs
Você pode precisar resolver conflitos manualmente
git merge main


### Pull Requests
Mescla de branchs no repositório
Permite code review
O repositório resolve os conflitos automaticamente

### Configura o Gitflow
git flow init
git flow feature start {nome-da-feature}

