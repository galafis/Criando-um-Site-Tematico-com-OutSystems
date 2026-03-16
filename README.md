# 🌟 Site Temático com OutSystems – Projeto Final

## 🇧🇷 Português

Este projeto, desenvolvido por Gabriel Demetrios Lafis, representa o encerramento da jornada de aprendizado com OutSystems. O objetivo foi criar um site temático cativante, interativo e cheio de personalidade, unindo **design criativo**, **tecnologia robusta** e **integração com APIs reais**. A entrega inclui versões web e mobile, demonstrando a versatilidade da plataforma OutSystems.

### 🚀 Visão Geral do Projeto

O projeto foca na criação de um site temático utilizando a plataforma OutSystems, com o tema **Pokémon**. A escolha do tema permite uma vasta gama de interações e o uso da [PokeAPI](https://pokeapi.co/) para dados em tempo real, proporcionando uma experiência dinâmica para os fãs da franquia.

### 🧩 Funcionalidades Principais

- 🌐 **Aplicação Web Reactive**: Layout responsivo, adaptado a diferentes tamanhos de tela.
- 📱 **Aplicativo Mobile**: Navegação fluida e compatibilidade com instalação via QR Code (PWA).
- 🧠 **Consumo de API externa**: Sincronização via **Timer** para atualização contínua dos dados no banco local.
- 🛠 **Arquitetura Canvas**: Divisão em camadas com separação de responsabilidades (Core, Services, UI).
- 🎨 **Tema personalizado**: Identidade visual exclusiva do universo Pokémon.
- 🎥 **Integração multimídia**: Vídeos, imagens animadas, efeitos visuais e transições suaves.
- 🔐 **Autenticação de Usuário**: Tela de login e autenticação.
- 🧾 **Tela de Detalhes**: Informações dos personagens e funcionalidades extras.
- 📦 **Banco de Dados Sincronizado**: Dados atualizados via agendamentos inteligentes (timers).

### 📁 Estrutura do Repositório

```
assets/
├── hero-image.png
docs/
├── README.md
├── architecture.mmd
src/
├── SiteTematico_Pokemon.oml
.gitignore
LICENSE
README.md
```

- `src/`: Contém os arquivos fonte do projeto OutSystems (.oml).
- `docs/`: Contém a documentação detalhada do projeto, incluindo o README original e diagramas.
- `assets/`: Recursos visuais como a imagem hero.
- `LICENSE`: O arquivo de licença do projeto.
- `README.md`: Este arquivo, com a documentação bilíngue e visão geral do projeto.

### 🔗 APIs Utilizadas

- [PokeAPI](https://pokeapi.co/) – Utilizada para consumir dados dos Pokémons.

### ⚠️ Limitações e Considerações sobre o Código OutSystems

É importante notar que o arquivo `SiteTematico_Pokemon.oml` é um artefato binário gerado pela plataforma OutSystems. Devido à natureza proprietária e de baixo código da plataforma, as seguintes limitações se aplicam:

- **Aprimoramento Direto do Código**: Não é possível realizar edições diretas ou aprimoramentos no código-fonte dentro do arquivo `.oml` utilizando ferramentas de desenvolvimento convencionais (como editores de texto ou IDEs padrão). Quaisquer modificações devem ser feitas através do ambiente de desenvolvimento OutSystems.
- **Testes Unitários e Validação**: A implementação de testes unitários e validação completa do código-fonte, conforme as práticas de desenvolvimento tradicionais, não é aplicável diretamente ao arquivo `.oml`. A funcionalidade e a qualidade do código são validadas dentro do ambiente OutSystems, que oferece suas próprias ferramentas de depuração e teste.

Este repositório foca na demonstração da estrutura do projeto, documentação e integração com APIs, conforme desenvolvido originalmente por Gabriel Demetrios Lafis na plataforma OutSystems. A funcionalidade do aplicativo é garantida pela execução no ambiente OutSystems.

### 📊 Diagrama de Arquitetura

```mermaid
graph TD
    A[Usuário] -->|Acessa| B(Aplicação Web/Mobile OutSystems)
    B -->|Consome| C[API Externa: PokeAPI]
    C -->|Dados de Pokémon| B
    B -->|Persiste Dados| D[Banco de Dados Local]
    D -->|Sincronizado via Timer| C
```

### 🏅 Badges

<!-- BADGES_PLACEHOLDER -->

### 🖼️ Imagem Hero

![Imagem Hero do Projeto](assets/hero-image.png)



[![GitHub last commit](https://img.shields.io/github/last-commit/galafis/Criando-um-Site-Tematico-com-OutSystems)](https://github.com/galafis/Criando-um-Site-Tematico-com-OutSystems/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/galafis/Criando-um-Site-Tematico-com-OutSystems)](https://github.com/galafis/Criando-um-Site-Tematico-com-OutSystems)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![License-MIT](https://img.shields.io/badge/License--MIT-yellow?style=for-the-badge)





## 🌐 GitHub Pages (Configuração Manual)

Para visualizar uma demonstração interativa deste projeto via GitHub Pages, siga os passos abaixo para configurar manualmente:

1.  **Acesse as Configurações do Repositório**: No seu repositório GitHub, clique na aba `Settings` (Configurações).
2.  **Navegue até GitHub Pages**: No menu lateral esquerdo, clique em `Pages`.
3.  **Selecione a Branch e Pasta**: Em `Build and deployment`, selecione `Deploy from a branch`.
    *   Para `Branch`, escolha `main` (ou a branch principal do seu repositório).
    *   Para `Folder`, selecione `/pages`.
4.  **Salvar**: Clique em `Save` (Salvar).

Após a configuração, o GitHub Pages será ativado e o site de demonstração estará disponível em um URL similar a `https://galafis.github.io/Criando-um-Site-Tematico-com-OutSystems/`.

O arquivo `pages/index.html` foi preparado para servir como uma página de demonstração simples, direcionando os visitantes de volta ao repositório principal.


---

## English

### Overview

🌟 Site Temático com OutSystems – Projeto Final - A project built with HTML, React, OutSystems, developed by Gabriel Demetrios Lafis as part of professional portfolio and continuous learning in Data Science and Software Engineering.

### Key Features

This project demonstrates practical application of modern development concepts including clean code architecture, responsive design patterns, and industry-standard best practices. The implementation showcases real-world problem solving with production-ready code quality.

### How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/galafis/Criando-um-Site-Tematico-com-OutSystems.git
   ```
2. Follow the setup instructions in the Portuguese section above.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Developed by [Gabriel Demetrios Lafis](https://github.com/galafis)
