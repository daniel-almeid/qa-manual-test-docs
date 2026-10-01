# BUG-001: Checkout aceita CEP com letras
**Severidade:** Média · **Prioridade:** Média · **Status:** Aberto
**Ambiente:** Chrome 130, Windows 11, build de teste

## Passos para reproduzir
1. Fazer login com standard_user.
2. Adicionar qualquer produto e abrir o checkout.
3. Preencher nome e sobrenome; no CEP digitar "abcde".
4. Clicar em Continue.

## Resultado atual
O sistema avança para a revisão do pedido.

## Resultado esperado
Bloquear o avanço e exibir mensagem de CEP inválido.

## Evidência
Anexar screenshot ou vídeo (print da tela de revisão com CEP "abcde").

*Exemplo ilustrativo do formato de bug report.*
