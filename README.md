# CursinhoEACH

Sistema em **.NET Core MVC** para auxiliar o Cursinho Popular EACH – USP no controle de assiduidade e desempenho dos alunos.

---

## Pré-requisitos

1. **Instalar o .NET SDK 9.0**  
   Baixe e instale o SDK compatível com seu sistema operacional:  
   [Download .NET 9.0.304](https://dotnet.microsoft.com/pt-br/download/dotnet/9.0)

   - Windows: escolha **x64 Installer** (a maioria dos PCs).  
   - macOS: escolha **x64** ou **Arm64**, dependendo do processador.  
   - Linux: siga as instruções do gerenciador de pacotes.

2. **Clonar o repositório**:
   ```bash
        git clone https://github.com/seu-usuario/CursinhoEACH.git
        cd CursinhoEACH
   ```

3. **Executar projeto**:
    - Confiar no certificado HTTPS de desenvolvimento:
    ```bash
        dotnet dev-certs https --trust
    ```
    - Rodar a aplicação:
    ```bash
        dotnet run
    ```
    - Aplicação ficará disponível em:
     ```
        https://localhost:<port#>
    ```
