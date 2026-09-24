# Sala de Sinais — Gold Specialist Dashboard

**Status:** projeto local funcional e extensamente testado. Código mantido privado/local.

> O valor deste case para portfólio é a engenharia de software, QA e integração. Ele não é apresentado como promessa de resultado financeiro.

## Objetivo
Construir um dashboard local para o ativo GOLD integrado ao MetaTrader 5, capaz de adquirir dados em tempo real, validar a qualidade da fonte, gerar estados/sinais manuais, registrar histórico e explicar bloqueios.

## Componentes
- Python, Streamlit e MetaTrader 5
- SQLite e trilha de auditoria
- aquisição e normalização de dados
- state machine de confirmação
- histórico, diagnóstico e relatórios técnicos
- ampla suíte de testes automatizados

## Exemplo de investigação real
Durante a integração foi identificada diferença de horário entre o timestamp do broker e o horário UTC local. Em vez de simplesmente compensar o valor, foi implementado um fluxo de qualificação com coleta de amostras reais, comparação estatística, validação do offset e bloqueio seguro enquanto a fonte não estivesse qualificada.

Um relatório registrou uma janela de **151 amostras em 300 segundos**, classificando o offset do servidor como estável e permitindo normalização somente após a validação.

## QA e testes
A documentação do projeto registra, em uma das etapas de validação, **874 testes automatizados passando**, incluindo proteção contra envio automático de ordens no dashboard manual.

## Competências demonstradas
- debugging de integração com sistema externo
- QA e testes automatizados
- tratamento de dados em tempo real
- SQLite e trilha de auditoria
- observabilidade e análise de causa raiz
- arquitetura fail-safe
- tradução de erro técnico para UX operacional compreensível

## Aplicação freelance
Relevante para **dashboards, automações Python, integrações com APIs/sistemas externos, ferramentas internas, investigação de bugs, pipelines de dados e QA técnico**.
