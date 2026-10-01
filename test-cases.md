# Casos de teste
| ID | Cenário | Passos | Resultado esperado | Prioridade |
|---|---|---|---|---|
| CT-01 | Login válido | Informar standard_user / secret_sauce | Redireciona para inventário | Alta |
| CT-02 | Senha incorreta | Usuário válido + senha errada | Mensagem de credenciais inválidas | Alta |
| CT-03 | Usuário bloqueado | locked_out_user | Mensagem de usuário bloqueado | Média |
| CT-04 | Campos vazios | Clicar em Login sem preencher | "Username is required" | Média |
| CT-05 | Adicionar ao carrinho | Clicar em Add to cart | Badge do carrinho mostra 1 | Alta |
| CT-06 | Remover do carrinho | Remover item | Badge some, carrinho vazio | Média |
| CT-07 | Checkout válido | Preencher dados e finalizar | Tela de confirmação | Alta |
| CT-08 | Checkout sem nome | Continuar com campos vazios | "First Name is required" | Média |
| CT-09 | Ordenar por preço | Low to High | Itens em ordem crescente | Baixa |
| CT-10 | Sessão | Acessar /inventory sem login | Redireciona ao login com erro | Alta |
