# website
Site institucional de Hugo Terças.

## Setup
O site está feito sobre o gerador de sites estáticos [Hugo](https://gohugo.io), com o tema [Academic](https://sourcethemes.com/academic/).

## Comandos do Gerador Hugo
Os seguintes comandos consideram uma instalção do Hugo com recurso ao [Snapcraft](https://snapcraft.io/).

Iniciar um servidor local para desenvolvimento com refrescamento automático, sempre que são alterados ficheiros:
```
snap run hugo serve
```

## Commandos básicos [Git](https://git-scm.com/)

- Estado do repositório:
```
git status
```

- Adicionar ficheiros e pastas novos ao repositório:
```
git add [nome-ficheiro-ou-pasta] [outro-ficheiro-ou-pasta]
```

- Adicionar alterações (ficheiros já existentes):
Pode-se recorrer ao comando anterior, mas é possível ver um pequeno *diff* local para cada uma das alteraçes, revendo o que se vai adicionar usando:
```
git add -p
```

- Podem ser ainda adicionadas, automaticamente, todas as alteraçes a ficheiros que já estão no repositório (i.e. os que não são novos):
```
git add -u
```

- Commit de alterações:
```
git commit -m "Mensagem de commit"
```

- Enviar alterações para repositório remoto:
```
git push origin master
```
