# BluaDiagnostics
Motivos:
- Excelente suporte a function calling.
- Boa relação custo-benefício.
- Alta confiabilidade em respostas estruturadas.

## Riscos Clínicos e Mitigações

### Alucinação
Mitigação: system prompt restritivo e validação humana.

### Diagnóstico Indevido
Mitigação: agente não fornece diagnóstico definitivo.

### Prescrição Sem Médico
Mitigação: qualquer prescrição depende de aprovação médica.

### LGPD
Mitigação: uso apenas de dados mínimos necessários.

### Jailbreak
Mitigação: casos de teste específicos no eval set.

## Arquitetura

O fluxo completo está documentado em `docs/arquitetura.md`.

## Estrutura do Repositório

- `prompts/`: system prompt.
- `evals/`: conjunto de testes.
- `tools/`: especificação das funções.
- `notebooks/`: PoC funcional.
- `docs/`: fluxograma da arquitetura.

## Execução

1. Abra o notebook `notebooks/sprint1_poc.ipynb` no Google Colab.
2. Configure a variável `OPENAI_API_KEY`.
3. Execute todas as células.

## Resultados Esperados

- Conversa com memória de contexto.
- Chamada automática de tools.
- Respostas seguras e contextualizadas.

## Link do Repositório

https://github.com/nathanbiketeixeira/BluaDiagnostics/edit/main/README.md
