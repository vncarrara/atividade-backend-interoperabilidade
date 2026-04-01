# Atividade Backend Interoperabilidade
Implementação de processamento assíncrono com XMLHttpRequest para a home page do e-commerce Brasil

## Resumo Visual do Ciclo de Requisição

Para facilitar a implementação pela equipe de desenvolvimento, seguiremos o fluxo abaixo em cada requisição:

1. Quando o usuário clica: Interação do usuário (clique/filtro) ativa o JavaScript.

2. Instanciação: Criação do objeto new XMLHttpRequest().

3. Configuração: Definição do método (GET/POST), URL e parâmetro async: true.

4. Headers: Configuração de metadados (ex: Authorization, Content-Type).

5. Event Handlers: Registro de funções para monitorar o status (onload, onerror).

6. Disparo (Send): Envio da requisição em segundo plano, mantendo a UI responsiva, ou seja, sem, travar.

7. Processamento: Recebimento do JSON, tratamento de erros e atualização dinâmica do DOM.

## Benefícios

- Experiência de Usuário (UX): Navegação fluida sem recarregamentos de página (Zero Refresh).

- Performance de Rede: Redução drástica no consumo de dados, trafegando apenas o necessário via JSON.

- Escalabilidade: Possibilidade de múltiplas requisições paralelas para diferentes microserviços.

- Resiliência: Controle total sobre cancelamentos (xhr.abort()) e tratativas de erro granulares.
