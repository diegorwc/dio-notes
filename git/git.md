# Como configurar
## Comando para configurar o usuário no git  
`git --config global user.name "<NomeDeUsuario>"`

## Comando para configurar o email no git
`git --config global user.email <seuemail@email.com>`

Obs: _Como pode ser deduzido intuitivamente, a flag global serve para realizar essas configurações globalmente. Se por algum motivo você desejar realizar uma configuração especifica de usuário e e-mail em algum projeto, omita a flag __global__._

# Comandos básicos
## Adicionar vários arquivos para o stage
`git add .` OU `git add *`

## Realizar o commit dos arquivos do stage
`git commit -m "<MensagemBreveComInformaçõesRelevantes>"`

## Adicionar um servidor remoto (e.g. um repositório no Github)
`git remote add origin <EndereçoDoRepositorio.git>`

## Listar servidores remotos configurados no repositório
`git remote -v`

## Enviar (empurrar) código para o servidor remoto configurado como "origin"
`git push origin main`
Obs: _Origin é um aliás para o endereço do servidor remoto. Main é o nome da branch que será enviada ao servidor remoto._

## Atualizar (puxar) código do repositório remoto "origin" para a branch local "main"
`git pull origin main`
