# README.md - Atividade 04c

## Atividade 3 - Automatização de Tarefas de Banco de Dados com Triggers e Stored Procedures

### Descrição Rápida
Este repositório contém os scripts e a documentação para a automatização de tarefas de banco de dados relacionadas a uma clínica médica. As tarefas automatizadas incluem a aplicação de descontos em cobranças de exames com base no tipo de plano de saúde e a criação de consultas para diferentes relatórios e registros, utilizando `triggers` e `stored procedures` em SQL.

### Descontos em Cobranças de Exames
- **Plano de saúde tipo Especial**: 100% de desconto.
- **Plano de saúde tipo Padrão**: 30% de desconto.
- **Plano de saúde tipo Básico**: 10% de desconto.
- Um `trigger` é ativado a cada inclusão de um pedido de exame, realizando o cálculo do valor a pagar que é registrado automaticamente na tabela correspondente.

### Stored Procedures Criados
- **Agenda de médicos**: Procedimento para consultar a agenda dos médicos.
- **Exames solicitados**: Procedimento para listar os exames solicitados.
- **Histórico de pagamentos**: Procedimento para acessar o histórico de pagamentos.
- **Resumo de pagamentos**: Procedimento para obter um resumo dos pagamentos.

### Observações Importantes
- Todos os scripts SQL foram testados e validados conforme os critérios fornecidos.
- É necessário ter as permissões adequadas no SGBD para criar triggers e stored procedures.

---

**Nota**: Os scripts são específicos para o banco de dados da clínica médica e devem ser ajustados conforme necessário para outros contextos ou requisitos.