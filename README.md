# Cardápio Dona Sil

Cardápio online de bolos, tortas e doces da Dona Sil, publicado em **https://donasil.github.io**.

- Os sabores ficam na lista `MENU`, no começo do `<script>` do `index.html`.
  - `tag: 'new'` marca uma novidade (hoje: crepe de chocolate e Leite Ninho com uva verde).
  - `top: true` põe o selo "Mais vendido" no bolo (hoje: os dois Dona Sil, Carinhoso de Nutella e Mousse de chocolate meio amargo). Vale junto com a `tag` e não muda a ordem.
  - `sabores: [...]` faz o item abrir e fechar, com cada sabor escolhido separado (ex.: brigadeiros e pão de mel).
  - `g: '...'` agrupa os itens dentro da aba (Tortas doces / Tortas salgadas, Docinhos gourmet / Outros doces). O aviso de um grupo fica em `GRUPO_NOTA` (hoje: pedido mínimo de 50 unidades nos docinhos gourmet) e aparece também no pedido.
  - `rotulo: '...'` é o nome usado no pedido e no WhatsApp quando o nome sozinho fica ambíguo (ex.: "Torta salgada de atum").
- Imagens: os bolos usam fotos de bolos da Dona Sil do Instagram (pasta `img/bolos`, lista `FOTO`), escolhidas pelo jeito do sabor; tortas e doces usam desenhos (`TORTA` e `DOCE`; tortas salgadas com `tampa: true`) até termos fotos. Tortas com foto da Dona Sil ficam na pasta `img/tortas`, lista `FOTO_TORTA` (hoje: palmito, com 2 fotos), e também ampliam ao toque. Um sabor pode ter várias fotos (uma lista de nomes): a primeira vai no cartão, com o aviso "2 fotos", e na foto ampliada dá para passar de uma para outra pelas setas, deslizando para o lado ou com as setas do teclado. Bolos sem foto aparecem só com o nome.
- A pessoa escolhe os sabores só no **+** (o resto do cartão não escolhe nada); tocar na foto de um bolo amplia a foto, e dá para escolher o sabor por ali também. Peso, quantidade e preço são combinados direto com a Dona Sil.
- **Seu pedido** (carrinho): o botão **Ver meu pedido**, na barra de baixo, fica sempre à mostra com o número de escolhidos; tocar nele abre a lista para tirar itens, trocar os sabores dos brigadeiros e escrever observações (de cada item e do pedido), que vão junto na mensagem do WhatsApp. O WhatsApp do pedido fica só dentro do carrinho; no rodapé há um link de WhatsApp para dúvidas. O pedido fica guardado no aparelho se a página recarregar.
- **Voltar do celular:** a foto ampliada, o pedido e as abas Tortas e Doces entram no histórico do navegador. O "voltar" fecha a foto ou o pedido, depois volta para Bolos e só então sai do cardápio. Ao recarregar, a página continua na aba em que estava.
- Fonte do conteúdo: Canva "Cardápio Dona Sil - OUT/25".
- Encomendas: WhatsApp (11) 99523-3302 · Instagram [@donasil_](https://instagram.com/donasil_)
