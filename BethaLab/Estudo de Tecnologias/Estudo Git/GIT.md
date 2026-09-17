O Git é uma ferramenta de versionamento de código, que auxilia na construção de software em conjunto (nao é só isso que faz, mas no nosso contexto vai ser usado pra esse fim).

O fluxo de trabalho utilizando o Git é como se fosse uma árvore, onde o sistema principal é o tronco maior da árvore, e você pode contribuir na produção desse software criando branches (galhos) para realizar suas alterações no código sem que afete o código base. 

Conforme são feitas essas mudanças, você pode ir criando saves do seu código, pra poder voltar neles caso uma alteração tenha dado pau. Esses saves são chamados de ```commits```

Abaixo tem uma imagem ilustrativa do fluxo do Git

![[Pasted image 20260917162427.png]]

## Principais comandos e suas atribuições

#### git init
Transforma a pasta atual em um repositório Git local.

#### git clone URL
Baixa um repositório remoto em sua maquina.

#### git status
Mostra o estado atual dos arquivos modificados.

#### git add ```arquivo```
Move o arquivo que você escreveu depois do codigo para a staging area. Pode-se usar ```git add .``` pra adicionar tudo.

#### git commit -m "mensagem"
Salva os arquivos da staging area no histórico do repositorio. Existem padrões de mensagem de cada empresa, como "fix" para correção, "docs" pra documentação e etc

#### git branch ```nome```
Cria uma ramificação do código base

#### git checkout ```nome``` || git switch ```nome```
Troca a branch

#### git merge ```nome_da_branch```
Junta as alterações da branch especificada com a branch que você está no momento

#### git push
Envia seus commits locais para o repositório remoto

### git pull
Puxa as atualizações do repositório remoto e já mescla com o seu código local