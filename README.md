# Projeto e-Ticket

Este é um projeto que utilizei para praticar **JavaScript** e **manipulação do DOM**.

A estrutura em **HTML e CSS** já estava pronta, e minha parte foi desenvolver toda a lógica da aplicação utilizando **JavaScript**.

O objetivo do projeto é simular um **sistema simples de compra de ingressos**, permitindo selecionar o tipo de ingresso, definir a quantidade desejada e realizar a compra, com atualização automática da quantidade disponível.

---

## Funcionalidades Implementadas

- Seleção do tipo de ingresso através de um campo `<select>`
- Validação da quantidade inserida pelo usuário
- Verificação para garantir que a quantidade seja um **número inteiro positivo**
- Verificação de **disponibilidade de ingressos**
- Atualização dinâmica da **quantidade restante de ingressos**
- Exibição de mensagens de erro quando a quantidade solicitada é maior que a disponível
- Exibição de mensagem de **compra realizada com sucesso**
- Separação da lógica em funções específicas para cada tipo de ingresso

---

## Tecnologias Utilizadas

- **HTML** (estrutura da aplicação)
- **CSS** (estilização da interface)
- **JavaScript** (lógica e manipulação do DOM)

---

## Como Funciona

1. O usuário seleciona o **tipo de ingresso**.
2. Insere a **quantidade desejada**.
3. Ao clicar em **Comprar**, o sistema valida a quantidade informada.
4. O sistema verifica se há ingressos suficientes disponíveis.
5. Caso haja disponibilidade, a quantidade comprada é subtraída do estoque.
6. A página atualiza automaticamente a **quantidade restante de ingressos**.

---

Este projeto foi desenvolvido como parte dos exercícios práticos do curso **"Lógica de programação: praticando com desafios"**, disponibilizado pela plataforma **Alura**.
