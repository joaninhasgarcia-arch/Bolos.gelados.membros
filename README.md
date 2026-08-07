# Bolos Gelados Gourmet — Área de Membros Premium

Área de membros responsiva, em arquivo único, criada para organizar as videoaulas do curso **Bolos Gelados Gourmet** com uma experiência inspirada em plataformas de streaming.

## Arquivos

- `index.html` — área de membros completa.
- `README.md` — orientações de publicação e personalização.

## O que está incluído

- Visual premium escuro com detalhes em rosa e dourado.
- Layout responsivo para celular, tablet e computador.
- Catálogo com **20 videoaulas diferentes**, distribuídas em quatro módulos.
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

O vídeo de ID `AtmJu3bV6q0` não apresentou um título identificável durante a organização. Ele foi exibido como:

**Aula Extra — Receita Especial**

Para alterar esse nome, procure pelo ID dentro do `index.html` e substitua apenas o campo `title`.

## Personalização rápida

No final do `index.html`, existe a constante JavaScript `modules`. Nela é possível alterar:

- título da aula;
- sabor;
- categoria;
- ID do vídeo do YouTube;
- ordem das aulas e módulos.

As cores principais ficam no começo do CSS, dentro do bloco `:root`.
