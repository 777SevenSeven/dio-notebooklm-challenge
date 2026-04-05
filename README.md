# 🛡️ Guia de Estudo: Introdução à Cibersegurança Financeira

[![DIO](https://img.shields.io/badge/DIO-Bootcamp-0000FF?style=for-the-badge&logo=digitalocean&logoColor=white)](https://www.dio.me/)
[![NotebookLM](https://img.shields.io/badge/Google-NotebookLM-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://notebooklm.google.com/)

Este repositório contém o projeto prático desenvolvido para o desafio **DIO - CyberSegurança Riachuelo**. O objetivo é aplicar IA Generativa (Google NotebookLM) na curadoria e organização de conhecimento, criando um miniguia de estudo sobre um tema financeiro introdutório: **Os impactos financeiros da Cibersegurança e a proteção do Sistema Bancário**.

---

## 🎯 O Objetivo e o Contexto Financeiro

No ecossistema atual de varejo e tecnologia (como os serviços financeiros da Riachuelo), o dinheiro é digital. Portanto, a **segurança da informação é uma disciplina estritamente financeira**. 

O objetivo deste projeto é traduzir regulamentações complexas (como a Resolução nº 4.893 do Banco Central) e relatórios de ataques cibernéticos em um guia de estudo palatável. A meta é educar colaboradores e clientes sobre como as vulnerabilidades digitais se traduzem em perdas monetárias reais e como o sistema financeiro se protege.

## ⚠️ O Problema e as Consequências

**O Problema:** Existe uma barreira de conhecimento entre o setor de tecnologia (que entende de cibersegurança) e o usuário/colaborador comum (que movimenta o dinheiro).
**A Consequência:** Sem o letramento sobre ameaças digitais aplicadas a finanças, clientes caem em fraudes, e empresas de varejo sofrem com o vazamento de dados que geram multas milionárias e perda de confiança no mercado.

## ⚙️ A Metodologia (Como foi feito)

O projeto cumpriu todas as etapas exigidas pelo desafio da DIO, focando em aprendizagem ativa:

1. **Curadoria de Fontes:** Seleção de 3 a 5 fontes abertas detalhando o custo de violações de dados, normativas do Banco Central do Brasil e casos reais de ataques ao sistema financeiro.
2. **Definição de Objetivos:** Estruturação do escopo para garantir que a IA não desviasse do tom introdutório.
3. **Engenharia de Prompt:** Teste e validação de comandos no NotebookLM para extrair informações específicas, forçando a correlação entre falhas técnicas e impactos econômicos.
4. **Geração do Miniguia:** Criação automatizada de resumos estruturados, um glossário de conceitos mistos (Tech/Finanças) e perguntas estratégicas para revisão.

---

## 📦 Artefatos do Desafio

Os resultados do processamento pelo NotebookLM podem ser visualizados na estrutura abaixo:

### 1. Fontes Utilizadas (Grounding)
* *2025-Cybersecurity-Report-Vulnerability-and-Maturity-Challenges-to-Bridging-the-Gaps-in-Latin-America-and-the-Caribbean.pdf, 20250822_Cost-of-a-Data-Breach-Report-2025.pdf, Ataque-bilionario-ao-Sistema-Financeiro-tlp_clear.pdf, Exibe Normativo.pdf*

### 2. O Output Gerado (Miniguia de Estudo)
* *Olá! Como educador corporativo, preparei este miniguia de estudos especialmente para a nossa equipe do ecossistema de varejo e pagamentos. Em um cenário onde o varejo oferece cada vez mais serviços financeiros (como concessão de crédito, carteiras digitais e pagamentos instantâneos), a intersecção entre a nossa operação e as ciberameaças exige máxima atenção.

Vamos explorar como a segurança financeira e cibernética sustenta a confiança dos nossos clientes e a continuidade dos nossos negócios.

***

### 🎯 Objetivos de Estudo
Ao final deste miniguia, você será capaz de:
1. **Compreender o impacto financeiro e operacional global** dos ataques cibernéticos, especialmente as ameaças que exploram a cadeia de suprimentos e as novas tecnologias de IA.
2. **Entender a dinâmica de um ciberataque no Sistema Financeiro Nacional** (como fraudes envolvendo o Pix) e as vulnerabilidades associadas a terceiros e prestadores de serviços.
3. **Reconhecer as diretrizes regulatórias do Banco Central (Bacen)** que exigem controles rígidos de segurança, planos de resposta a incidentes e proteção de dados para proteger os meios de pagamento.

***

### 📊 Resumo Estruturado: Impactos Financeiros e Resoluções do Bacen

**O Custo e o Impacto das Violações de Dados**
No cenário global, as violações de dados causam impactos estrondosos: o custo médio global de uma violação é de US$ 4,44 milhões. No ecossistema de varejo e pagamentos, a interrupção das operações é uma realidade dura, afetando 86% das organizações que sofrem violações. Vetores de ataque como *Phishing* e comprometimento da cadeia de suprimentos (fornecedores terceirizados) estão entre os mais comuns e custosos. Além disso, o uso da Inteligência Artificial por cibercriminosos para criar campanhas de manipulação mais convincentes já está presente em 16% das violações.

**Ameaças Reais ao Sistema de Pagamentos (O Caso Pix)**
No Brasil, a dependência de fornecedores de tecnologia terceirizados exige cautela. Recentemente, um ciberataque histórico atingiu uma provedora de infraestrutura (C&M Software), que funciona como uma ponte para o Sistema de Pagamentos Brasileiro. Invasores possivelmente usaram credenciais vazadas e exploraram esse acesso para desviar quantias bilionárias (estimadas entre R$ 400 milhões e R$ 3 bilhões) das "contas reservas" de várias instituições via Pix. Para conter a sangria, o Banco Central precisou desconectar a empresa afetada, interrompendo as operações de Pix de quase 300 instituições temporariamente. Isso ilustra como o comprometimento de um único fornecedor pode paralisar as operações financeiras de todo um ecossistema.

**As Regras do Jogo: Resolução CMN nº 4.893**
Para blindar o sistema financeiro contra esses cenários, o Banco Central exige rigor absoluto através da Resolução CMN nº 4.893. Toda instituição deve manter uma política de segurança cibernética compatível com o seu porte e com a sensibilidade dos dados de seus clientes. A resolução obriga a adoção de planos de resposta a incidentes e estabelece regras rígidas para a contratação de serviços de processamento em nuvem. De forma bem específica para a nossa realidade de pagamentos, a norma exige o uso de múltiplos fatores de autenticação (MFA) para acessos administrativos aos ambientes críticos do Pix e o isolamento físico e lógico desses sistemas.

***

### 📖 Glossário de Conceitos

**1. PSTI (Provedor de Serviços de Tecnologia da Informação):** São empresas terceirizadas, autorizadas pelo Banco Central, que fornecem infraestrutura e sistemas (como acesso ao Pix e *core* bancário) para instituições financeiras. Elas funcionam como "portas de entrada" para a rede do sistema financeiro.

**2. Shadow AI (IA Sombra):** Refere-se ao uso de ferramentas ou modelos de Inteligência Artificial por colaboradores sem a aprovação ou supervisão da equipe de segurança da empresa. Esse uso invisível aumenta drasticamente os custos e os riscos de vazamento de dados sensíveis dos clientes. 

**3. Phishing:** Uma tática criminosa, frequentemente o vetor inicial de invasões, em que golpistas tentam manipular os usuários (por e-mail ou mensagens falsas) para que entreguem suas senhas e credenciais de acesso.

**4. Contas Reserva:** São contas mantidas pelas instituições financeiras diretamente no Banco Central. O saldo nelas contido serve como lastro e é utilizado exclusivamente para a liquidação interbancária (o "acerto de contas" entre os bancos ao final de transações como o Pix).

**5. Sistema de Pagamentos Brasileiro (SPB):** É a grande engrenagem do Banco Central que permite que o dinheiro mude de mãos no Brasil com segurança. Envolve regras, infraestruturas e sistemas responsáveis por processar desde TEDs e liquidação de boletos até o moderno Pix.

***

### 🧠 Perguntas Estratégicas
Vamos testar o que aprendemos? *(Respostas no final)*

**1. No ecossistema de segurança cibernética, qual foi a tática de ataque inicial mais comum que criminosos utilizaram (muitas vezes aprimorada por IA) para comprometer sistemas corporativos globais?**
a) Invasão física aos data centers.
b) Phishing e roubo de credenciais.
c) Queda de energia e falhas de hardware.

**2. Para mitigar fraudes e proteger as transações instantâneas, o que a Resolução CMN nº 4.893 do Banco Central exige para os acessos administrativos de ambientes críticos como o Pix?**
a) Apenas que os administradores usem senhas com mais de 8 caracteres.
b) O uso obrigatório de múltiplos fatores de autenticação (MFA).
c) Que as transferências ocorram exclusivamente durante o horário comercial.

**3. O que nos ensina o grande ataque ao Sistema Financeiro Brasileiro ocorrido em junho de 2025 sobre a cadeia de pagamentos?**
a) Que o ataque mirou os celulares dos clientes finais do varejo, roubando o saldo de suas contas corrente.
b) Que o sistema financeiro é imune a ataques se a instituição tiver um bom antivírus.
c) Que criminosos podem focar em fornecedores terceirizados de infraestrutura (PSTIs) para burlar as defesas dos bancos e desviar recursos direto das contas reserva.

***

### 💡 Prompts Reutilizáveis
Se você quiser usar o **NotebookLM** para continuar estudando os documentos desta base e aprofundar seu conhecimento na nossa realidade, copie e cole estes prompts:

1. *"Aja como um auditor de conformidade do Bacen. Detalhe quais são as regras, procedimentos e controles específicos que a Resolução 4.893 exige das instituições ao contratarem serviços de computação em nuvem."*
2. *"Resuma os fatores que mais aumentam e os que mais reduzem o custo de uma violação de dados globalmente, focando no papel da automação de segurança e da Inteligência Artificial Sombra (Shadow AI)."*

***
*(Gabarito: 1-B; 2-B; 3-C)**

### 3. Prompts Reutilizáveis para Estudo Futuro
Para continuar explorando o tema no NotebookLM, o projeto gerou os seguintes prompts:
* *"Aja como um auditor de conformidade do Bacen. Detalhe quais são as regras, procedimentos e controles específicos que a Resolução 4.893 exige das instituições ao contratarem serviços de computação em nuvem.""*
* *"Resuma os fatores que mais aumentam e os que mais reduzem o custo de uma violação de dados globalmente, focando no papel da automação de segurança e da Inteligência Artificial Sombra (Shadow AI)"*
