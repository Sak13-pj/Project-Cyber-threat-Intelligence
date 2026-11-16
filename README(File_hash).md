# Projeto 03 — File and Hash Threat Intelligence

**Organização:** Nexguard Security  
**Trilha:** SOC / Threat Intelligence  
**Plataforma:** TryHackMe  
**Laboratório:** [File and Hash Threat Intel](https://tryhackme.com/room/fileandhashthreatintel)  
**Status:** Concluído  
**Tipo:** Laboratório educacional em ambiente controlado

## 1. Objetivo

Documentar um fluxo de análise de arquivos suspeitos e indicadores de comprometimento (IOCs), utilizando hashes e fontes de inteligência de ameaças para apoiar a triagem e a investigação defensiva.

## 2. Escopo

Este projeto registra o estudo dos seguintes conceitos e atividades abordados no laboratório:

- Identificação e análise de arquivos por meio de hashes.
- Consulta e interpretação de informações em plataformas de threat intelligence.
- Correlação de metadados e reputação de arquivos.
- Consulta a fontes como VirusTotal e MalwareBazaar, conforme aplicável ao exercício.
- Interpretação de informações de sandbox e comportamento de arquivos.
- Contextualização de indicadores com a base MITRE ATT&CK, quando houver evidência suficiente.

> **Limite da documentação:** este repositório não afirma que um arquivo é malicioso apenas por sua reputação, nem apresenta IOCs, datas, técnicas ou resultados específicos sem evidência registrada. Os campos ainda não preenchidos devem ser completados a partir das anotações e capturas reais do laboratório.

## 3. Metodologia de análise

1. **Identificação:** registrar o nome do arquivo e sua origem dentro do laboratório.
2. **Hashing:** calcular ou coletar hashes (por exemplo, SHA-256) para identificar o artefato de forma consistente.
3. **Enriquecimento:** consultar fontes de inteligência e comparar reputação, prevalência, datas e metadados.
4. **Análise contextual:** avaliar detecções, relações e resultados de sandbox sem tratar um único indicador como prova conclusiva.
5. **Mapeamento:** associar comportamentos observados a técnicas MITRE ATT&CK somente quando houver evidência.
6. **Conclusão:** registrar o nível de confiança, limitações e próximos passos defensivos.

## 4. Ferramentas e fontes

- TryHackMe — ambiente educacional e roteiro do laboratório.
- VirusTotal — reputação, relações e metadados de arquivos.
- MalwareBazaar — inteligência sobre amostras, quando utilizada no exercício.
- TryDetectThis — recurso associado ao laboratório.
- MITRE ATT&CK — referência para contextualização de técnicas.

A lista acima identifica ferramentas e referências relacionadas ao estudo; não significa que todos os recursos tenham sido usados em cada etapa ou que todos os resultados tenham sido validados independentemente.

## 5. Resultados

**Status do laboratório:** concluído.

Os resultados técnicos específicos devem ser registrados em `analises/` e acompanhados por evidências em `evidencias/`. Não inclua amostras maliciosas, arquivos executáveis ou dados de terceiros no repositório público.

| Item | Registro |
|---|---|
| Sala | File and Hash Threat Intel |
| Plataforma | TryHackMe |
| Conclusão | Concluída |
| Evidências anexadas | A preencher |
| IOCs confirmados | A preencher com evidência |
| Data/hora de execução | A preencher |

## 6. Observações de qualidade

Durante a atividade, houve divergência entre timestamps encontrados em materiais externos e o validador da sala para uma questão sobre primeira observação de um arquivo no mundo real. Por isso, nenhum timestamp deve ser publicado como fato confirmado sem preservar a fonte, o campo consultado e o contexto temporal.

## 7. Aprendizados

- Um hash identifica o conteúdo de um arquivo, mas não determina sozinho se ele é malicioso.
- Resultados de múltiplos mecanismos de detecção exigem contexto e validação.
- Datas como *first submission*, *first seen* e *first seen in the wild* podem representar eventos diferentes.
- IOCs precisam de contexto, fonte e grau de confiança para serem úteis em uma investigação.
- O mapeamento MITRE ATT&CK deve refletir comportamentos observados, não suposições.

## 8. Próximas melhorias

- Adicionar capturas próprias, com informações sensíveis ocultadas.
- Registrar hashes e IOCs efetivamente observados.
- Incluir fontes e horários de consulta.
- Documentar uma análise de amostra com cadeia de evidências, sem executar arquivos fora de ambiente isolado.
- Revisar o relatório antes da publicação.

## 9. Aviso

Este material descreve um exercício educacional realizado em laboratório autorizado. Não constitui uma análise forense independente de uma amostra real nem autorização para testar sistemas de terceiros.

---

**Nexguard Security**  
*Defesa estratégica. Segurança ofensiva.*
