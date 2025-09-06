# Meetup LFDT Brasil — Ptah: Privacidade e Interoperabilidade em Ecossistemas Financeiros (02/set/2025)

**Quando:** 02 de setembro de 2025, 19:00 (BRT)  
**Onde:** online — Meetup LFDT SP  
**Tema:** Framework Ptah para privacidade-by-design, atomicidade e composabilidade em redes tokenizadas e reguladas (RTMN), com aplicações a Drex e multi-ativos. :contentReference[oaicite:0]{index=0}

## Gravação
- YouTube (live): https://www.youtube.com/live/JuVM0tLGdSY

## Materiais do evento
- **Folder/convite** (PDF): *LFDT Brazil Chapter Meetup | Ptah* — informações de agenda e contexto do encontro. :contentReference[oaicite:1]{index=1}  
- **Slides (BBChain / Ptah)** (PDF): visão executiva do projeto, fundamentos (Zero Trust, compartmentalization), blueprint (Transaction/Balance Nodes, Matcher/Dispatcher/Governance), sequência transacional, e Ptah Explorer. :contentReference[oaicite:2]{index=2}  
- **Paper (TechRxiv)** (PDF): *Applying a Distinguished Framework to Ensure Privacy-by-Design and Composability in a Regulated Tokenized Multi-Asset Network* — fundamentos teóricos, requisitos (atomicidade, finality, privacidade), arquitetura modular e avaliação de aplicabilidade (ex.: títulos públicos federais). :contentReference[oaicite:3]{index=3}

## Palestrantes
- **André Luiz de Souza Carneiro (CEO, BBChain):** especialista em Blockchain Business Architecture no setor financeiro; MBA FIA/USP; liderança da BBChain desde 2020. :contentReference[oaicite:4]{index=4}  
- **Rodrigo Gonçalves Bueno (CTO, BBChain):** cofundador; especialista em computação distribuída/Big Data; arquiteto de soluções; contribuidor de Corda no Brasil. :contentReference[oaicite:5]{index=5}  
- **João Paulo Aragão Pereira (PhD):** inovação em serviços financeiros, sistemas multiagentes, IA/GenAI; atuação em PIX, Open Finance e piloto Drex; pesquisa em privacidade e governança aplicada. :contentReference[oaicite:6]{index=6}

## Resumo do conteúdo
O meetup apresentou o **Ptah** como um framework modular e distribuído para **redes tokenizadas reguladas (RTMN)**, com **privacidade por compartimentalização criptográfica**, **atomicidade (2PC)**, **composabilidade/programmability** e **finalidade de liquidação**, preservando auditoria regulatória. A arquitetura separa **Matcher** (assinaturas), **Dispatcher** (movimentos), **Executor/2PC** (contexto completo) e **Balance Nodes** (ordem e não-duplo gasto), reduzindo superfícies de observação de dados. São discutidos interoperabilidade (UL/Finternet), mensageria assíncrona (Kafka), e camadas de dados (SQL + CRDT + DLT). :contentReference[oaicite:7]{index=7} :contentReference[oaicite:8]{index=8}

### Pontos-chave
- **Privacidade-by-design:** cada serviço vê apenas o mínimo necessário; o contexto completo fica no executor/2PC. :contentReference[oaicite:9]{index=9}  
- **Sequência transacional:** validação → matching/aggregation → execução 2PC (prepare/commit) → prova/finality (opcional rollup/ZK). :contentReference[oaicite:10]{index=10}  
- **Interoperabilidade e multiativos:** integração entre depósitos tokenizados, CBDC, títulos e outros RWAs; coordenação assíncrona e finality determinística. :contentReference[oaicite:11]{index=11}  
- **Exploradores e serviços de rede:** Governance (endereçamento/rotas), Matcher, Dispatcher, Uniqueness e Proof of Transactions. :contentReference[oaicite:12]{index=12}

## Links úteis
- Página do meetup: https://www.meetup.com/lfdt-sao-paulo/events/310729917/ :contentReference[oaicite:13]{index=13}
- Slides (Google): https://docs.google.com/presentation/d/1x6rcQ3oE2FcDU-xi7cvkiaBqweu8UtcUCoUqAgXHQG8/edit :contentReference[oaicite:14]{index=14}
- Paper (TechRxiv): https://doi.org/10.36227/techrxiv.175070238.83562629/v1 :contentReference[oaicite:15]{index=15}

## Como citar
> Bueno, R. G.; Carneiro, A. L. S.; Pereira, J. P. A. *Applying a Distinguished Framework to Ensure Privacy-by-Design and Composability in a Regulated Tokenized Multi-Asset Network*. TechRxiv, 23 jun. 2025. DOI: 10.36227/techrxiv.175070238.83562629/v1. :contentReference[oaicite:16]{index=16}

## Agradecimentos
Evento organizado pelo Capítulo Brasil da LFDT. A participação foi aberta e gratuita à comunidade. :contentReference[oaicite:17]{index=17}
