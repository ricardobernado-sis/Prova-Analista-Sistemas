# Prova-Analista-Sistemas
Prova de Analista de Sistemas Ricardo Bernardo
# 🎓 IESB - Módulo Controle Acadêmico

## 🏗️ Arquitetura da Solução


## 📋 Decisões Arquiteturais

| Decisão | Justificativa |
|---------|---------------|
| **Procedures** | Centraliza regras de negócio no BD |
| **TRY/CATCH** | Transações ACID com rollback |
| **View consolidada** | Facilita relatórios/BI futuro |
| **Camada Serviço** | Separação Controller/Service |
| **Logs auditáveis** | Rastreabilidade obrigatória |

## 🔮 Visão Futura (Integrações)


## 🧪 Testes de Aceitação

1. ✅ Aluno INATIVO → Não abre solicitação
2. ✅ Solicitação FINALIZADA → Não altera
3. ✅ Acesso = ATIVO + Sem pendência
4. ✅ Logs gerados automaticamente
