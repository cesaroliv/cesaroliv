# Live Signal Executor

**Status:** projeto local avançado / protótipo técnico. Código mantido privado/local.

> Este case demonstra automação, integração e QA. Não é apresentado como estratégia de investimento nem como promessa de retorno financeiro.

## Objetivo
Captar comandos humanos de uma transmissão ao vivo, interpretar instruções operacionais e registrá-las ou executá-las em ambiente controlado no MetaTrader 5.

## Componentes
- Python
- captura de áudio e transcrição local
- OCR e captura multi-monitor
- parser de comandos e normalização de símbolos
- consolidação de sinais
- SQLite e auditoria por sessão
- modos observe / paper / live
- integração MetaTrader 5
- risk guard
- painel e diagnóstico

## Segurança operacional

A arquitetura separa explicitamente simulação e execução real, mantém rastreabilidade de posição/sessão e aplica múltiplos gates antes de qualquer ação externa.

## QA
O projeto possui dezenas de arquivos de testes cobrindo parser, configuração, banco, diagnóstico, OCR, detecção visual, pipeline, risk guard e integração mockada com MT5.

## Competências demonstradas
- automação Python
- processamento de áudio e OCR
- integração desktop
- pipelines orientados a eventos
- persistência e auditoria
- testes automatizados
- troubleshooting de sistemas com múltiplas fontes de entrada

## Aplicação freelance
Relevante para **automação de processos, captura e processamento de dados, ferramentas desktop, integrações, OCR, transcrição, QA e pipelines Python**.
