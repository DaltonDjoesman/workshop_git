# Git e GitHub para quem está a começar

Workshop prático e reutilizável: uma apresentação interativa, guias passo a passo e um pequeno exercício. No fim, terás uma cópia deste repositório na tua conta GitHub com uma alteração e um commit feitos por ti.

## Para quem é

Para qualquer pessoa que nunca tenha usado Git. Não precisas de saber programar.

## Pré-requisitos

- Um computador com Windows, macOS ou Linux, e permissão para instalar programas (ou Git já instalado).
- Um email para criar a conta GitHub (gratuita).
- Ligação à internet. Conta com cerca de 90 minutos para fazer tudo.

## Como seguir

1. **Slides:** abre a [apresentação interativa](https://daltondjoesman.github.io/workshop_git/). A teoria segue `status → add → commit → push → log → pull → branch → merge → fork`; depois, os slides acompanham toda a prática.
2. **VS Code:** confirma que o [Visual Studio Code](guia/instalar-vscode.md) abre; vais usá-lo para editar um ficheiro.
3. **WSL (opcional, só Windows):** vê a opção [WSL + Ubuntu](guia/wsl-opcional.md). Não é necessária: Git Bash chega.
4. **Conta GitHub e Git:** cria ou abre a tua conta em [github.com/signup](https://github.com/signup) e prepara o Git pelo guia de [Windows](guia/instalar-windows.md), [macOS](guia/instalar-macos.md) ou [Linux](guia/instalar-linux.md).
5. **Fork e Clone:** cria um **Fork** deste repositório na tua conta e clona a tua cópia. O [roteiro](guia/roteiro.md) explica cada passo.
6. **Exercício:** personaliza o [modelo](exercicio/README.md) e faz `git status` → `git add` → `git commit` → `git push` → `git log`.

O **Fork** é necessário: cria uma cópia na tua conta, para onde podes enviar as tuas alterações. Se clonasses diretamente este repositório, não terias permissão para fazer `push`.

## Ficheiros

| Ficheiro | Para quê |
| --- | --- |
| [`docs/slides/index.html`](docs/slides/index.html) | Apresentação (publicada no [GitHub Pages](https://daltondjoesman.github.io/workshop_git/)) |
| [`docs/index.html`](docs/index.html) | Página de entrada que redireciona para os slides |
| [`docs/assets/workshop-qr.svg`](docs/assets/workshop-qr.svg) | QR code para este repositório (slide 16) |
| [`guia/roteiro.md`](guia/roteiro.md) | Passos e verificações durante a sessão |
| [`guia/instalar-vscode.md`](guia/instalar-vscode.md) | Verificar ou instalar o editor |
| [`guia/instalar-windows.md`](guia/instalar-windows.md) · [`instalar-macos.md`](guia/instalar-macos.md) · [`instalar-linux.md`](guia/instalar-linux.md) | Preparar o Git no teu sistema |
| [`guia/wsl-opcional.md`](guia/wsl-opcional.md) | Linux dentro do Windows (opcional) |
| [`guia/erros-frequentes.md`](guia/erros-frequentes.md) · [`guia/perguntas.md`](guia/perguntas.md) | Ajuda rápida quando algo não corre como esperado |
| [`guia/recursos.md`](guia/recursos.md) | Documentação oficial e repositórios reais para explorar |
| [`exercicio/README.md`](exercicio/README.md) | O ficheiro que vais personalizar no teu Fork |

## O que deves conseguir mostrar no fim

- O endereço do teu Fork, na tua conta GitHub.
- O texto que alteraste em `exercicio/README.md`.
- Um commit teu na página **Commits** do Fork.

Se ficares bloqueado, consulta os [erros frequentes](guia/erros-frequentes.md) e pede ajuda a quem está a orientar a sessão. Nunca partilhes palavras-passe, códigos de autenticação ou tokens.

## Fontes

[Pro Git](https://git-scm.com/book/en/v2) e documentação do [Git](https://git-scm.com/docs), [GitHub Docs](https://docs.github.com/), [Microsoft Learn (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install) e [Visual Studio Code](https://code.visualstudio.com/docs). Os ícones do exercício vêm de [Devicon](https://github.com/devicons/devicon) e os badges de [Shields.io](https://shields.io/).
