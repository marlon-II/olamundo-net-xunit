# 🌍 Olá Mundo - .NET 10 com xUnit

![.NET](https://img.shields.io/badge/.NET-10.0-512BD4?style=flat-square&logo=dotnet)
![xUnit](https://img.shields.io/badge/xUnit-Testing-lightgrey?style=flat-square)
![VS Code](https://img.shields.io/badge/VS_Code-Ready-007ACC?style=flat-square&logo=visual-studio-code)

Este repositório contém uma solução de introdução ("Olá Mundo"), desenvolvida para demonstrar a estrutura fundamental de uma aplicação em .NET integrada a um ambiente de testes automatizados. 


---

## 🚀 Tecnologias Utilizadas

A solução foi construída utilizando as seguintes ferramentas:

* **[.NET 10](https://dotnet.microsoft.com/)**: Plataforma de desenvolvimento rápida, multiplataforma e de código aberto.
* **[xUnit](https://xunit.net/)**: Framework de testes robusto e gratuito para o ecossistema .NET.
* **[Visual Studio Code](https://code.visualstudio.com/)**: Editor de código-fonte leve e poderoso.

---

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:

1. [SDK do .NET 10](https://dotnet.microsoft.com/download)
2. [Visual Studio Code](https://code.visualstudio.com/)
3. Extensão do C# para VS Code (fornecida pela Microsoft)

---

## 💻 Como executar a aplicação no VS Code

Siga os passos abaixo para baixar e rodar a aplicação utilizando o seu Visual Studio Code:

1. **Clone o repositório:**
   Abra o terminal e execute:
   ```bash
   git clone https://github.com/marlon-II/olamundo-net-xunit.git
   ```

2. **Abra o projeto no VS Code:**
   Navegue até a pasta do projeto e abra-a no editor:
   ```bash
   cd olamundo-net-xunit
   code .
   ```

3. **Abra o Terminal Integrado:**
   No VS Code, pressione `` Ctrl + ` `` (ou vá em `Terminal` > `New Terminal`).

4. **Execute o projeto principal:**
   No terminal integrado, certifique-se de estar na pasta do projeto da aplicação (caso exista uma) e digite:
   ```bash
   dotnet run
   ```

---

## 🧪 Como rodar os testes

Os testes automatizados ajudam a validar se a aplicação está funcionando conforme o esperado. Você pode executá-los diretamente pelo VS Code:

**Opção 1: Via Terminal Integrado**
No terminal do VS Code, na pasta raiz da solução, execute:
```bash
dotnet test
```

**Opção 2: Via Interface do VS Code (Test Explorer)**
Se você estiver utilizando a extensão do C# e o C# Dev Kit, um ícone de "Flasco de laboratório" (Testing) aparecerá no menu lateral esquerdo do VS Code. Clicando nele, você poderá ver todos os testes mapeados e rodá-los visualmente clicando no botão "Play" (▶️).

---
*Desenvolvido como demonstração de estrutura de projetos .NET com testes.*

---

*Desenvolvido por: Marlon Andrade Bartoli, RA 4251920432.*
