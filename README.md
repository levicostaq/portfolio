# 💼 Portfólio — Levi Costa

Desenvolvo soluções para empresas que precisam organizar processos, reduzir trabalho manual e transformar informações dispersas em ferramentas úteis para a gestão. Já atendi clínicas, escritórios de advocacia, empresas do setor automotivo, organizações de eventos e empresas juniores.

Esta é a vitrine desses trabalhos. O código-fonte é privado por envolver dados e regras de negócio de clientes — aqui documento o problema, a solução e o resultado de cada projeto.

Projetos com código aberto estão nos [meus repositórios](https://github.com/levicostaq?tab=repositories).

📫 [LinkedIn](https://linkedin.com/in/levicostaq) · [Voltar ao perfil](https://github.com/levicostaq)

📄 [Baixar portfólio em PDF](Portfolio-Levi-Costa.pdf)

---

## 🎯 Torre de Controle

**Plataforma de gestão empresarial — conceito próprio, com quatro implementações**

Ao trabalhar com organizações diferentes, percebi um problema recorrente: informações importantes espalhadas entre planilhas, documentos, mensagens e anotações, sem ninguém conseguindo enxergar o quadro completo. A Torre de Controle é a resposta que desenvolvi para isso — uma estrutura-base de plataforma de gestão que centraliza metas, indicadores, resultados financeiros, projetos, desempenho de equipes, parcerias e planejamento estratégico, adaptada ao funcionamento de cada organização atendida.

### Implementações

| Cliente | Segmento | Foco da implementação |
|---|---|---|
| **Unijus** | Empresa Júnior de Direito (UNIFOR) | Diretorias, metas, parcerias, resultados e desenvolvimento institucional |
| **Proativa** | Empresa Júnior de Eng. de Produção (UNIFOR) | Acompanhamento estratégico e operacional — projeto colaborativo com a Unijus |
| **APSV Advogados** | Escritório de advocacia | Gestão jurídica em kanban por área de atuação e metas financeiras |
| **MC Bares e Eventos** | Setor de eventos | Receita mensal, eventos realizados, parceiros, desempenho comercial e NPS |

**Resultado:** quatro implementações entregues, cada uma adaptada ao funcionamento e aos indicadores da organização atendida.

### Stack

`React` · `TypeScript` · `Supabase` · `Lovable` · `Recharts`

### Telas — implementação Unijus

> Os dados exibidos são fictícios, usados para demonstração.

**Visão Geral — termômetro de resultado**
![Visão Geral da Torre de Controle](assets/torre-visao-geral.png)

**Metas da Rede — jornada de crescimento e projetos de impacto do PE 2025-2027**
![Metas da Rede](assets/torre-metas-rede.png)

**Deep Dive por Diretoria — KPIs por área, com NPS, ticket médio e taxa de conversão**
![Deep Dive por Diretoria](assets/torre-diretorias.png)

---

## 🏥 Automação para clínica de oftalmologia

**Atendimento inteligente no WhatsApp e prontuário eletrônico cirúrgico**

A clínica dependia das secretárias para responder manualmente cada dúvida e pedido de agendamento pelo WhatsApp. Desenvolvi um agente de atendimento conectado ao WhatsApp que conversa com pacientes, responde dúvidas frequentes, realiza agendamentos, coleta informações e encaminha para a equipe quando o caso exige atendimento humano.

Também desenvolvi um prontuário eletrônico estruturado em quatro etapas do fluxo cirúrgico: dados pessoais, pré-operatório, intraoperatório e pós-operatório.

**Resultado:** a automação passou a realizar de 3 a 9 agendamentos por dia sem nenhuma intervenção manual, reduzindo o trabalho repetitivo e otimizando o tempo das secretárias do consultório.

### Stack

`n8n` · `Evolution API` · `Supabase` · `IA generativa`

> 🚧 Prints e diagrama do fluxo em breve.

---

## ⚖️ Automação comercial — Escritório Eveline Milfont

**Do anúncio ao follow-up: atendimento e gestão de leads automatizados**

Leads vindos do Facebook Ads esfriavam antes de receber a primeira resposta, e não havia um lugar único para acompanhar quem já tinha sido atendido. Construí o processo comercial de ponta a ponta:

- **Captação** — automação que dispara o atendimento no instante em que o lead entra em contato, usando a API oficial da Meta para conectar o WhatsApp ao fluxo
- **Atendimento** — bot que faz o primeiro contato, conduz a conversa, auxilia no agendamento de reuniões e executa follow-up automático
- **Gestão** — funil estruturado no Pipedrive, com etapas definidas e automações internas para organizar os leads e centralizar o histórico de atendimento

**Resultado:** primeira resposta muito mais rápida, atendimento contínuo e organizado, e redução das chances de potenciais clientes serem esquecidos.

### Stack

`n8n` · `API oficial da Meta` · `WhatsApp Business` · `Pipedrive`

---

## 🚗 Uchoautos — site de vendas com gestão de estoque

**Vitrine digital com painel administrativo autônomo**

Desenvolvi o site institucional da empresa com catálogo dos automóveis disponíveis e um painel administrativo para que a própria equipe gerencie o estoque: cadastrar veículos, alterar informações, atualizar imagens e remover os já vendidos.

**Resultado:** a Uchoautos passou a contar com uma vitrine digital própria e autonomia total para manter o catálogo atualizado, sem depender de suporte técnico.

### Stack

`Lovable` · `Banco de dados` · `Desenvolvimento web` · `Integração com WhatsApp`

---

## 🚀 Autolink

Cofundei a Autolink, uma iniciativa de automação comercial e qualificação de leads. Alguns dos projetos listados acima nasceram dela — é onde prospecto, converso com o cliente para entender o processo e entrego a solução do início ao fim.

`Automação de processos` · `WhatsApp` · `CRM` · `Qualificação de leads`

---

## 🎓 Projetos acadêmicos e de extensão

### GAC — Gestão de Ativos do CCT

Plataforma para digitalizar o controle de empréstimo de projetores e chaves na UNIFOR. Em equipe de quatro, atuei na engenharia de requisitos e no protótipo: conduzimos entrevistas com professores, coordenação e responsáveis, estruturamos as regras de negócio e priorizamos funcionalidades com MoSCoW, produzindo casos de uso, diagramas de classes e de sequência e requisitos funcionais e não funcionais.

`React` · `UML` · `Engenharia de requisitos` · `MoSCoW` · `NFC` · `QR Code`

### Shuffle Six

Jogo educativo de raciocínio lógico apresentado a crianças de 7 a 9 anos do Colégio Yolanda de Queiroz, em projeto de extensão da UNIFOR. O jogo mostra um número-alvo e oferece números e operadores embaralhados — o desafio é montar uma operação que chegue ao resultado.

`Godot Engine`

---

## 🛠️ Como eu trabalho

1. **Entendimento do contexto** — converso com o cliente e com os usuários para compreender como o processo funciona hoje e onde estão as dificuldades reais.
2. **Transformação do problema em solução** — organizo o que foi levantado e defino como vira funcionalidade, indicador, automação ou fluxo.
3. **Desenvolvimento e validação** — construo uma primeira versão funcional, apresento e ajusto conforme o feedback.
4. **Entrega de autonomia** — sempre que possível, entrego soluções que o próprio cliente administra, reduzindo a dependência de suporte técnico.

---

<sub>Interessado em detalhes técnicos de algum destes projetos? É só chamar no <a href="https://linkedin.com/in/levicostaq">LinkedIn</a>.</sub>
