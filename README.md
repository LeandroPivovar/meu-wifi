# Meu WiFi - site institucional

Site one-page da **Meu WiFi**: locação de internet via satélite para eventos, com seção especial de Wi-Fi para pesca.

## Estrutura

```
index.html   # página única (hero, sobre, eventos, pesca, depoimentos, mapa, FAQ)
styles.css   # estilos (tema claro/escuro automático, laranja da marca)
script.js    # link do WhatsApp, menu mobile, header, animações, carrossel, FAQ
assets/      # favicon e fotos
```

Sem build: HTML, CSS e JS puros. Publique a pasta em GitHub Pages, Netlify, Vercel ou hospedagem comum.

## Dados usados (perfil do WhatsApp Business)

- Telefone/WhatsApp: +55 84 9842-8445 (`wa.me/558498428445`, constante `WHATSAPP` no `script.js`)
- Atendimento 24 horas
- Categoria: promotor de eventos, serviços Wi-Fi e locação para eventos
- Logo: internet de alta velocidade em qualquer lugar, com antena de satélite

O botão da seção de pesca abre o WhatsApp com uma mensagem própria (atributo `data-msg`).

## Antes de publicar

- **Região**: o mapa mostra o Rio Grande do Norte (DDD 84). Se houver cidade base, troque `Rio+Grande+do+Norte` no `src` do iframe.
- **Depoimentos** são exemplos. Substitua por avaliações reais de clientes.
- **Pesca**: confirme com a empresa o alcance a bordo, se a antena é instalada no barco e como funciona a energia.
- **FAQ**: confirme capacidade de pessoas, necessidade de energia e prazos de reserva.
- **Logo**: o cabeçalho usa um selo laranja com ícone de Wi-Fi. Para usar o logo oficial, salve em `assets/` e troque o bloco `.brand`.

## Créditos das imagens

Fotos via [Unsplash](https://unsplash.com) (licença Unsplash).
