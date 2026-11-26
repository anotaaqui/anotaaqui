<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img src="assets/banner-light.svg" alt="anota.aqui — software local-first para restaurantes" width="100%">
  </picture>
</p>

<h1 align="center">anota.aqui</h1>

<p align="center">
  <a href="https://github.com/anotaaqui"><img src="https://img.shields.io/badge/GitHub-anotaaqui-16140f?style=flat-square&logo=github&logoColor=f7f3ea" alt="GitHub"></a>
  <a href="mailto:zionfmbrasil@gmail.com"><img src="https://img.shields.io/badge/e--mail-zionfmbrasil@gmail.com-c4442a?style=flat-square&logo=gmail&logoColor=ffffff" alt="E-mail"></a>
  <img src="https://img.shields.io/badge/Brasil-pt--BR-2f9e6e?style=flat-square" alt="Brasil">
  <img src="https://img.shields.io/badge/licen%C3%A7a-MIT-16140f?style=flat-square" alt="Licença MIT">
  <img src="https://img.shields.io/badge/local--first-sim-2f6fed?style=flat-square" alt="Local-first">
</p>

---

## Sobre

Sou contratado para resolver os grandes problemas de grandes empresas, sobrevivendo sob o jugo do capitalismo que trata tudo como mercadoria, como também nos conduz a ver tudo como comercializável. <p></p> Quase esquecemos que somos agentes de mudança e com potencia.<p></p> Usando o pouco tempo e recurso que capitalismo não vampirizou, desenvolvi o **anota.aqui**, um console de operação para restaurantes que roda na máquina do restaurante. A ideia é simples: o pedido sai do WhatsApp, passa pela cozinha, vira entrega, fecha a conta e termina no pós-venda — sem planilha no meio e sem servidor central.

O projeto é **local-first**, **MIT** e **grátis e sempre será**. LLM e Mercado Pago são opcionais; o fluxo inteiro funciona com ou sem eles.

## Agora

- Construindo o console: pedidos, cozinha, entrega, pagamento, mapa e pós-venda.
- Afinando o atendimento no WhatsApp: leitura assistida, sugestões, envio opcional e supervisor de mensagens.
- Deixando o cardápio vivo: importar, ativar, desativar e manter o histórico.
- Testando o fluxo inteiro em um restaurante de verdade.

## Como eu penso

> Software de restaurante não precisa de servidor central, assinatura e nem de um robô falando com o cliente. Precisa resolver o turno.

- **Local-first.** Os dados ficam com quem produz o pedido.
- **Humano no comando.** O sistema sugere; a pessoa decide e confirma.
- **Sem dependência.** LLM e Mercado Pago são escolhas, não pré-requisitos.
- **Simples de rodar.** Um console, um banco local, um navegador.

## Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=ffffff" alt="Python">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=ffffff" alt="SQLite">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=16140f" alt="JavaScript">
  <img src="https://img.shields.io/badge/WebDriver%20BiDi-FF7139?style=flat-square&logo=firefox&logoColor=ffffff" alt="WebDriver BiDi">
  <img src="https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=flat-square&logo=openstreetmap&logoColor=ffffff" alt="OpenStreetMap">
  <img src="https://img.shields.io/badge/Mercado%20Pago-00B1EA?style=flat-square&logo=mercadopago&logoColor=ffffff" alt="Mercado Pago">
  <img src="https://img.shields.io/badge/DeepSeek-4D6BFE?style=flat-square&logo=openai&logoColor=ffffff" alt="DeepSeek">
</p>

## Projetos

| Projeto | O que é | Estado |
| --- | --- | --- |
| **anota.aqui** | Console local-first para restaurantes: WhatsApp assistido, pedidos, cozinha, entrega, Pix e pós-venda. | em desenvolvimento |
| **anotaaqui.github.io** | Landing page do projeto, com a jornada e os recursos atuais. | público · [site](https://anotaaqui.github.io/) |
| **anotaaqui** | Este perfil. | público |

> O código da aplicação está privado por enquanto. Quando abrir, será sob MIT.

<details>
<summary><strong>O que tem por dentro do anota.aqui</strong></summary>

<br>

- **Console local:** Python + SQLite + interface web servida em `127.0.0.1`.
- **WhatsApp assistido:** leitura da conversa via WebDriver BiDi, preenchimento sem apertar Enter e envio automático opcional.
- **Pedido com estado:** rascunho, pagamento, cozinha, entrega, cancelamento e pós-venda.
- **Cardápio vivo:** importação do KiCardápio, ativação e desativação de pratos sem apagar o cadastro.
- **Entrega:** endereço, referência, acesso, taxa configurável, previsão e mapa com OpenStreetMap.
- **Pagamento:** Pix pelo Mercado Pago, Pix manual ou dinheiro/cartão na entrega.
- **Cozinha:** KDS, alerta de atraso, comanda térmica e baixa em um toque.
- **Pós-venda:** tentativa de retenção no cancelamento, encerramento e retomada na próxima saudação.
- **Supervisor:** mensagens não respondidas, fila travada e erro de envio são retomados automaticamente.
- **Sem servidor central:** o banco e os dados ficam na máquina do restaurante.

</details>

## Contato

- GitHub: [@anotaaqui](https://github.com/anotaaqui)
- E-mail: [zionfmbrasil@gmail.com](mailto:zionfmbrasil@gmail.com)

<p align="center"><sub>Feito com calma, café e SQLite.</sub></p>
