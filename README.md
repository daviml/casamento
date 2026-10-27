# Nosso Casamento

App para planejar o orçamento do casamento do Davi e da Letícia: cada item com valor, o que não vamos gastar,
calculadora de comida por convidado, pagamentos e dinheiro guardado. Roda no navegador e instala no celular (PWA).

- **App:** publicado pelo GitHub Pages a partir deste repositório (só código, sem dados).
- **Dados:** ficam no repositório **privado** `casamento-dados` (`dados.json`), sincronizados pelo próprio app.
  Separado do repositório das finanças, para o token da Letícia não ter acesso a elas.

## Conectar um celular
1. Abra o app → **Ajustes** → **Sincronizar os dois celulares**.
2. Repositório: `daviml/casamento-dados`.
3. Token: fine-grained, acesso só ao `casamento-dados`, permissão **Contents: Read and write**.
   No segundo celular, cole o **código de conexão** copiado no primeiro.

## Instalar no celular
Abra o endereço do GitHub Pages no Chrome → menu ⋮ → **Instalar app** / **Adicionar à tela inicial**.
