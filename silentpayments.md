# Silent Payments

BIP 352

---

## Privacidade Financeira
(sender privacy)

- **Alice** faz uma doação via PIX para a vítma de enchente **Bob**
    - **Alice** quis cortar intermediários
- agora **Bob** possui o nome completo da **Alice**

---

## Privacidade Financeira
(receiver privacy)

- **Carol** tem uma ong de apoio a um grupo vulnerável que aceita doações via um site de vaquinhas
  - ela forneceu dados pessoais para poder usar o site
  - o dono do site **Dimas** é um adversário da causa
- agora **Dimas** pode "doxar" **Carol**

---
## Bitcoin

- há um pseudonimato, mas como as transações são públicas, linkar os envolvidos é possível
- reuso de endereços públicos é uma má prática
- sempre gerar novos endereços requer algum tipo de interação entre a pagadora e a receptora

---
## Silent Payments

> Silent Payments allow you to create a single, static address to share with friends, use for donations, or post for tips without sacrificing privacy. -- https://silentpayments.xyz/docs

- endereço único
- privacidade para os dois lados da transção
- sem necessidade de um servidor ou comunicação entre as partes

---
## Referências

- https://github.com/bitcoin/bips/blob/master/bip-0352.mediawiki
- https://silentpayments.xyz/
- https://bitcoinops.org/en/topics/silent-payments/
- https://medium.com/@ottosch/how-silent-payments-work-41bea907d6b0
- https://en.wikipedia.org/wiki/Elliptic-curve_Diffie%E2%80%93Hellman
- https://github.com/bitcoin/bitcoin/issues/28536

---
## Demo (sillentium.dev)

- Bluewallet (send)
- Sillentium.dev (receive)


```
sp1qq09mpfa2svdh4v79xmyy4g8zltvf4k9d95lygkn9xt9wgczl8gdpzqse5jr6e23tm3u5mefxmdf2nw04sn92zk4caplguhqr8wg6lj47uqvmdsfa
```
