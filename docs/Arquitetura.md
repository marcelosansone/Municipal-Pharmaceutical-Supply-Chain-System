##ARQUITETURA SaaS E API
Sistema de Gestão de Estoque e Supply Chain Farmacêutico Municipal
1. VISÃO GERAL DA ARQUITETURA
O sistema será desenvolvido em arquitetura SaaS modular, baseada em APIs REST, garantindo:
– Escalabilidade
– Segurança
– Auditabilidade
– Integração futura com outros sistemas (ex: prontuário, compras, financeiro)
1.1 Camadas da arquitetura
Camada de Apresentação (Frontend)
Interface Web (PC / tablet)
Telas específicas:
Farmácia Central
Unidades de Saúde
Gestão
Auditoria
Camada de Aplicação (API)
FastAPI (Python)
Validação rigorosa de dados
Regras de negócio centralizadas
Camada de Dados
PostgreSQL (dados transacionais)
Estrutura preparada para séries temporais
Camada de Segurança
Autenticação
Autorização por perfil
Logs e trilhas de auditoria
