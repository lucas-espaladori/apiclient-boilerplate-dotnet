# API Client boilerplate template

💡 🏗️ A boilerplate API client template for .NET API client wrappers

---

## About

This is a **template repository** that sets the basic code and infrastructure for a repository/solution in **.NET C#** to create an **API client wrapper** (sometimes known as **SDK**).

---

## Instructions

> **Warning**
>
> The automated process listed below only works in a **Windows** environment. A **Linux/MAC** setup is on the way but currently is not supported, so it should be done manually

### Automated process

- Click on the green button **USE THIS TEMPLATE**
- Give a name to your new project/repository
- Clone your newly created repository to your machine
- Execute/run the file `initial-setup.bat` or `initial-setup.ps1` and follow the instructions on the prompt/terminal.

### Manual process

- Click on the green button **USE THIS TEMPLATE**
- Give a name to your new project/repository
- Clone your newly created repository to your machine
- Delete this file (`README.md`) and rename `README.template.md` to `README.md`
- Change the `appveyor.yml` with your **tokens** (use secure tokens) or use your preferred CI tool (Circle CI, GitHub Actions, Jenkins, Team City, Azure DevOps)
- Change `SolutionName.sln` to your solution/project name.
- Change project name (`SolutionName.csproj`, `SolutionName.Tests.csproj`, `SolutionName.IntegrationTests.csproj`) and namespace inside directories `Src` and `Tests`.
- Change the package name in the `SolutionName.csproj`.
- Change the *main project* reference in the tests project in files `Tests/SolutionName.Tests.csproj` and `Tests/SolutionName.IntegrationTests.csproj`
- Fix in the `README.md` the path of the badges. (change all *{username}/{repo}* tokens with your own data).
- Add to `README.md` usage instructions of your client/SDK.
- Update `_config.yml` with project details (github.io docs website)

---

## License

Licensed under: **MIT license** ([LICENSE](https://github.com/guibranco/apiclient-boilerplate-dotnet/blob/main/LICENSE) or [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT)).

This will be also the **LICENSE** of your API client wrapper / SDK, but you are free to change it for another that suits your needs.







# Modelo padrão do cliente API

💡 🏗️ Um modelo padrão de cliente de API para wrappers de cliente de API .NET

---
## Sobre

Este é um ** modelo repositório** que define o código básico e a infraestrutura para um repositório/solução em **.NET C#** para criar um **wrapper de cliente API** (também conhecido como **SDK**).

---

## Instruções

> **Aviso**
>
> O processo automatizado listado abaixo funciona apenas em ambientes **Windows**. Uma configuração para **Linux/MAC** está em desenvolvimento, mas atualmente não é suportada, portanto, deve ser feita manualmente.

### Processo Automatizado

- Clique no botão verde **USE THIS TEMPLATE**
- Dê um nome ao seu novo projeto/repositório
- Clone o repositório recém-criado para a sua máquina
- Execute o arquivo `initial-setup.bat` ou `initial-setup.ps1` e siga as instruções no prompt/terminal.

### Processo Manual

- Clique no botão verde **USE THIS TEMPLATE**
- Dê um nome ao seu novo projeto/repositório
- Clone o repositório recém-criado para a sua máquina
- Exclua este arquivo (`README.md`) e renomeie `README.template.md` para `README.md`
- Altere o `appveyor.yml` com seus **tokens** (use tokens seguros) ou use sua ferramenta de CI preferida (Circle CI, GitHub Actions, Jenkins, Team City, Azure DevOps)
- Altere `SolutionName.sln` para o nome da sua solução/projeto.
- Altere o nome do projeto (`SolutionName.csproj`, `SolutionName.Tests.csproj`, `SolutionName.IntegrationTests.csproj`) e o namespace dentro dos diretórios `Src` e `Tests`.
- Altere o nome do pacote no `SolutionName.csproj`.
- Altere a referência do *projeto principal* nos projetos de teste nos arquivos `Tests/SolutionName.Tests.csproj` e `Tests/SolutionName.IntegrationTests.csproj`
- Corrija no `README.md` o caminho dos crachás. (substitua todos os tokens *{username}/{repo}* com seus próprios dados).
- Adicione ao `README.md` instruções de uso do seu cliente/SDK.
- Atualize o `_config.yml` com detalhes do projeto (site de documentação github.io)

---

## Licença

Licenciado sob: **Licença MIT** ([LICENSE](https://github.com/guibranco/apiclient-boilerplate-dotnet/blob/main/LICENSE) ou [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT)).

Esta também será a **licença** do seu wrapper de cliente API / SDK, mas você está livre para alterá-la por outra que atenda às suas necessidades.
  
