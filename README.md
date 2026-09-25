# Raízes do Nordeste — protótipo acadêmico

Protótipo estático de um sistema de pedidos para uma rede de alimentação, com identidade visual inspirada nas raízes nordestinas. A mesma base simula três canais: **site**, **app** e **totem**.

## Executar

Abra `index.html` no navegador. Também é possível usar um servidor local:

```bash
python3 -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Funcionalidades demonstradas

- Navegação por Cardápio, Fidelidade e Meu pedido;
- Fotos do Combo Sertão, Tapioca da Feira e Cuscuz Nordestino;
- Seleção de unidade e produtos;
- Inclusão de quantidade e cálculo do total;
- Consentimento explícito para uso dos dados (LGPD);
- Tela de pagamento **MOCK**, sem cobrança e sem integração real;
- Layout responsivo e modos site, app e totem;
- Mensagens de sucesso e erro para apoiar testes de qualidade de software.

## Estrutura

- `index.html`: interface, cardápio e tela de pagamento mock;
- `styles.css`: visual responsivo e identidade nordestina;
- `app.js`: regras simples do pedido e validações;
- `assets/hero-nordeste.jpg`: imagem principal;
- `assets/combo-sertao.jpg`: foto do Combo Sertão;
- `assets/tapioca-feira.jpg`: foto da Tapioca da Feira;
- `assets/cuscuz-nordestino.jpg`: foto do Cuscuz Nordestino.

## Qualidade de software demonstrada

O protótipo contém requisitos verificáveis: responsividade, validação de consentimento LGPD, mensagens de erro, fluxo de pagamento simulado e separação entre interface, estilos e regras. O pagamento mock é proposital para atender ao escopo acadêmico, sem processar dados financeiros reais.

