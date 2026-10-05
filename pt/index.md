---
layout: default
lang: pt-BR
permalink: /pt/
alt_url: /
description: Uma lista de mercado aconchegante para a família. Toque no que precisa e o item vai para o topo.
---

<div class="hero">
  <img src="{{ '/assets/mascot.png' | relative_url }}" alt="Uma raposa apoiando o queixo numa cesta de vime">
  <h1>Foxy Basket</h1>
  <p class="tagline">Listas de mercado com cara de casa.</p>
  {% if site.app_store_url %}
  <a class="badge" href="{{ site.app_store_url }}">Baixar na App Store</a>
  {% else %}
  <p class="muted">Em breve na App Store para iPhone.</p>
  {% endif %}
</div>

<div class="cards">
  <div class="card">
    <h3>Ela lembra</h3>
    <p>Sua lista guarda tudo o que você sempre compra. Toque no que precisa nesta ida ao mercado e o item sobe para o topo. No mercado, toque de novo e ele volta para baixo, pronto para a próxima semana.</p>
  </div>
  <div class="card">
    <h3>Na sua ordem</h3>
    <p>Ordene por corredor, de A a Z ou por categoria, ou crie uma ordem personalizada para o seu mercado. Cada pessoa da lista escolhe a sua.</p>
  </div>
  <div class="card">
    <h3>Feita para a família</h3>
    <p>Convide pelo @usuário ou e-mail, escolha quem pode adicionar, editar ou excluir, e veja as mudanças na hora.</p>
  </div>
</div>

## Privada de verdade

Suas listas só aparecem para quem você convida. Não há anúncios nem rastreamento, e você pode excluir sua conta e tudo o que há nela em Ajustes. Leia a [política de privacidade]({{ '/pt/privacidade/' | relative_url }}).
