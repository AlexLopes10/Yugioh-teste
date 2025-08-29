Este projeto é uma aplicação em React que consome a API YGOProDeck
para listar cartas de Yu-Gi-Oh!, aplicar filtros, adicionar ao carrinho e simular uma finalização de compra.

FUNCIONALIDADE:
 Listagem de cartas diretamente da API.

FILTROS AVANÇADOS POR:
 Tipo (type)
 Atributo (attribute)

 Paginação dinâmica com escolha de itens por página.
 Carrinho persistente usando localStorage.

RESUMO DA COMPRA COM:
 Subtotal
 Tipos de frete (fixo ou combinado)
 Total a pagar

FEEDBACK AO USUARIO:
 Modal de mensagens para ações como adicionar item, limpar filtros ou finalizar compra.

ESTRUTURA:
 busquei deixar componentizado e com CSS separados para melhor organização.

TECNOLOGIAS UTILIZADAS:
 React 18
 React Router DOM (navegação entre páginas)
 Fetch API (requisições à API do YGOProDeck)
 LocalStorage (persistência do carrinho)
 CSS Modules organizados por página e componente

COMO USAR:
 PAGINA INICIAL:
  Veja os banners rotativos.
  Use os filtros para buscar cartas por tipo ou atributo.
  Altere a quantidade de itens exibidos por página.
  Adicione cartas ao carrinho.

 CARRINHO:
  Visualize os itens adicionados com descrição e preço convertido para BRL.
  Escolha o tipo de frete.
  Veja o total da compra.
  Finalize a compra (mensagem de sucesso e carrinho esvaziado).