
# Medicina para Todos

Bem-vindo ao repositório do projeto **Medicina para Todos**. Este projeto é um site de serviços médicos, desenvolvido com HTML, CSS e JavaScript puro, sem o uso de frameworks de front-end ou renderização do servidor. O site tem como objetivo fornecer informações médicas acessíveis para todos.

## Índice

- [Visão Geral](#visão-geral)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Instalação](#instalação)
- [Uso](#uso)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Visão Geral

O site **Medicina para Todos** inclui as seguintes páginas:
- **Início**: Página principal com uma visão geral do site.
- **Sobre**: Informações sobre o objetivo do site e a equipe por trás dele.
- **Contato**: Formulário de contato para os visitantes entrarem em contato com a equipe.
- **Login**: Página de login para acesso a conteúdos exclusivos.

## Estrutura do Projeto

A estrutura de diretórios do projeto é organizada da seguinte forma:

```
/medicina-para-todos
|-- /css
|   |-- styles-principal.css
|   |-- /componentes
|       |-- header.css
|       |-- footer.css
|       |-- contato.css
|       |-- sobre.css
|       |-- login.css
|-- /js
|   |-- index.js
|   |-- /componentes
|       |-- sobre.js
|       |-- contato.js
|       |-- login.js
|-- /imagens
|-- /fonts
|-- /src
    |-- sobre.html
    |-- contato.html
    |-- login.html
|-- index.html
```

- **/css**: Contém os arquivos de estilo.
  - **/componentes**: Contém estilos específicos para componentes como o header e o footer.
- **/js**: Contém os arquivos de script.
  - **/componentes**: Contém scripts específicos para componentes ou funcionalidades.
- **/imagens**: Contém as imagens usadas no site.
- **/fonts**: Contém as fontes personalizadas usadas no site.
- **/src**: Contém as páginas:
  - **sobre.html**: Página "Sobre".
  - **contato.html**: Página de contato.
  - **login.html**: Página de login.
- **index.html**: Página inicial do site.

## Instalação

Para clonar e configurar este repositório localmente, siga os passos abaixo:

1. **Clone o repositório:**

   ```sh
   git clone https://github.com/HenriqueSerres/medicina-para-todos
   ```

2. **Navegue até o diretório do projeto:**

   ```sh
   cd medicina-para-todos
   ```

## Uso

Para visualizar o site localmente, basta abrir os arquivos HTML em seu navegador. Por exemplo, para visualizar a página inicial, abra `index.html` em seu navegador preferido.
Ou usando `Live Server`- extensão do VSCode.

```sh
open index.html
```

## Contribuição

Contribuições são bem-vindas! Para contribuir, siga os passos abaixo:

1. **Fork o repositório.**
2. **Crie uma nova branch:**

   ```sh
   git checkout -b minha-branch
   ```

3. **Faça suas alterações e commite:**

   ```sh
   git commit -m "Minha contribuição"
   ```

4. **Envie para o repositório remoto:**

   ```sh
   git push origin minha-branch
   ```

5. **Abra um Pull Request.**

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter mais informações.
