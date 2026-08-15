# Bolos Gelados Gourmet — Área de Membros Premium

Área de membros responsiva, em arquivo único, criada para organizar as videoaulas do curso **Bolos Gelados Gourmet** com uma experiência inspirada em plataformas de streaming.

## Arquivos

- `index.html` — área de membros completa.
- `README.md` — orientações de publicação e personalização.

## Atualização desta versão

Foram mantidos o visual, a estrutura e as aulas já existentes e acrescentado o **Módulo 5 — Vendas, Embalagens e Negócio** com 7 novas aulas:

1. Embalagem para Bolo Gelado
2. Como Fazer Etiquetas e Adesivos pelo Celular com o Canva
3. Aula de Precificação
4. Como Vender pelo Instagram
5. Análise de Perfis do Instagram
6. Como Vender pelo WhatsApp
7. Aula Extra — Como Começar a Vender e Receber Encomendas pelo iFood

A área agora contém **27 videoaulas distribuídas em 5 módulos**.

## Ofertas complementares dentro das aulas

Foram adicionadas **apresentações visuais de oferta** dentro do player, com copy, benefícios e botão de compra, sem alterar o estilo principal da plataforma:

- Nas aulas relacionadas a **embalagem/etiquetas**, aparece um card promocional do **Pack de 30 Etiquetas Editáveis**:
  `https://pay.cakto.com.br/3atx3oo_1041160`

- Na **Aula de Precificação**, aparece um card promocional da **Calculadora Automática de Precificação e Lucro**:
  `https://pay.cakto.com.br/ajhxeao_1039693`

Esses cards aparecem apenas nas aulas que possuem uma oferta relacionada e foram pensados para melhorar a conversão pós-venda dentro da área de membros.

## O que está incluído

- Visual premium escuro com detalhes em rosa e dourado.
- Layout responsivo para celular, tablet e computador.
- Catálogo com **27 videoaulas diferentes**, distribuídas em cinco módulos.
- Capas automáticas usando as miniaturas oficiais dos vídeos do YouTube.
- Player em janela modal, sem retirar o aluno da área de membros.
- Busca por nome, sabor ou categoria.
- Filtros por módulo.
- Seção “Continue assistindo”.
- Marcação de aulas concluídas.
- Progresso salvo localmente no navegador do aluno com `localStorage`.
- Navegação lateral no computador e menu inferior no celular.

## Módulos

1. Bolos Embrulhados
2. Marmitas Lucrativas
3. Fatias Gourmet
4. Cremosos e Especiais
5. Vendas, Embalagens e Negócio

## Publicação no GitHub Pages

1. Extraia o ZIP.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. No GitHub, abra **Settings > Pages**.
4. Escolha a branch principal e a pasta raiz.
5. Salve e aguarde a publicação.

## Importante sobre acesso e segurança

Este projeto é uma interface estática. Ao publicar o arquivo diretamente no GitHub Pages, qualquer pessoa que possuir o endereço poderá acessar o conteúdo. O HTML não oferece proteção real por senha.

Para restringir o acesso, publique a página dentro de uma plataforma com autenticação, use um serviço de membros ou proteja o site por uma camada de login no servidor.

## Miniaturas e vídeos

As capas são carregadas a partir das miniaturas públicas do YouTube. Os vídeos são exibidos usando o player incorporado `youtube-nocookie.com` e precisam continuar disponíveis nos links originais.

## Aula com título genérico

O vídeo de ID `AtmJu3bV6q0` permanece exibido como:

**Aula Extra — Receita Especial**

Para alterar esse nome, procure pelo ID dentro do `index.html` e substitua apenas o campo `title`.

## Personalização rápida

No final do `index.html`, existe a constante JavaScript `modules`. Nela é possível alterar:

- título da aula;
- sabor/tema;
- categoria;
- ID do vídeo do YouTube;
- ordem das aulas e módulos;
- botão de oferta opcional por aula (`offer`).

As cores principais ficam no começo do CSS, dentro do bloco `:root`.
