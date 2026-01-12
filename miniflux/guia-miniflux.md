# Guia do Miniflux

O Miniflux é um agregador de RSS leve, minimalista e fácil de usar. Ele fornece uma API que permite a conexão com outros aplicativos de RSS. Este guia ajudará você a começar a usar o Miniflux.

## Como adicionar um novo feed

Na página inicial, clique no botão `+` ao lado de `Fontes` no menu superior.

No campo de URL, insira a URL do feed que deseja assinar. Para assinar o **Manual do Usuário**, por exemplo, copie e cole o endereço: `https://manualdousuario.net/feed/`.

![Tela de cadastro de novo feed no Miniflux.](/images/miniflux-novo-feed.png)

Caso você não saiba o endereço exato do feed, experimente inserir o endereço do site. O Miniflux detecta automaticamente feeds no código-fonte do site.

![Tela com itens do feed do Manual do Usuário no Miniflux.](/images/miniflux-feed-lista.png)

Ao clicar em um item, você poderá ler a notícia diretamente no Miniflux.

![Item/post do Manual do Usuário aberto no Miniflux.](/images/miniflux-feed-item.png)

## Como importar feeds de outras plataformas

Primeiro, exporte o seu feed da plataforma atual para um arquivo no formato `*.opml`. Veja como fazer [no Feedly](https://feedly.helpscoutdocs.com/article/52-how-can-i-export-my-sources-and-feeds-through-opml) (em inglês). Você também pode importar usando um link direto para o arquivo de feed.

Na página inicial, clique no `+` ao lado de `Fontes` no menu superior. Na tela seguinte, clique no menu `Importar`.

![Tela de importação de feeds via arquivo OPML no Miniflux.](/images/miniflux-importar.png)
