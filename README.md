# Portfólio — Derick Borges Prado

Sou estudante do primeiro semestre de Desenvolvimento de Sistemas na ETEC e atuo na área de segurança do trabalho. Este portfólio reúne minha apresentação, meus conhecimentos e os projetos que venho desenvolvendo.

Meu objetivo é aplicar o que aprendo no curso para criar soluções que ajudem na prevenção de riscos, na organização de informações e nas rotinas de segurança do trabalho.

## Acesso

Endereços definidos para a publicação no repositório `portfolio`:

- [Repositório no GitHub](https://github.com/derickdk137-byte/portfolio)
- [Site no GitHub Pages](https://derickdk137-byte.github.io/portfolio/)

A publicação ainda precisa ser concluída. Se o repositório receber outro nome, estes links deverão ser atualizados.

## Tecnologias utilizadas

- HTML5
- CSS3
- Bootstrap 5.3.9
- JavaScript
- GitHub Pages para publicação

## Sobre o site

A página está dividida em Perfil, Habilidades, Projetos e Contato. O menu permite acessar cada seção e se adapta às telas de celulares.

Na seção de habilidades, apresento meus conhecimentos em Python, Linux, SSH e automações. Em Projetos, estão os links dos meus repositórios. Os contatos levam ao meu GitHub e ao LinkedIn.

Escolhi preto e dourado como as cores dominantes. No modo escuro, o preto predomina. No modo claro, os tons de dourado e creme ficam mais presentes.

## Recurso novo: troca de tema

Além da estrutura trabalhada nas apostilas, acrescentei um botão para alternar entre os modos claro e escuro. A escolha fica salva no navegador e é recuperada ao abrir a página novamente.

A troca foi feita com JavaScript, alterando o atributo `data-bs-theme` do HTML. As cores de cada modo são definidas por variáveis no CSS, e a preferência é guardada no `localStorage`. Se o navegador bloquear esse armazenamento, ainda é possível trocar o tema durante a visita.

Também incluí uma seção de habilidades e efeitos de transição nos botões e cards.

## Como abrir

Basta abrir `index.html` no navegador. O Bootstrap, o CSS e o JavaScript estão incorporados ao arquivo, por isso não é necessário instalar nada. A conexão com a internet é necessária para acessar os links externos.

## Como atualizar os projetos

No final de `index.html`, procure a lista `const projetos = [`. Cada item contém o título, a descrição, as tecnologias e os links de um projeto.

Para adicionar outro trabalho, copie um dos itens existentes, altere os dados e separe os itens com vírgula. O campo `site` pode ficar vazio quando o projeto não tiver uma página publicada. Os cards são criados automaticamente a partir dessa lista.

## Publicação

O passo a passo está em [PUBLICAR.md](PUBLICAR.md).

## Material de apoio

- Agendas 13, 14 e 15 de Desenvolvimento de Sistemas I — ETEC.
- [Documentação do Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/).
- [Documentação do GitHub Pages](https://docs.github.com/en/pages).
