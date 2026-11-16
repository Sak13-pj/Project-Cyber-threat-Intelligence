# Relatório Técnico — Projeto 03
## File and Hash Threat Intelligence

**Organização:** Nexguard Security  
**Ambiente:** TryHackMe — File and Hash Threat Intel  
**Classificação:** Laboratório educacional  
**Status:** Concluído

## 1. Resumo executivo

Foi concluído um laboratório voltado à análise de arquivos e inteligência baseada em hashes. O exercício reforça um fluxo de triagem que combina identificação de artefatos, consulta a fontes de inteligência, interpretação de metadados e contextualização de possíveis indicadores de comprometimento.

Este documento é uma versão inicial para portfólio. Resultados específicos, hashes, nomes de amostras, datas e capturas devem ser inseridos somente após conferência das evidências originais do laboratório.

## 2. Objetivos

- Compreender o uso de hashes como identificadores de arquivos.
- Investigar reputação e contexto de artefatos em fontes de threat intelligence.
- Interpretar metadados e resultados de análise automatizada.
- Distinguir eventos temporais diferentes, como primeira submissão e primeira observação em ambiente real.
- Organizar evidências e conclusões de forma reproduzível.

## 3. Escopo e ambiente

**Laboratório:** https://tryhackme.com/room/fileandhashthreatintel  
**Plataforma:** TryHackMe  
**Ambiente:** laboratório educacional controlado.

O escopo limita-se às atividades do laboratório. Nenhum sistema externo foi testado como parte deste projeto.

## 4. Procedimento técnico

### 4.1 Identificação do artefato
Registrar o nome e a origem do arquivo fornecidos pelo exercício. Preservar o artefato original e evitar alterações que modifiquem seu hash.

### 4.2 Identificação criptográfica
Registrar o algoritmo utilizado e o valor calculado/fornecido. SHA-256 é recomendado para identificação e correlação.

| Campo | Valor |
|---|---|
| Nome do artefato | A preencher |
| SHA-256 | A preencher |
| Fonte do valor | A preencher |
| Data/hora da coleta (UTC) | A preencher |

### 4.3 Enriquecimento de inteligência
Registrar cada fonte consultada, a data/hora, o campo observado e o resultado. Não equiparar automaticamente “first submission”, “first seen” e “first seen in the wild”.

| Fonte | Informação consultada | Resultado/evidência |
|---|---|---|
| VirusTotal | A preencher | A preencher |
| MalwareBazaar | A preencher, se aplicável | A preencher |
| TryDetectThis | A preencher | A preencher |

### 4.4 Análise comportamental e contextualização
Descrever somente comportamentos efetivamente observados. Se houver associação com MITRE ATT&CK, indicar a técnica e a evidência que sustenta o mapeamento.

## 5. Indicadores de comprometimento (IOCs)

Nenhum IOC específico é declarado neste modelo inicial. Preencher a tabela somente com indicadores efetivamente observados e com fonte rastreável.

| Tipo | Indicador | Fonte | Confiança | Observações |
|---|---|---|---|---|
| Hash / domínio / IP / URL | A preencher | A preencher | A preencher | A preencher |

## 6. Limitações e validação

Durante a conclusão do laboratório, uma questão relacionada ao horário da primeira observação do arquivo apresentou divergência entre respostas publicadas em materiais externos e o validador do exercício. Por rigor técnico, esse timestamp não é tratado neste relatório como um fato confirmado. A diferença reforça a necessidade de registrar o nome exato do campo, a fonte, o fuso horário e a data da consulta.

## 7. Conclusão

O laboratório foi concluído e contribuiu para praticar conceitos de análise de arquivos, hashing e threat intelligence. A principal lição operacional é correlacionar múltiplas fontes e preservar contexto e evidências antes de classificar um arquivo ou publicar um IOC.

## 8. Evidências a anexar

- Captura da conclusão da sala (sem dados pessoais).
- Capturas das consultas relevantes.
- Registro de hashes efetivamente observados.
- Resultados de sandbox, se disponíveis e pertinentes.
- Referências das fontes consultadas.

## 9. Segurança e ética

A atividade foi realizada em ambiente educacional autorizado. Arquivos potencialmente maliciosos não devem ser executados em máquinas pessoais ou ambientes não isolados. Dados de terceiros, credenciais e informações sensíveis não devem ser publicados.

**Nexguard Security**  
*Defesa estratégica. Segurança ofensiva.*
