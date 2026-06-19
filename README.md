# kotatsu-dl
Um downloader de mangás multiplataforma e fácil de usar, com suporte a diversas fontes de mangás.

[![Sources count](https://img.shields.io/badge/dynamic/yaml?url=https%3A%2F%2Fraw.githubusercontent.com%2FYakaTeam%2Fkotatsu-parsers%2Frefs%2Fheads%2Fmaster%2F.github%2Fsummary.yaml&query=total&label=manga%20sources&color=%23E9321C)](https://github.com/YakaTeam/kotatsu-parsers)  [![AUR version](https://img.shields.io/aur/version/kotatsu-dl-git?color=%233584E4)](https://aur.archlinux.org/packages/kotatsu-dl-git)

![scr](https://github.com/user-attachments/assets/1f1d28f7-9bc1-4d55-8491-43e21242755f)

# Instalação

### Para usuários do Windows/Linux/Mac
Basta baixar o [último release](https://github.com/YakaTeam/kotatsu-dl/releases/latest) e usá-lo.

```shell
java -jar ./kotatsu-dl.jar
```
O Java 17 ou posterior é obrigatório.

### Para usuários do ArchLinux
O pacote está disponível no AUR (build antiga do [KotatsuApp](https://github.com/YakaTeam/kotatsu-dl))

```shell
yay -S kotatsu-dl-git
```
Ao instalar a partir do AUR, o comando `kotatsu-dl` estará disponível em todo o sistema.

# Como Usar

```shell
Uso: kotatsu-dl [<opções>] <link>

Opções:
  --dest, --destination=<valor>  Caminho do arquivo ou diretório de saída. O padrão é o diretório atual
  --format=(cbz|zip|dir)         Formato de saída
  -j, --jobs=<int>               Número de tarefas paralelas para download
  --throttle                     Desacelera o download para evitar o bloqueio do seu endereço IP pelo servidor
  --chapters=<números ou faixa>  Números dos capítulos para download. Pode ser um único número ou faixa, ex. "1-4,8,11" ou "all" (todos)
  -v, --verbose                  Mostra mais informações
  --sources                      Mostra a lista de fontes de mangás suportadas e sai
  -h, --help                     Mostra esta mensagem e sai

Argumentos:
  <link>  Link direto para o mangá copiado do navegador
```
