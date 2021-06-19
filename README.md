# devops

* Containers - Tecnologias chave
- `namespace` - isolam os processos dos containers e também os pontos de montagem, diretórios, discos, redes, etc.
- `cgroups` - limita acesso aos recursos da máquina.
- `union mounting` - característica dos sistemas de arquivos que trabalham com camadas, camadas estas que podem ser compartilhadas.

* Images
 - onde a aplicação está localizada, com suas respectivas dependências, bibliotecas, binários e arquivos relacionados.
 - É a referência para que a aplicação funcione em qualquer ambiente, a imagem é usada para construir este estado (container).
 - Construída em uma ou mais camadas.
