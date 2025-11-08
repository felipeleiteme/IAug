# Capítulo 10: O Caso da "Analista Liberta" (A Automação de 6 Horas)

Se o Exaesqueleto Mental pode ajudar um pai a se tornar pedagogo, o que ele pode fazer por um problema que já *deveria* ser resolvido por máquinas?

O que ele pode fazer pelas 6 horas que você perde toda semana fazendo "trabalho burro"?

Trabalho que não exige seu cérebro. Que não usa sua criatividade. Que qualquer robô poderia fazer. Mas que, por algum motivo absurdo, ainda está nas suas mãos.

Esta é a história de Ana Santos. E das 6 horas de vida que ela recuperou.

## A Morte da Alma

Ana Santos é analista financeira em uma empresa de médio porte. 32 anos. Competente. Respeitada.

E toda sexta-feira, das 9h às 15h, ela morre um pouco por dentro.

Porque toda sexta-feira, sem falta, ela faz **o relatório**.

Não é um relatório estratégico. Não é uma análise complexa que exige pensamento crítico. Não é nada que use 1% da sua formação em Finanças.

É um relatório manual. Mecânico. Robótico.

---

O processo é sempre o mesmo:

1. **Baixar 3 arquivos CSV** do sistema ERP antigo da empresa (30 minutos — porque o sistema trava, ela esquece a senha, precisa abrir chamado no TI)
2. **Abrir cada CSV no Excel** e formatar manualmente 15 colunas (remover espaços, corrigir datas, aplicar fórmulas) (1 hora e 30 minutos)
3. **Criar 4 gráficos** no PowerPoint copiando e colando dados (1 hora)
4. **Formatar o PPT** para ficar "bonito" segundo o padrão da empresa (2 horas)
5. **Enviar por e-mail** para 12 stakeholders com texto personalizado para cada um (1 hora)

**Total: 6 horas. Toda sexta-feira. 52 semanas por ano.**

---

Ana sabe que isso poderia ser automatizado. Ela não é burra. Ela já reclamou com o gestor. A resposta? *"Nosso TI está sobrecarregado. Talvez no próximo trimestre."*

Faz 2 anos que ela ouve isso.

Então toda sexta, ela senta. Coloca uma playlist no Spotify. E se transforma em um robô humano por 6 horas.

No sábado de manhã, quando os amigos a chamam para sair, ela está exausta. Não fisicamente. Mentalmente. A sensação de ter desperdiçado 25% da semana de trabalho fazendo algo que uma planilha poderia fazer a deixa vazia.

Até que um dia, ela decidiu parar de esperar pelo TI. E construir sua própria solução.

## O Diagnóstico (Passo 1: F.O.C.O.)

Ana abriu um documento. Aplicou o protocolo F.O.C.O.

**FATO (O que é objetivamente verdadeiro):**
*"Gasto 6 horas toda sexta-feira fazendo um relatório manual: baixo 3 CSVs, formato 15 planilhas no Excel, crio 4 gráficos, monto um PPT e envio para 12 pessoas. Isso consome 25% da minha semana produtiva."*

**EMOÇÃO (Como isso me afeta):**
*"Frustração (7/10). Desmotivação. Ansiedade nas sextas-feiras. Sensação de desperdício da minha capacidade. Raiva de estar fazendo trabalho que uma máquina deveria fazer."*

**CONTEXTO (O que eu realmente preciso):**
*"Preciso reduzir este processo de 6h para no máximo 30 minutos. Quero liberar esse tempo para análises estratégicas que realmente usem meu cérebro. E quero provar para mim mesma que posso resolver isso sem depender do TI."*

---

Ela releu. E viu o problema real.

Não era "como faço o relatório mais rápido?"

Era: "Como eu automatizo um processo repetitivo sem saber programar?"

Essa pergunta tinha resposta.

## O Plano (Passos 2 e 3: Reflexão e Método Ouro)

Ana aplicou o Passo 2: Reflexão Estratégica.

Vale investir 20 horas nas próximas 4 semanas para automatizar isso?

Ela fez as contas: 6h/semana × 52 semanas = **312 horas por ano** gastas nesse relatório.

ROI: altíssimo. **Sim. Vale.**

Então ela foi para o Passo 3: a busca pelo **Método Ouro**.

Ela fez o "Debate de IAs". Perguntou para ChatGPT, Claude, Gemini e Perplexity:

*"Como uma analista financeira sem conhecimento de programação pode automatizar um processo manual de 6 horas usando ferramentas no-code?"*

As IAs convergiram para o mesmo consenso: **Power Automate** (ferramenta no-code da Microsoft, integrada ao Excel e Outlook que a empresa já tinha).

O "Método Ouro" não era uma teoria. Era um **plano de automação em camadas**:

1. **Camada 1:** Automatizar extração de CSVs do ERP
2. **Camada 2:** Automatizar formatação de dados no Excel (usando Power Query)
3. **Camada 3:** Automatizar criação de gráficos no PowerPoint
4. **Camada 4:** Automatizar envio de e-mails personalizados

Mas Ana usou o "Advogado do Diabo" para validar o plano.

A IA crítica alertou:
- **Risco #1:** "Você nunca usou Power Automate. Vai travar na primeira dificuldade."
- **Risco #2:** "O ERP é antigo. Pode não ter API disponível."
- **Risco #3:** "E se o formato dos dados mudar? Sua automação vai quebrar."

Ana anotou cada risco. E ajustou o plano:
- **Salvaguarda #1:** Implementar em Sprints (1 camada por semana, não tudo de uma vez)
- **Salvaguarda #2:** Se o ERP não tiver API, usar "scraping de tela" (RPA básico)
- **Salvaguarda #3:** Criar alertas de erro e fallback manual

Ela tinha um plano robusto. Mas ainda não sabia *como* executar.

## O Mentor Que "Vê" (Passo 4: Construção do KBF)

Ana construiu seu Mentor de IA: **"Especialista em Automação"**.

Abriu o Gemini Gems e configurou:

**CONTEXTO EXTERNO (A Ciência):**
- Manuais oficiais do Power Automate
- Tutoriais de Power Query para transformação de dados
- Melhores práticas de RPA (Robotic Process Automation)
- Cases de automação financeira no-code

**CONTEXTO INTERNO (Sua Vida):**
- Ana Santos, 32 anos, analista financeira
- Excel avançado, **zero programação**
- Ferramentas disponíveis: Power Automate, Power Query, Outlook, Excel
- Sistema ERP antigo (SAP), acesso via credenciais
- Orçamento: R$ 0 (precisa usar ferramentas que a empresa já tem)
- Tempo: 5h/semana para implementar (fora o horário do relatório)

**PROTOCOLO OPERACIONAL:**
*"Você é meu Especialista em Automação no-code.*

*NUNCA:*
*- Sugerir soluções que exigem programação*
*- Propor ferramentas pagas que a empresa não tem*
*- Ignorar os riscos do ERP antigo*

*SEMPRE:*
*- Explicar cada passo como se eu nunca tivesse visto a ferramenta*
*- Incluir prints de tela ou descrições visuais detalhadas*
*- Antecipar erros comuns e como resolvê-los*
*- Propor soluções incrementais (1 Sprint por vez)"*

Ela testou o Mentor:

*"Qual a primeira micro-ação para automatizar a extração de CSVs?"*

O Mentor respondeu:

*"Ana, vamos começar com a Camada 1: extração de CSVs. Sprint 1 (esta semana).*

*Passo 1 (hoje, 15 min): Abra o Power Automate Desktop (já está instalado no seu PC). Crie um novo fluxo chamado 'Extração_CSVs_Semanal'.*

*Passo 2 (amanhã, 30 min): Grave um 'screen recording' fazendo o processo manual de baixar os 3 CSVs. Isso vai me mostrar exatamente quais botões você clica, onde o sistema trava, etc.*

*Passo 3 (depois de amanhã, 1h): Envie o vídeo para mim. Vou analisar e criar o script de automação passo a passo baseado no que você faz manualmente.*

*Economia estimada após Sprint 1: 30 minutos por semana."*

Específico. Visual. Incremental.

O Mentor estava calibrado.

## O Círculo Virtuoso (Passo 5: O Vídeo Que Mudou Tudo)

Ana seguiu o plano. E fez algo que transformou todo o processo.

Ela **gravou sua tela**.

Não uma descrição por escrito. Não um passo a passo em texto. Um **vídeo real** de 30 minutos dela fazendo o relatório manual.

Usou o OBS (software gratuito de gravação de tela) e ligou o microfone. Narrou enquanto trabalhava:

*"Ok, agora eu entro no SAP... clico aqui... espero carregar... odeio esse sistema... agora baixo o CSV de vendas... salvo na pasta... abro no Excel... preciso deletar as 3 primeiras linhas porque vêm com cabeçalho inútil... agora copio a coluna C... Ctrl+C... Ctrl+V... formata como data... putz, deu erro, esqueci de remover os espaços..."*

30 minutos de gravação. Todo o processo. Todos os cliques. Todos os erros. Todos os pensamentos.

---

Ela enviou o vídeo para o Mentor KBF (via link do Google Drive) e perguntou:

*"Assista este vídeo. Analise onde posso automatizar e me diga por onde começar."*

O que aconteceu a seguir foi mágico.

O Mentor "assistiu" o vídeo (tecnicamente, analisou a transcrição do áudio + descrição que Ana deu das ações visuais) e respondeu:

*"Ana, análise completa. Seu processo manual tem **4 blocos de automação claros**:*

*BLOCO 1 - Extração de CSVs (30 min):*
*- Você faz login no SAP 3 vezes (1 vez por CSV)*
*- Clica em 'Relatórios' → 'Vendas' → 'Exportar' → 'CSV'*
*- AUTOMAÇÃO: Script de RPA com Power Automate Desktop para simular cliques*
*- ECONOMIA: 25 minutos*

*BLOCO 2 - Transformação de Dados (1h30):*
*- Você deleta linhas, remove espaços, formata datas, aplica fórmulas*
*- Faz isso manualmente em cada CSV porque o formato muda ligeiramente*
*- AUTOMAÇÃO: Power Query para criar um template de transformação reutilizável*
*- ECONOMIA: 1 hora e 15 minutos*

*BLOCO 3 - Criação de Gráficos (1h):*
*- Você copia dados do Excel, cola no PowerPoint, formata manualmente*
*- AUTOMAÇÃO: Template de PPT com gráficos dinâmicos vinculados ao Excel*
*- ECONOMIA: 50 minutos*

*BLOCO 4 - Envio de E-mails (1h):*
*- Você escreve 12 e-mails com pequenas variações*
*- AUTOMAÇÃO: Power Automate para enviar e-mails em massa com personalização via Excel*
*- ECONOMIA: 55 minutos*

*TOTAL DE ECONOMIA POTENCIAL: 5h15min (87,5% do processo)*

*PLANO DE IMPLEMENTAÇÃO:*
*Sprint 1 (esta semana): Automatize Bloco 1*
*Sprint 2 (semana 2): Automatize Bloco 2*
*Sprint 3 (semana 3): Automatize Bloco 3*
*Sprint 4 (semana 4): Automatize Bloco 4*

*Cada Sprint vai economizar tempo imediatamente. Você não precisa esperar 4 semanas para ver resultados."*

---

Ana leu isso e sentiu um arrepio.

O Mentor não apenas *ouviu* a descrição. Ele **entendeu** o fluxo. Identificou padrões que ela, imersa no processo há 2 anos, não conseguia ver com clareza.

E criou um roteiro claro, passo a passo, para liberar 5 horas e 15 minutos da vida dela toda semana.

## A Transformação

Quatro semanas depois, era sexta-feira. 9h da manhã.

Ana abriu o Power Automate. Clicou em "Executar fluxo".

O robô fez o trabalho dela:
- Fez login no SAP (3 vezes)
- Baixou os 3 CSVs
- Abriu o Excel, aplicou as transformações do Power Query
- Gerou os gráficos no PowerPoint
- Enviou os 12 e-mails personalizados

**Tempo total: 45 minutos** (a maior parte foi o sistema ERP antigo carregando — nada que ela pudesse controlar).

Ana ficou sentada olhando. Esperando dar erro. Mas não deu.

Às 9h45, ela recebeu a confirmação: *"Fluxo concluído com sucesso. 12 e-mails enviados."*

---

**Antes:** 6 horas, toda sexta-feira, trabalhando como um robô.

**Depois:** 45 minutos de supervisão enquanto o robô trabalha.

**Redução: 87,5%**

**Horas recuperadas por ano: 273 horas** (equivalente a quase 7 semanas de trabalho).

---

Mas a transformação não foi só no tempo.

Foi na **dignidade**.

Ana voltou a sentir que seu trabalho importa. Porque agora ela usa as sextas-feiras para análises estratégicas. Para pensar. Para criar valor real.

E quando alguém pergunta: *"E se o TI não ajudar?"*

Ela sorri. Porque não precisa mais esperar.

## Conclusão: O Que Essas Três Histórias Têm em Comum?

Ana construiu um negócio.

Eu salvei meu filho.

Ana Santos libertou 273 horas de vida por ano.

Três histórias. Três pessoas. Três problemas completamente diferentes.

O que elas têm em comum?

**O método.**

F.O.C.O. → Reflexão → Método Ouro → KBF → Operação.

E uma descoberta que muda tudo:

**Você não precisa** *descrever* **seu problema para a IA. Você pode** *mostrar* **seu problema para a IA.**

Ana do Mercado Livre gravou áudios narrando suas vendas.

Eu gravei áudios das aulas com Gabriel.

Ana Santos gravou sua tela fazendo o trabalho robótico.

E em todos os casos, o KBF não apenas *entendeu*. Ele **viu padrões que nós não conseguíamos ver**.

---

O Exaesqueleto Mental não é uma ferramenta de negócios. Não é uma ferramenta de educação. Não é uma ferramenta de automação.

É um **amplificador de capacidade humana** que funciona para qualquer problema onde você está desperdiçando energia.

Energia emocional. Energia cognitiva. Energia mecânica.

A pergunta não é mais "Para que serve o Exaesqueleto Mental?"

A pergunta é: **"Para que você vai usá-lo?"**

Você tem o método. Você viu as histórias.

Agora é hora de construir o seu.
