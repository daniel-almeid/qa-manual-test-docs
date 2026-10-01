# Plano de teste: fluxo de login e checkout (SauceDemo)
**Versão:** 1.0 · **Autor:** Daniel Almeida

## 1. Objetivo
Garantir que login, carrinho e checkout funcionem conforme esperado antes de cada release.

## 2. Escopo
- **Dentro:** autenticação, listagem de produtos, carrinho, checkout.
- **Fora:** pagamento real, performance sob carga, acessibilidade avançada.

## 3. Estratégia
Testes funcionais manuais, exploratórios (sessões de 45 min) e regressão automatizada (Playwright).

## 4. Ambiente
Chrome e Firefox atuais; Android e iOS (responsivo); https://www.saucedemo.com

## 5. Critérios
- **Entrada:** build estável no ambiente de teste.
- **Saída:** 100% dos casos críticos aprovados e nenhum bug crítico ou alto aberto.

## 6. Riscos
Dados de teste compartilhados, instabilidade do ambiente público.
