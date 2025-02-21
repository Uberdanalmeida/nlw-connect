# NLW Connect - CodeCraft Summit 2025 

!(imagem/nlw-connect.png)

Este projeto consiste em uma página web para o evento CodeCraft Summit 2025, desenvolvido durante a NLW Connect. A página oferece informações sobre o evento e um formulário de inscrição.

## Visão Geral

A página é construída com HTML, CSS e JavaScript. O design é responsivo e adaptado para diferentes tamanhos de tela.

## Funcionalidades

*   **Informações sobre o evento:** Detalhes sobre o evento, datas, horários e formato (online e gratuito).
*   **Formulário de inscrição:** Permite aos usuários inserir seus dados (email e telefone) para se inscrever no evento.
*   **Página de convite:** Após a inscrição, o usuário é redirecionado para uma página com um link de convite personalizado e estatísticas sobre suas inscrições.
*   **Design responsivo:** A página se adapta a diferentes tamanhos de tela, proporcionando uma boa experiência em dispositivos móveis e desktops.

## Tecnologias Utilizadas

*   **HTML:** Estrutura da página web.
*   **CSS:** Estilos e layout da página.
*   **JavaScript:** Interatividade e funcionalidades dinâmicas.

## Estrutura do Projeto

*   `index.html`: Arquivo principal HTML.
*   `style.css`: Arquivo de estilos CSS.
*   `script.js`: Arquivo JavaScript com a lógica da aplicação.

## Como Executar

1.  Clone o repositório: `git clone <link-do-repositorio>`
2.  Abra o arquivo `index.html` em seu navegador.

## Funcionalidades Detalhadas

### Inscrição

O formulário de inscrição coleta o email e o telefone do usuário. Ao clicar em "Confirmar", o JavaScript verifica se o usuário já está cadastrado. Se não estiver, um novo usuário é criado com um código de referência único. Em ambos os casos, o usuário é redirecionado para a página de convite.

### Página de Convite

Esta página exibe uma mensagem de confirmação, um link de convite personalizado (que inclui o código de referência do usuário) e estatísticas sobre o número de inscrições feitas através do link do usuário.

### Estatísticas

A página de convite mostra o número de inscrições feitas através do link de convite do usuário. Esta funcionalidade é implementada com JavaScript que filtra os usuários com base no código de referência.

## Imagens

As imagens utilizadas no projeto são referenciadas através de links do GitHub, facilitando o uso e a distribuição do projeto.  O script JavaScript atualiza dinamicamente os links das imagens para garantir que sejam carregadas corretamente.

## Próximos Passos

*   Implementar a persistência dos dados (usando localStorage, um banco de dados, etc.).
*   Melhorar a validação do formulário.
*   Adicionar mais informações sobre o evento.
*   Implementar outras funcionalidades interativas.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.