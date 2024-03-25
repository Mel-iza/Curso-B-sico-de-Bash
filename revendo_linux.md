## 1.1 - Revendo o terminal do Linux 

O shell é uma camada do sistema operacinal responsável por fazer uma interface entre o usuário e o kernel.

- O shell é um interpretador de comandos
- Esses comandos podem vir da entrada padrão (terminal) ou de um arquivo (script).

Além de permitir a execução de comandos, o shell possui os mesmos recursos de qualquer linguagem de programação de alto nível, como:
- <b>manipulação de variáveis
- Estruturas de controle de fluxo
- Laços de repetição (loops), etc. </b>

Essa característica é o que nos permite criar scripts, automatizar tarefas e criar programas para as mais diversas finalidades.


<br> Envolve a automação de diversas tarefas.

## 1.2 - O prompt da linha de comando

Quando iniciado, o shell procura suas configurações globais, as configurações do usuário e, finalmente, exibe um indicador chamado 'prompt de comando', que é onde o usuário irá digitar seus comandos.


Prompt típico do Debian GNU/Linux: `usuario@hostname:~/caminho$`
Utilizaremos o prompt dessa maneira ao longo do curso: <br>

`:~$` - para comandos executados como usuário normal <br>
`:~#` - para comandos executados como usuário 'root'

## 1.3 - Tipos de Shell

Existem vários tipos de shell, entre eles: <br>
- `sh` - Bourne shell
- `bash` - Bourne Again Shell
- `rbash` - Restricted Bash
- `dash` - O shell padrão do BSD
- `zsh` - (z-shell) Zero shell
- `fish` - Friendly Interactive Shell


## 1.4 - O que é o Bash

O bash, ou Bourne Again Shell é uma implementação aprimorada de comandos Bourne Shell (sh) que apresenta todos os recursos e características de uma linguagem de programação de alto nível
<br> Por configuração, o bash pode ser compatível com os padrões POSIX, possibilitando que seus scripts sejam executados por diversos sistemas "unix like" sem alterações.

<br> Desenvolvido originalmente por Brian Fox, e continuando por Chat Ramey, o bash foi lançado em 1989 como um software livre.

<br> O bash é o shell padrão do Projeto GNU e da maioria das distribuições Linux.

## 1.5 - Os comandos _builtin_ do bash

Esses tipos de comandos são os comandos internos do bash.


