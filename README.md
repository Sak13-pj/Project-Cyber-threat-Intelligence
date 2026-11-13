# NEXGUARD SECURITY

## Projeto 02 --- Intro to Cyber Threat Intelligence

**Defesa estratégica. Segurança ofensiva.**

> Projeto educacional concluído no TryHackMe, com foco em fundamentos de
> Cyber Threat Intelligence (CTI), enriquecimento de indicadores e
> aplicação de inteligência no contexto de operações de segurança (SOC).

------------------------------------------------------------------------

## 1. Visão geral

Este projeto documenta a conclusão da sala **[Intro to Cyber Threat
Intel](https://tryhackme.com/room/cyberthreatintel)**, do TryHackMe.

A atividade aborda como transformar dados e indicadores isolados em
inteligência contextualizada e útil para apoiar a triagem de alertas, a
investigação de incidentes e a tomada de decisões defensivas.

**Status:** Concluído --- 100% das tarefas, incluindo a etapa *Practical
Analysis*.

## 2. Objetivos de aprendizagem

-   Compreender o papel da Cyber Threat Intelligence em um SOC.
-   Diferenciar dados, informações e inteligência.
-   Reconhecer indicadores de comprometimento (IOC), indicadores de
    ataque (IOA) e TTPs.
-   Conhecer fontes de inteligência e práticas de enriquecimento de
    indicadores.
-   Entender as classificações estratégica, tática, operacional e
    técnica.
-   Compreender o ciclo de vida da inteligência de ameaças.
-   Conhecer padrões, frameworks e mecanismos de compartilhamento de
    CTI.
-   Aplicar os conceitos em uma atividade prática de análise.

## 3. Conteúdos estudados

### Fundamentos de CTI

-   Finalidade da inteligência de ameaças no processo de triagem e
    investigação.
-   Transformação de dados brutos em informação contextualizada e
    inteligência acionável.
-   Relação entre CTI, SOC e resposta a incidentes.

### Indicadores e comportamento de ameaças

-   **IOC (Indicator of Compromise):** artefato que pode indicar
    comprometimento.
-   **IOA (Indicator of Attack):** comportamento ou atividade que pode
    indicar um ataque em andamento.
-   **TTPs:** táticas, técnicas e procedimentos associados ao
    comportamento de adversários.
-   Tipos de indicadores: endereços IP, domínios, URLs, hashes,
    endereços de e-mail e artefatos locais.

### Fontes e enriquecimento

-   Telemetria interna, como logs de SIEM e alertas de EDR.
-   Fontes comerciais e feeds de inteligência.
-   OSINT e comunidades de compartilhamento.
-   Validação, correlação, contexto, confiabilidade e relevância dos
    indicadores.

### Classificações de inteligência

-   **Estratégica:** tendências e riscos que apoiam decisões de alto
    nível.
-   **Tática:** técnicas e comportamentos utilizados por adversários.
-   **Operacional:** contexto de campanhas, objetivos e intenção.
-   **Técnica:** indicadores e artefatos específicos, como IPs e hashes.

### Ciclo de vida de CTI

-   Direção e planejamento.
-   Coleta.
-   Processamento.
-   Análise.
-   Disseminação.
-   Feedback.

### Padrões e frameworks

-   MITRE ATT&CK.
-   MITRE D3FEND.
-   Cyber Kill Chain.
-   CVE, CVSS e NVD.
-   STIX e TAXII.
-   Traffic Light Protocol (TLP).

## 4. Aplicação prática

A sala inclui uma atividade de análise prática baseada em um cenário de
investigação. Nela, os conceitos de CTI são aplicados para construir um
perfil de ameaça a partir de artefatos e informações disponíveis no
ambiente de aprendizagem.

**Resultado informado:** conclusão de 100% da sala, incluindo a tarefa
*Practical Analysis*.

Este README não reproduz respostas da sala, dados sensíveis ou
informações que possam comprometer o ambiente de aprendizagem.

## 5. Relevância para operações SOC

Os conhecimentos abordados são aplicáveis a atividades de nível inicial
em operações de segurança, especialmente:

-   Triagem e priorização de alertas.
-   Enriquecimento e contextualização de IOCs.
-   Pesquisa em fontes OSINT.
-   Identificação de comportamentos e TTPs.
-   Apoio à investigação e ao escalonamento de incidentes.
-   Compartilhamento responsável de inteligência.

## 6. Competências demonstradas

-   Fundamentos de Threat Intelligence.
-   Interpretação e classificação de indicadores.
-   Compreensão do ciclo de inteligência.
-   Familiaridade com frameworks e padrões de CTI.
-   Análise contextual de ameaças.
-   Documentação técnica de atividade prática.

## 7. Evidências

As evidências visuais da conclusão e da atividade prática podem ser
adicionadas nesta seção.

Sugestão de organização:

``` text
Projeto-02-Cyber-Threat-Intelligence/
├── README.md
├── evidencias/
│   ├── conclusao-sala.png
│   └── practical-analysis.png
└── relatorio/
    └── (relatorio, se aplicavel)
```

> Adicione somente capturas próprias, removendo informações pessoais,
> tokens, credenciais ou outros dados sensíveis. Não inclua respostas
> que violem as regras da plataforma.

## 8. Referências

-   [TryHackMe --- Intro to Cyber Threat
    Intel](https://tryhackme.com/room/cyberthreatintel)
-   [MITRE ATT&CK](https://attack.mitre.org/)
-   [MITRE D3FEND](https://d3fend.mitre.org/)
-   [FIRST --- Traffic Light Protocol (TLP)](https://www.first.org/tlp/)
-   [OASIS --- STIX](https://oasis-open.github.io/cti-documentation/)
-   [OASIS --- TAXII](https://oasis-open.github.io/cti-documentation/)

## 9. Escopo e autorização

Atividade realizada em ambiente educacional disponibilizado pelo
TryHackMe. O conteúdo deste repositório tem finalidade de estudo e
demonstração de aprendizagem. Não representa uma avaliação de segurança
de sistemas de terceiros.

------------------------------------------------------------------------

**NEXGUARD SECURITY**\
*Defesa estratégica. Segurança ofensiva.*
