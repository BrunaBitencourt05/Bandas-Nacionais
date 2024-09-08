# Bandas Nacionais- Imersão Dev com Google Gemini

**Bandas Nacionais** é um site que permite explorar e pesquisar informações sobre três bandas brasileiras famosas: Raimundos, Charlie Brown Jr. e Legião Urbana. O projeto foi desenvolvido como parte do curso Imersão Dev com Google Gemini da Alura.

## Visão Geral

O site oferece uma interface simples e intuitiva onde os usuários podem pesquisar e acessar informações detalhadas sobre essas bandas icônicas da música brasileira. O design é limpo e moderno, focando na usabilidade e estética.

## Funcionalidades

- **Campo de Pesquisa**: Permite buscar informações sobre as bandas. O usuário pode digitar o nome da banda ou uma tag relevante para realizar a pesquisa.
- **Resultados de Pesquisa**: Exibe descrições e links relacionados às bandas pesquisadas.

## Funcionalidade de Pesquisa

A função `pesquisar()` realiza a busca das bandas com base no texto inserido pelo usuário. O código JavaScript faz o seguinte:
1. **Captura o Valor da Pesquisa**: Obtém o valor do campo de pesquisa e o converte para minúsculas.
2. **Verifica Se Algo Foi Digitado**: Exibe uma mensagem se o campo de pesquisa estiver vazio.
3. **Busca nos Dados**: Percorre os dados das bandas e verifica se o título, descrição ou tags contêm o texto pesquisado.
4. **Exibe Resultados**: Atualiza a interface com os resultados encontrados ou uma mensagem caso nenhum resultado seja encontrado.

## Bandas Disponíveis

1. **Legião Urbana**
   - **Descrição**: Legião Urbana foi uma banda brasileira de rock formada em 1982, em Brasília, por Renato Russo e Marcelo Bonfá, com Dado Villa-Lobos e Renato Rocha na formação mais conhecida. O grupo encerrou suas atividades em 1996, após o falecimento de Renato Russo.
   - **Link**: [Legião Urbana na Wikipedia](https://pt.wikipedia.org/wiki/Legião_Urbana)
   - **Tags**: rock brasileiro, 80s, legenda

2. **Raimundos**
   - **Descrição**: Os Raimundos são uma banda brasileira de rock formada em Brasília em 1987. Eles são conhecidos pela mistura de punk rock, hardcore e música brasileira, se tornando um dos maiores nomes do rock nacional.
   - **Link**: [Raimundos na Wikipedia](https://pt.wikipedia.org/wiki/Raimundos)
   - **Tags**: rock brasileiro, punk, hardcore

3. **Charlie Brown Jr.**
   - **Descrição**: Charlie Brown Jr. foi uma banda brasileira de rock formada em Santos em 1992. A banda se destacou por suas letras sobre temas do cotidiano e por sua energia contagiante nos shows.
   - **Link**: [Charlie Brown Jr. na Wikipedia](https://pt.wikipedia.org/wiki/Charlie_Brown_Jr.)
   - **Tags**: rock brasileiro, alternativo

## Tecnologias Utilizadas

- **HTML/CSS**: Estrutura e estilo da página.
- **JavaScript**: Funcionalidade para pesquisa e exibição de resultados.
- **Vercel**: Hospedagem e deployment do site.

## Estrutura do Projeto

- `index.html`: Página principal do site com estrutura HTML e links para estilos e scripts.
- `styles.css`: Arquivo de estilos para o layout e design do site.
- `dados.js`: Contém dados das bandas e lógica de manipulação dos dados.
- `app.js`: Implementa a funcionalidade de pesquisa e manipulação da interface.

## Design e Estilo

- **Fonte**: Utiliza a fonte [Chakra Petch](https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap) para um visual moderno e legível.
- **Cor de Fundo**: A cor de fundo do site é um verde claro (`rgb(153, 242, 120)`), proporcionando um visual fresco e vibrante.
- **Estilo dos Componentes**: O site utiliza bordas arredondadas, sombras sutis e efeitos de hover para uma experiência de usuário agradável e moderna.
- **Layout**: O layout é centrado vertical e horizontalmente na página, com o conteúdo principal focado no centro e o footer fixo na parte inferior.

## Como Usar

1. Acesse o site [aqui](https://bandas-nacionais.vercel.app/).
2. Utilize o campo de pesquisa para digitar o nome da banda desejada ou uma tag relacionada.
3. Clique em "Pesquisar" para visualizar as informações.

## Agradecimentos

Um agradecimento especial aos professores **Rafaella Ballerini**, **Guilherme Lima** e **Luciano Martins** pelo suporte e orientação durante o curso.

## Contato

Para mais informações ou sugestões, entre em contato com: [BrunaBitencourt@gmail.com](mailto:BrunaBitencourt@gmail.com).

## Licença

Este projeto é disponibilizado sob a licença [MIT](LICENSE).

---

Explore o site e descubra mais sobre essas bandas que marcaram a música brasileira!
