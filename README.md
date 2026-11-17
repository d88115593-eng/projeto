# GESTIFY PRO — Painel demonstrativo

Este repositório contém o **protótipo interativo do produto** GESTIFY PRO. O foco é a experiência do cliente, **não** a página de vendas, o checkout Black Cat ou os criativos.

## Testar
Abra `index.html` no navegador. É um aplicativo estático sem instalação de dependências.

## Funcionalidades desta versão
- Dashboard responsivo com indicadores, gráfico de faturamento e animações.
- Registro de vendas, despesas, produtos, estoque, clientes e metas.
- Simulador de precificação.
- Alertas básicos de estoque e exportação manual dos registros em JSON.
- Persistência local no navegador (`localStorage`).

## Atenção — não está pronto para comercialização
Esta é uma **demonstração**, com dados fictícios na primeira abertura. Ainda não há login, contas isoladas por empresa, banco de dados, painel Master, expiração de acesso, sincronização entre aparelhos, recuperação de dados nem infraestrutura de produção. Não use para dados sensíveis nem como única cópia das informações do negócio. O estoque não baixa automaticamente nas vendas; o resultado financeiro é estimativo.

## Próximos passos
Criar autenticação, backend e banco de dados com isolamento por cliente, painel Master e auditoria; testar segurança e desempenho; preparar o kit Digital para entrega. Somente depois criar página de vendas e integrar Black Cat.
