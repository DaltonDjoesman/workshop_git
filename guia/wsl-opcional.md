# WSL no Windows: percurso opcional

[Voltar ao início](../README.md) · [Roteiro](roteiro.md) · [Slide 18](https://daltondjoesman.github.io/workshop_git/slides/#slide-18)

**Para este workshop, Git Bash chega no Windows.** O WSL (Windows Subsystem for Linux) permite usar Ubuntu no computador, mas a instalação pode exigir privilégios de administrador e reinício. Não precisas dele para terminar o exercício.

## Se já usas WSL

Abre a distribuição Linux, por exemplo **Ubuntu**, e segue o [guia Linux](instalar-linux.md) **dentro desse terminal**. O Git e a configuração de nome, email e autenticação dentro de WSL são distintos dos do Git Bash no Windows. Faz o clone numa pasta do teu diretório pessoal Linux, como `~/workshop`, para manter o percurso simples.

Usa o URL HTTPS do teu próprio *fork*. Se já tens Git Credential Manager configurado para WSL, podes continuar a usá-lo. Caso contrário, a opção `gh auth login --web --git-protocol https` e `gh auth setup-git` do [guia Linux](instalar-linux.md) permite entrada pelo navegador. Não assumas que teres entrado no GitHub no Git Bash autentica automaticamente o Git dentro de WSL.

## Se quiseres instalar WSL e Ubuntu

1. Confirma que tens uma versão de Windows compatível e acesso de administrador. Segue as [instruções oficiais da Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install).
2. Abre **PowerShell como administrador** e executa o comando do slide 18:

   ```powershell
   wsl --install
   ```

3. Reinicia o computador quando for pedido. Na primeira abertura do Ubuntu, cria o utilizador Linux solicitado.
4. No terminal Ubuntu, segue o [guia Linux](instalar-linux.md).

O comando instala Ubuntu por predefinição. Se apresentar ajuda ou pedir uma distribuição, segue as [variações documentadas pela Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install). Se a instalação ou reinício atrasar, continua com [Git Bash](instalar-windows.md) e termina a configuração do WSL mais tarde.

Fontes: [instalação do WSL — Microsoft Learn](https://learn.microsoft.com/en-us/windows/wsl/install), [Git Credential Manager no WSL](https://github.com/git-ecosystem/git-credential-manager/blob/main/docs/wsl.md).
