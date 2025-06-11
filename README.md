# O Cubo Mágico - Um Cubo de Rubik 3D Interativo

Este é um projeto de um Cubo mágico totalmente interativo, desenvolvido com JavaScript e a biblioteca Three.js. Permite que os utilizadores embaralhem e resolvam o cubo, enquanto acompanham as suas estatísticas de tempo.

## Funcionalidades

* **Cubo 3D Interativo:** Gire as faces do cubo com o mouse.
* **Vários Tamanhos de Cubo:** Suporta cubos de 2x2x2 até 5x5x5.
* **Cronómetro e Estatísticas:** Mede o tempo de resolução e guarda estatísticas como melhor tempo, pior tempo e médias (de 5, 12 e 25).
* **Embaralhamento Personalizável:** Escolha o número de movimentos (20, 25 ou 30) para embaralhar o cubo.
* **Temas e Personalização Visual:**
    * Vários temas de cores pré-definidos (Cube, Erno, Dust, etc.).
    * Um editor de tema para ajustar a Matiz, Saturação e Luminosidade da interface.
    * Ângulo da câmara ajustável (Ortográfica ou Perspetiva).

## Tecnologias Utilizadas

* **HTML5**
* **CSS3 / Sass** para estilos modulares.
* **JavaScript (ES6+)** para toda a lógica do jogo e interatividade.
* **Three.js** para a renderização e manipulação da cena 3D.

## Como Executar Localmente

Como este é um projeto puramente de front-end, não é necessário um processo de compilação complexo para o executar.

1.  **Clona o repositório:**
    ```sh
    git clone https://github.com/RD1707/o-cubo
    ```

2.  **Navega até à pasta do projeto:**
    ```sh
    cd o-cubo
    ```

3.  **Abre o ficheiro `index.html`:**
    Abre o ficheiro `index.html` diretamente no teu navegador de preferência (como Chrome, Firefox, etc.).

    > **Nota:** Para uma melhor experiência e para garantir que todos os módulos JavaScript carreguem corretamente, é recomendado servir os ficheiros a partir de um servidor web local. Se usa o Visual Studio Code, podes usar a extensão **Live Server** para fazer isso com um clique.