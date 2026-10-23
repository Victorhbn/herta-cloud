# HertaCloud: propostas de produtos para desenvolvimento futuro

> **Versão 0.1 · 23/10/2026 · uso interno**
> Base: *Business Plan*, *Marketing, comercial e mídia kit* e *Abertura e backoffice* (v1.0, 22/10/2026).
> O **Herta Gateway** é uma proposta nova: não consta nos documentos de origem e precisa de validação de negócio, jurídica e regulatória antes de qualquer compromisso comercial.

Este documento reúne, por produto, o que já está decidido, o que é hipótese e o que falta decidir antes de construir. Preços e metas citados são **hipóteses não validadas**: não devem ir para material comercial nem para o site.

---

## Sumário

1. [Visão geral do portfólio](#1-visão-geral-do-portfólio)
2. [Princípios comuns a todas as linhas](#2-princípios-comuns-a-todas-as-linhas)
3. [Herta Protect](#3-herta-protect)
4. [Herta Data](#4-herta-data)
5. [Herta Insight](#5-herta-insight)
6. [Herta Billing](#6-herta-billing)
7. [Herta Gateway (novo)](#7-herta-gateway-novo)
8. [Herta Action (radar)](#8-herta-action-radar)
9. [Herta AI Analyst (radar)](#9-herta-ai-analyst-radar)
10. [Sequência sugerida](#10-sequência-sugerida)
11. [Comunicação no site](#11-comunicação-no-site)
12. [Decisões em aberto](#12-decisões-em-aberto)

---

## 1. Visão geral do portfólio

| Produto | O que é | Estágio | Libera comercialmente quando… |
|---|---|---|---|
| **Protect** | Backup, monitoramento, testes, restauração e relatório | Oferta principal | Laboratório pronto, contrato validado e cobertura técnica definida |
| **Data** | Inventário, mapa de fontes, qualidade, acesso e governança | Diagnóstico ou projeto | Houver escopo fechado por projeto |
| **Insight** | KPIs, integrações autorizadas, painéis e revisão gerencial | Pilotos pagos | 2 a 3 pilotos pagos concluídos, antes de padronizar |
| **Billing** | Cobranças e recebimentos para clínicas | Em piloto (1 clínica) | Projeto com caixa, responsável e aceite próprios |
| **Gateway** | Gateway de pagamento próprio, sem custódia | Em breve (proposta) | Ver [critérios de lançamento](#710-critérios-de-lançamento) |
| **Action** | Alertas e automações com logs e tratamento de exceções | Radar | Fontes e regras de negócio estáveis |
| **AI Analyst** | Consulta e análise assistida sobre dados preparados | Radar | Controles, teste de qualidade e revisão humana |

**Ciclo de valor:** proteger → organizar → interpretar → agir. Não lançar todas as linhas ao mesmo tempo. A venda começa com uma dor e uma entrega; a expansão vem depois de uso, capacidade e margem observados.

---

## 2. Princípios comuns a todas as linhas

### 2.1 Arquitetura de receita
- **Diagnóstico pago + implantação + mensalidade.**
- São adicionais: projetos de integração, novos painéis, usuários, canais, volumes e suporte extraordinário.
- Taxas de terceiros (provedores, licenças, tráfego) ficam sempre explícitas.
- Nunca oferecer integrações, armazenamento ou desenvolvimento ilimitados.

### 2.2 Comunicação
- Não prometer recurso ainda não entregue, proteção absoluta, resultado financeiro garantido nem "tempo real" sem demonstração técnica.
- Interfaces mostradas antes da entrega são sempre rotuladas como **interface ilustrativa**.
- Não inventar clientes, depoimentos, certificações, números ou parcerias.

### 2.3 Segurança e privacidade (linha de base)
| Controle | Aplicação |
|---|---|
| Papéis | Definir controlador e operador por atividade; não presumir papel único |
| Dados mínimos | Coletar só o necessário. Billing e Gateway sem prontuário, diagnóstico ou descrição desnecessária de tratamento |
| Acessos | Contas individuais, MFA, menor privilégio e revisão periódica de permissões |
| Isolamento | Ambientes e dados de cada cliente segregados |
| Fornecedores | Mapear suboperadores, localização dos dados e transferência internacional |
| Incidentes | Identificar, conter, preservar evidências e acionar responsáveis. A regra geral da ANPD para incidente com risco ou dano relevante prevê comunicação em 3 dias úteis; validar o enquadramento com o jurídico |
| Continuidade | Testes documentados, responsável substituto e plano de resposta |

### 2.4 Capacidade
- Se 70% da agenda técnica útil ficar comprometida por dois meses, é preciso substituir, contratar ou limitar vendas.
- Billing e Gateway só avançam com recursos reservados e sem prejudicar a operação do Protect.

---

## 3. Herta Protect

**Estágio:** oferta principal · **Público inicial:** escritórios contábeis de 10 a 30 pessoas

### 3.1 Problema
O comprador (sócio ou gestor administrativo) não sabe quais dados podem ser recuperados, por quem e em quanto tempo. A TI interna, o prestador e o fornecedor do ERP influenciam a decisão.

### 3.2 Entrega proposta
- Monitoramento automatizado das rotinas de cópia
- Revisão humana em dias úteis, das 9h às 18h, no fuso contratado
- Amostra mensal de restauração
- Teste trimestral de recuperação de um objeto crítico acordado
- Relatório mensal de uma página: cobertura, cópias válidas, testes, falhas e ações
- Um responsável por conta e caminho de escalonamento
- Portabilidade, documentação e plano de encerramento definidos no início

**Fora de escopo:** perícia forense, remoção de invasores, reconstrução ilimitada, atendimento humano 24/7 e ambientes não homologados.

### 3.3 Oferta para teste (hipóteses herdadas, sem cotação atual)
| Item | Hipótese | Escopo inicial |
|---|---|---|
| Diagnóstico | R$ 1.200 | Uma unidade e até 3 sistemas; mapa de responsabilidades e lacunas |
| Implantação | R$ 3.900 | Até 8 horas técnicas; configuração, primeiro teste e aceite |
| Protect Essencial | R$ 2.190/mês | 1 ambiente homologado; até 500 GB de origem e 1,5 TB de repositório |
| Excedentes | Orçamento (referência R$ 350/h) | Aprovação prévia; volume, tráfego, licenças e deslocamento à parte |

- **Retenção inicial:** hipótese de 30 pontos diários, limitada à aplicação e ao espaço contratado. Pontos de restauração não equivalem à retenção legal.
- **Franquia de restauração:** 2 h/mês, não acumulável. Tarefas periódicas são obrigação da oferta e não consomem a franquia.

### 3.4 Implantação (estimativa de 10 dias úteis)
| Dias | Entrega |
|---|---|
| D1–2 | Inventário e acessos |
| D3–4 | Arquitetura e política |
| D5–6 | Configuração e primeira cópia |
| D7–8 | Teste isolado com usuário |
| D9 | Correções |
| D10 | Aceite e treinamento |

A cobrança recorrente começa na data contratada, depois dos critérios de ativação.

### 3.5 Rotina de serviço
- **Diária:** fila de alertas e cópias fora da janela.
- **Semanal:** falhas recorrentes, capacidade e pendências.
- **Mensal:** teste, relatório, horas e margem.
- **Trimestral:** recuperação crítica, acessos, fornecedor e escopo.
- **Incidente:** registrar, conter com autorização, comunicar o responsável, preservar evidência, recuperar em ambiente seguro e revisar a causa.

### 3.6 Para desenvolver
- [ ] Escolher e cotar o fornecedor de backup e o repositório
- [ ] Montar o laboratório e o runbook de restauração
- [ ] Modelo do relatório mensal de uma página, idealmente gerado a partir de logs
- [ ] Medir horas reais de monitoramento, testes, suporte e incidentes por cliente
- [ ] Definir RPO e RTO por sistema depois do teste. Primeira resposta e resolução são métricas distintas, e as metas de resposta só entram no contrato com escala confirmada
- [ ] Testar a substituição técnica: recuperar sem depender do titular

### 3.7 Métricas
Conversas qualificadas, diagnósticos pagos, propostas e contratos, horas por cliente, margem, testes com aceite e falhas recorrentes.

---

## 4. Herta Data

**Estágio:** diagnóstico ou projeto com escopo fechado

### 4.1 Proposta
Inventário de dados, mapa de fontes, qualidade, acesso e governança. É a ponte entre a proteção (Protect) e a interpretação (Insight).

### 4.2 Entregáveis a validar
Os documentos de origem só definem a linha; os entregáveis abaixo são sugestão.
- Inventário de sistemas e fontes, com responsável por cada um
- Mapa de fluxo de dados entre sistemas
- Matriz de acesso, indicando quem vê o quê
- Avaliação de qualidade das fontes que alimentarão indicadores
- Recomendações priorizadas, que servem de insumo para o Insight

### 4.3 Para desenvolver
- [ ] Template de inventário e de matriz de acesso
- [ ] Critérios de qualidade mínimos para uma fonte entrar no Insight
- [ ] Estimar horas por projeto antes de precificar

---

## 5. Herta Insight

**Estágio:** pilotos pagos (2 a 3 antes de padronizar) · **Sem preço validado**

### 5.1 Escopo do piloto
- Escolher **uma pergunta de negócio**: rentabilidade de clientes, inadimplência ou produtividade.
- Até **2 fontes autorizadas**, até **8 KPIs** e **1 painel executivo**.
- Dicionário de métricas, perfis de acesso, atualização pactuada e treinamento.

### 5.2 Aceite
- Conciliar uma amostra com a origem.
- Confirmar cada fórmula com o dono do indicador.
- Registrar a última atualização.
- Testar acesso e exportação.
- Medir o uso semanal e as decisões apoiadas.

### 5.3 Para desenvolver
- [ ] Escolher a ferramenta de painel e o padrão de integração
- [ ] Template do dicionário de métricas
- [ ] Estimar horas de implantação e gestão mensal antes de cotar
- [ ] Usar "tempo real" somente quando tecnicamente demonstrado

---

## 6. Herta Billing

**Estágio:** em piloto · **Público:** clínicas · **Prazo indicativo:** 20 a 28 semanas (levantamento, construção, automação, testes e piloto)

### 6.1 Proposta
Cobranças, recebimentos e indicadores em uma só visão. Cobrança por Pix integrada a um provedor de pagamentos, com o financeiro organizado.

### 6.2 Escopo corrigido (privacidade)
O documento anterior combinava cadastro de procedimentos com a intenção de não tratar dados clínicos. A revisão:
- **Não** copiar prontuário, procedimento ou plano clínico.
- Usar um identificador administrativo do orçamento e uma descrição neutra.
- Fazer avaliação de privacidade, porque até cobranças podem permitir inferências de saúde.

### 6.3 MVP
- Usuários e perfis
- Cadastro mínimo do pagador
- Parcelas
- Pix via gateway/provedor
- Status da cobrança
- Webhook idempotente
- Conciliação
- Painel de recebimentos (Recebido / A receber / Em atraso)
- Envio manual do link na primeira fase

### 6.4 Depois do MVP
Lembretes autorizados, cartão e boleto, renegociação e integrações.

### 6.5 Modelo financeiro
Dinheiro liquidado **diretamente para a clínica** via provedor, **sem custódia** pela HertaCloud. Validar quem recebe, como ocorre a liquidação, estornos, tarifas e suporte.

### 6.6 Proposta técnica inicial (a validar no levantamento)
```
Clinica (tenant)
 ├── Usuario ── Perfil
 ├── Pagador                       # cadastro mínimo, sem dado clínico
 └── Orcamento                     # identificador administrativo + descrição neutra
      └── Parcela
           └── Cobranca            # meio, valor, vencimento, status
                ├── EventoPagamento   # idempotente por id do provedor
                └── Conciliacao       # valor, tarifa, liquidação
```

### 6.7 Homologação obrigatória
- Evento duplicado e assinatura inválida
- Atraso de webhook
- Estorno e pagamento parcial
- Isolamento entre clínicas

### 6.8 Para desenvolver
- [ ] Decidir entre comprar/integrar e desenvolver, e revisar o prazo depois dessa decisão
- [ ] Contratar e homologar o provedor de pagamentos
- [ ] Orçar o projeto depois do levantamento e só iniciar com escopo assinado e recursos reservados
- [ ] Definir suporte, contrato e preço antes de trocar "piloto" por "disponível"
- [ ] Não prometer entrega completa em 90 dias nem redução de inadimplência sem evidência

---

## 7. Herta Gateway (novo)

**Estágio:** em breve / lista de interesse · **Origem:** pedido de 23/10/2026, fora dos documentos de 22/10

### 7.1 Problema
Cada meio de pagamento traz um provedor, um painel e um relatório diferentes. Os status ficam desencontrados entre sistema, provedor e banco. A conciliação é manual, e eventos duplicados ou estornos escapam do controle.

### 7.2 Posicionamento
Uma **camada de orquestração de pagamentos**: uma integração para cobrar por Pix, cartão, boleto e link, com eventos confiáveis e conciliação.
- **Sem custódia.** O valor é liquidado na conta do cliente por instituição de pagamento autorizada (PSP, adquirente ou banco). A HertaCloud não recebe nem repassa recursos.
- **Complementar ao Billing.** O Billing é a ferramenta de gestão para clínicas; o Gateway é a infraestrutura. Fica em aberto se o Billing passa a usar o Gateway internamente, o que evitaria duas integrações com provedores.

### 7.3 Público inicial (a validar)
Clínicas (via Billing), prestadores de serviço com cobrança recorrente, empresas de software (SaaS) e comércio com vendas online.

### 7.4 Fases propostas
| Fase | Escopo | Observação |
|---|---|---|
| **1 · MVP** | Pix (imediato e com vencimento), link de pagamento, API REST, webhooks, painel, conciliação e sandbox | Um provedor homologado |
| **2** | Cartão de crédito com tokenização/checkout do provedor, boleto, estornos e pagamentos parciais completos | Manter dados de cartão fora dos sistemas da HertaCloud |
| **3 · avaliar** | Multiprovedor com roteamento, recorrência/assinaturas, antifraude do provedor | **Split de pagamento exige análise regulatória própria** antes de entrar no escopo |

> O site hoje lista Pix, cartão, boleto e link como "recursos previstos para o lançamento". Se as fases acima forem adotadas, ajustar o site para refletir a fase 1.

### 7.5 Arquitetura proposta
```
Cliente (sistema / painel / link)
        │  HTTPS + chave de API + Idempotency-Key
        ▼
┌──────────────────────── Herta Gateway ────────────────────────┐
│ API pública ──► Serviço de cobranças ──► Adaptadores de provedor ─┼──► Provedor autorizado
│                     │                                          │        │
│                     ▼                                          │        │ webhooks do provedor
│             Ledger / conciliação ◄── Processador de eventos ◄──┼────────┘
│                     │                (normaliza, deduplica,    │
│                     ▼                 outbox)                  │
│                  Painel             Entrega de webhooks ───────┼──► Cliente
└────────────────────────────────────────────────────────────────┘
        Liquidação: provedor ──► conta bancária do cliente (sem passar pela HertaCloud)
```
- **Multi-tenant** com isolamento de dados, credenciais e chaves por cliente.
- **Outbox transacional** para que nenhum evento seja perdido entre o banco de dados e a entrega.
- **Adaptadores por provedor** para trocar ou somar provedores sem mudar a API pública.

### 7.6 Contrato de API (rascunho)
Os valores são sempre em centavos (inteiro) e a moeda é `BRL`.

| Método | Rota | Uso |
|---|---|---|
| `POST` | `/v1/cobrancas` | Cria cobrança (Pix, boleto ou cartão). Exige `Idempotency-Key` |
| `GET` | `/v1/cobrancas/{id}` | Consulta status |
| `POST` | `/v1/cobrancas/{id}/cancelamento` | Cancela uma cobrança pendente |
| `POST` | `/v1/cobrancas/{id}/estornos` | Estorno total ou parcial. Exige `Idempotency-Key` |
| `POST` | `/v1/links` | Cria link de pagamento |
| `GET` | `/v1/conciliacoes?data=AAAA-MM-DD` | Transações, tarifas e liquidações do dia |
| `POST` | `/v1/webhooks` | Cadastra endpoint de eventos |

**Estados da cobrança**
```
criada ─► pendente ─┬─► paga ─┬─► estornada_parcial ─► estornada
                    │         └─► estornada
                    ├─► vencida
                    └─► cancelada
```

**Eventos:** `cobranca.criada`, `cobranca.paga`, `cobranca.vencida`, `cobranca.cancelada`, `estorno.concluido`, `liquidacao.recebida`.

**Webhooks**
- Assinatura HMAC-SHA256 do corpo, com timestamp no cabeçalho e janela de tolerância contra replay.
- Entrega **pelo menos uma vez**: o cliente deduplica pelo `id` do evento.
- Reenvio com backoff exponencial e reprocessamento manual pelo painel.
- Pedidos idempotentes repetidos com a mesma chave devolvem a resposta original e não criam uma segunda cobrança.

### 7.7 Segurança e conformidade
| Tema | Proposta | Validar com |
|---|---|---|
| Enquadramento regulatório | Sem custódia e fora do fluxo de liquidação, para reduzir o risco de caracterização como instituição de pagamento | Jurídico (Lei 12.865/2013 e normas do Banco Central sobre arranjos e instituições de pagamento) |
| Pix | Acesso via PSP participante do Pix, nunca direto | Provedor contratado |
| Cartão (PCI DSS) | Tokenização ou checkout hospedado do provedor, sem armazenar, processar ou transmitir dados de cartão nos sistemas da HertaCloud | QSA / provedor |
| LGPD | Cliente como controlador dos dados dos pagadores e HertaCloud como operadora, com contrato de operador e mapa de suboperadores | Jurídico / privacidade |
| Segurança | MFA, menor privilégio, segregação por cliente, rotação de chaves, trilha de auditoria e teste de intrusão antes do lançamento | Responsável técnico |

### 7.8 Homologação
- Tudo da lista do Billing (duplicidade, assinatura inválida, atraso de webhook, estorno, parcial, isolamento)
- Replay de webhook, divergência de horário entre servidores e limite de requisições
- Indisponibilidade do provedor (fila e reprocessamento)
- Divergência na conciliação entre o ledger e o extrato do provedor
- Testes de ponta a ponta no sandbox do provedor

### 7.9 Modelo de receita (opções, sem valores)
Mensalidade por conta, tarifa por transação ou pacote com o Billing. As tarifas do provedor são sempre repassadas e exibidas de forma explícita. Precificar só depois de conhecer os custos reais do provedor e do suporte.

### 7.10 Critérios de lançamento
O selo "Em breve" só sai do site quando houver:
- [ ] Parecer jurídico e regulatório do modelo
- [ ] Provedor contratado e homologado, com sandbox funcionando
- [ ] Revisão de segurança e teste de intrusão concluídos
- [ ] Piloto com clientes da lista de interesse e conciliação sem divergência não explicada
- [ ] Suporte, SLA de resposta, contrato e preço definidos
- [ ] Documentação pública da API

### 7.11 Métricas
Inscrições na lista de interesse por segmento e volume, taxa de eventos entregues na primeira tentativa, latência de webhook, divergências de conciliação, conversão de links e tickets por conta.

---

## 8. Herta Action (radar)

**Proposta:** alertas e automações com logs e tratamento de exceções.
**Gatilho para iniciar:** fontes e regras de negócio estáveis, vindas do Protect, Insight ou Billing.
**Ideias iniciais (não validadas):**
- Alerta de backup fora da janela ou teste vencido (Protect)
- Aviso de parcela em atraso para a equipe da clínica (Billing)
- Alerta de KPI fora da faixa acordada (Insight)

Toda automação deve ter log, responsável, tratamento de exceção e forma de desligar.

---

## 9. Herta AI Analyst (radar)

**Proposta:** consulta e análise assistida sobre dados já preparados (Data e Insight).
**Gatilho para iniciar:** controles de acesso, teste de qualidade e revisão humana.
**Requisitos mínimos:**
- Responder só sobre dados governados, citando a fonte e a data de atualização
- Respeitar os perfis de acesso existentes
- Não usar dados sensíveis sem base legal e avaliação de privacidade
- Avaliação de qualidade das respostas antes de qualquer uso por cliente

---

## 10. Sequência sugerida

Não há datas comprometidas. A ordem depende de caixa, capacidade técnica e do que for validado.

| Etapa | Foco | Saída esperada |
|---|---|---|
| **0 · Formalização** | CNPJ, regime, NFS-e, conta, contratos e política de privacidade | Empresa apta a faturar |
| **1 · Protect** | Laboratório, fornecedor, runbook e primeiros diagnósticos | Meta de teste para 90 dias: 3 diagnósticos pagos e 1 a 3 contratos recorrentes |
| **2 · Data e Insight** | 2 a 3 pilotos pagos | Escopo padronizado e preço |
| **2 · Billing** | Levantamento, decisão comprar/integrar/desenvolver, piloto com 1 clínica | MVP homologado |
| **2–3 · Gateway** | Discovery, parecer regulatório, escolha de provedor, depois o MVP (fase 1) | Critérios de lançamento atendidos |
| **Radar** | Action e AI Analyst | Só depois que as bases estiverem estáveis |

---

## 11. Comunicação no site

O site (`index.html`) já reflete estes estágios. Ao mudar o estágio de um produto, atualizar os pontos listados.

| Produto | Selo no site | Onde aparece |
|---|---|---|
| Protect | Oferta principal | Card de soluções, seção `#protect`, FAQ |
| Data / Insight | Diagnóstico e projeto / Pilotos pagos | Cards de soluções |
| Billing | Em piloto | Card, seção `#billing`, comparativo, FAQ |
| Gateway | Em breve | Faixa de aviso, menu, card, seção `#gateway`, lista de interesse, FAQ, rodapé |
| Action / AI Analyst | No radar | Faixa "No radar" em soluções |

---

## 12. Decisões em aberto

- [ ] Validação jurídica da marca HertaCloud (INPI) e registro de domínio
- [ ] Município/UF, sede, composição societária e capital real
- [ ] Fornecedor de backup e cotação atualizada do Protect
- [ ] Billing: comprar/integrar ou desenvolver, provedor de pagamentos, preço e suporte
- [ ] Gateway: confirmar o nome do produto, o modelo sem custódia, as fases, o provedor, o parecer regulatório e a relação com o Billing
- [ ] Gateway: alinhar a lista de recursos do site com a fase 1 escolhida
- [ ] Canais de contato operacionais para o site (endpoint do formulário, e-mail, WhatsApp, Instagram)
- [ ] Vetor mestre oficial da logo Fluxo (o site usa uma vetorização do PNG aprovado)
