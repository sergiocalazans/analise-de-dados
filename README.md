# Dashboard Redes Sociais

Este é um projeto de **Análise de Dados e Visualização Web** que apresenta relatórios interativos sobre o uso de redes sociais no mundo e em uma comunidade escolar específica. A aplicação utiliza JavaScript assíncrono para consumir APIs e a biblioteca **Plotly.js** para renderizar gráficos dinâmicos e responsivos.

## 📊 Funcionalidades

* **Relatório Global:** Exibe dados demográficos sobre a população mundial conectada, tempo médio de uso e porcentagem de penetração das redes sociais.
* **Gráficos Comparativos:** * Gráfico de barras mostrando as redes com maior número de usuários ativos.
    * Gráfico de pizza (pie chart) detalhando as redes favoritas dos usuários globalmente.
* **Análise Local (Minha Escola):** Uma seção dedicada que processa dados específicos de uma comunidade, permitindo comparar tendências locais com as globais.
* **Persistência de Dados:** Uso de `localStorage` para armazenar respostas de API localmente, otimizando o carregamento e reduzindo requisições desnecessárias.

## 🛠️ Tecnologias Utilizadas

* **HTML5 & CSS3:** Estrutura semântica e estilização moderna com variáveis CSS (`:root`) e fontes do Google Fonts.
* **JavaScript (ES6+ Modules):** Organização do código em módulos reutilizáveis para funções de gráfico e tratamento de texto.
* **Plotly.js:** Biblioteca avançada para criação de gráficos interativos e responsivos.
* **Fetch API:** Consumo de dados JSON de APIs externas de forma assíncrona.

## 📂 Estrutura do Projeto

* `index.html` / `minha-escola.html`: Páginas principais do dashboard.
* `common.js`: Funções utilitárias para capturar estilos CSS e instanciar gráficos Plotly de forma padronizada.
* `informacoesGlobais.js`: Lógica para extração e exibição dos fatos rápidos sobre a internet no mundo.
* `style.css`: Identidade visual do projeto, utilizando uma paleta de cores focada em contraste e legibilidade.

## 🚀 Como Executar

1.  Clone o repositório.
2.  Como o projeto utiliza **Módulos JavaScript (`import/export`)**, é necessário rodar a aplicação através de um servidor local (como a extensão *Live Server* do VS Code) para evitar erros de política CORS.
3.  Abra o `index.html` no navegador.

---
*Este projeto foi desenvolvido por **Sérgio Calazans** como parte de um estudo sobre ciência de dados aplicada ao desenvolvimento web.*
