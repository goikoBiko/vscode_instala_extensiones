# vscode_instala_extensiones
Repositorio que contiene los archivos necesarios para facilitar la instalación de una lista de extensiones
Para instalar una lista de extensiones en tu vscode: 

dentro de la carpeta de proyecto crea una carpeta .vscode
dentro de la carpeta .vscode crea un archivo extensions.json

Para la bikoSchool nos indicaron una serie de extensiones: 

#extensions.json
{
    // See https://go.microsoft.com/fwlink/?LinkId=827846 to learn about workspace recommendations.
    // Extension identifier format: ${publisher}.${name}. Example: vscode.csharp
    // List of extensions which should be recommended for users of this workspace.
    "recommendations": [
      "MS-CEINTL.vscode-language-pack-es",
      "EditorConfig.EditorConfig",
      "usernamehw.errorlens",
      "dbaeumer.vscode-eslint",
      "MS-vsliveshare.vsliveshare",
      "esbenp.prettier-vscode",
      "Gruntfuggly.todo-tree",
      "mike-co.import-sorter",
      "pflannery.vscode-versionlens",
      "vscode-icons-team.vscode-icons",
      "styled-components.vscode-styled-components",
      "eamodio.gitlens",
      "WallabyJs.quokka-vscode",
      "mhutchie.git-graph"
    ],
    // List of extensions recommended by VS Code that should not be recommended for users of this workspace.
    "unwantedRecommendations": []
  }
