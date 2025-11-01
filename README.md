# ☀️ Previsão do Tempo

Este é um projeto simples de aplicação web para **visualizar a previsão do tempo** de qualquer cidade do mundo, utilizando a API **OpenWeatherMap**.

## 🚀 Tecnologias Utilizadas

O projeto foi construído com as seguintes tecnologias:

* **HTML5:** Estrutura da página.
* **CSS3:** Estilização e layout responsivo.
* **JavaScript (ES6+):** Lógica para buscar e exibir os dados da API.

## ✨ Funcionalidades

* **Busca por Cidade:** O usuário pode digitar o nome de uma cidade em um campo de input.
* **Exibição de Dados:** Exibe o nome da cidade, temperatura atual (em Celsius), descrição do tempo (ex: "Nublado", "Chuva leve"), umidade e um ícone representativo.
* **Integração com API:** Utiliza a API OpenWeatherMap para buscar dados de previsão em tempo real.

## 🛠️ Como Rodar o Projeto

Para rodar este projeto localmente, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [LINK_DO_SEU_REPOSITORIO]
    cd previsao-do-tempo
    ```
2.  **Obtenha uma Chave da API:**
    * Crie uma conta no [OpenWeatherMap](https://openweathermap.org/).
    * Obtenha sua chave de API (AppID).

3.  **Configure a Chave no `script.js`:**
    * Abra o arquivo `script.js`.
    * Substitua o valor da constante `key` pela sua chave de API.

    ```javascript
    const key = "SUA_CHAVE_AQUI" // Substitua este valor
    // ...
    ```

4.  **Abra o `index.html`:**
    * Simplesmente abra o arquivo `index.html` em seu navegador.

    > **Dica:** Para um desenvolvimento mais robusto, é recomendável usar uma extensão como o "Live Server" do VS Code, ou abrir o projeto via um servidor local.

## ⚙️ Estrutura de Arquivos

* `index.html`: Contém a estrutura da interface do usuário.
* `script.js`: Contém a lógica de busca de dados na API e a manipulação do DOM.
* `style.css`: Contém os estilos para a aplicação, incluindo o plano de fundo.

## 🤝 Contribuições

Sinta-se à vontade para sugerir melhorias, reportar bugs ou fazer um *fork* do projeto!

1.  Faça o *fork* do projeto.
2.  Crie uma *branch* para sua funcionalidade (`git checkout -b feature/nova-funcionalidade`).
3.  Faça o *commit* das suas alterações (`git commit -m 'Adiciona nova funcionalidade X'`).
4.  Faça o *push* para a *branch* (`git push origin feature/nova-funcionalidade`).
5.  Abra um *Pull Request*.

## 🔑 Licença

Este projeto está sob a licença **MIT**.
