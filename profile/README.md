# Pack 25 Sistemas IA

25 sistemas MVP para pequenas e médias empresas, feitos para você **clonar, personalizar com Claude Code ou Codex** e implantar para o seu cliente. Cada sistema é um repositório independente, com banco de dados, testes e documentação próprios.

> **Estado atual:** 0 de 25 sistemas disponíveis. Os demais estão em desenvolvimento e **só ganham repositório depois de passar nos testes de qualidade e segurança**. Este material reduz tempo de desenvolvimento; não promete renda nem resultado comercial.

## Como usar um sistema
1. Escolha o sistema na lista abaixo e abra o repositório dele.
2. Clique em **Code** e copie o link de clone.
3. No VS Code, abra a pasta do seu projeto e rode `git clone <link> nome-do-projeto`.
4. Abra a pasta com **Claude Code** ou **Codex** e peça: "leia o AGENTS.md e o MEMORY.md e explique o projeto".
5. Adapte para a empresa do seu cliente, em tarefas pequenas, rodando os testes.

**Importante:** crie um repositório **privado seu** para o projeto do cliente e nunca publique chaves (`.env`) nem dados pessoais do cliente. O guia completo, com a parte de privacidade (LGPD), vem em cada repositório.

## Os 25 sistemas

| # | Sistema | O que faz | Categoria | Estado |
|---|---|---|---|---|
| 01 | **CRM Completo** | Funil de vendas único com histórico, tarefas e indicadores calculados do banco | Comercial | Em desenvolvimento |
| 02 | **Gerador de Propostas** | Propostas padronizadas, versionadas e em PDF, com catálogo e aprovação de desconto | Comercial | Em desenvolvimento |
| 03 | **Qualificação de Leads** | Formulário público com pontuação por regras e distribuição automática ao responsável | Comercial | Em desenvolvimento |
| 04 | **Pós-venda e Recompra** | Alertas de recompra e segmentação simples para contato ativo da equipe | Comercial | Em desenvolvimento |
| 05 | **Portal do Cliente B2B** | Portal onde o cliente abre solicitações, acessa documentos e comenta, isolado por empresa | Comercial | Em desenvolvimento |
| 06 | **Financeiro Completo** | Controle de contas, categorias e fluxo de caixa com lançamentos auditáveis | Gestão | Em desenvolvimento |
| 07 | **Controle de Estoque** | Saldo confiável por depósito com movimentação auditável e alerta de mínimo | Gestão | Em desenvolvimento |
| 08 | **Precificação** | Cálculo transparente de preço, margem e markup com cenários comparáveis | Gestão | Em desenvolvimento |
| 09 | **Dashboard Executivo** | Importação de CSV com mapeamento de colunas e KPIs comparativos por período | Gestão | Em desenvolvimento |
| 10 | **Gestão de Comissões** | Planos de comissão por faixa com estornos e fechamentos rastreáveis | Gestão | Em desenvolvimento |
| 11 | **Agendamento Online** | Reserva pública com disponibilidade real, bloqueios e reagendamento | Operações | Em desenvolvimento |
| 12 | **Central de Chamados** | Tickets com SLA, responsáveis, notas e métricas | Operações | Em desenvolvimento |
| 13 | **Ordens de Serviço** | Ciclo completo da OS com checklist, peças, fotos e aceite simples | Operações | Em desenvolvimento |
| 14 | **Gestão de Projetos** | Quadro Kanban por projeto com prazos, responsáveis e comentários | Operações | Em desenvolvimento |
| 15 | **Gestão de Contratos** | Cadastro de contratos com arquivos, vencimentos e lembretes | Operações | Em desenvolvimento |
| 16 | **Dashboard de Marketing** | Visão consolidada de custo, conversão, ROAS e CPL por importação CSV | Marketing | Em desenvolvimento |
| 17 | **Pesquisa NPS e Satisfação** | Pesquisa pública NPS/CSAT com alertas para detratores e relatório | Marketing | Em desenvolvimento |
| 18 | **Programa de Fidelidade** | Pontos, recompensas e resgates com extrato imutável | Marketing | Em desenvolvimento |
| 19 | **Conteúdo com IA** | Marcas, briefings, calendário e aprovação, com sugestões de IA por ação explícita | Marketing | Em desenvolvimento |
| 20 | **Programa de Afiliados** | Links rastreáveis, leads atribuídos e comissão com aprovação | Marketing | Em desenvolvimento |
| 21 | **CRM Imobiliário** | Funil de negociação com imóveis, visitas e ficha pública do interessado | Verticais | Em desenvolvimento |
| 22 | **Cardápio Digital e Pedidos** | Cardápio público com carrinho, pedidos e painel de cozinha | Verticais | Em desenvolvimento |
| 23 | **Gestão de Academias** | Alunos, planos, agenda, treinos montados pelo profissional e mensalidades administrativas | Verticais | Em desenvolvimento |
| 24 | **Gestão Escolar** | Matrículas, turmas, aulas, presença, parcelas e certificados administrativos | Verticais | Em desenvolvimento |
| 25 | **Gestão de Eventos** | Inscrições com lotes, ingressos QR assinados, check-in único e controle de presença | Verticais | Em desenvolvimento |

## Padrão de qualidade
Isolamento de dados por empresa testado, autenticação com verificação em duas etapas para administradores, auditoria imutável, validação no servidor, guia de LGPD e checklist de segurança em cada sistema.

Cada sistema é MVP e **não** inclui emissão fiscal, assinatura eletrônica certificada, pagamento integrado, disparo em massa nem automação de WhatsApp.
