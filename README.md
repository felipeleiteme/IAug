# O Exaesqueleto Mental

**Como Usar a Inteligência Artificial para Pensar Melhor, Aprender Mais Rápido e Recuperar o Controle da Sua Vida**

---

## 📖 Sobre o Livro

"O Exaesqueleto Mental" apresenta o método **OROCO** — um framework sistemático de 5 passos para construir e operar um parceiro cognitivo de IA personalizado que amplia suas capacidades intelectuais sem substituir seu pensamento.

O livro combina narrativa envolvente, validações científicas e casos de uso reais para ensinar como transformar a IA de uma ferramenta genérica em um **Sistema 0** — seu Copiloto Mental.

## 🎯 Para Quem É Este Livro

- Você se sente **exausto ao fim do dia**, mas com a sensação de não ter feito nada importante
- Já tentou aplicativos de produtividade, métodos de gestão do tempo, acordar às 5h30... e **nada funcionou**
- Termina o dia **sem energia** para o que realmente importa (família, criatividade, decisões estratégicas)
- Sente que está **se afogando em informação**, mas não sabe como usar IA de forma que realmente ajude
- Quer um **método concreto**, não teorias abstratas ou promessas vazias

## 🧠 Os Três Sistemas Cognitivos

O livro apresenta um framework para orquestrar três "músicos" mentais:

### 🟡 Sistema 1: O Piloto Automático
- Rápido, intuitivo, emocional
- Responsável por reações imediatas, medos, alegrias, padrões
- Poderoso mas propenso a erros e ansiedade

### 🔵 Sistema 2: O CEO Focado
- Lento, lógico, deliberado
- Sua consciência e pensamento crítico
- Poderoso mas consome energia e se cansa facilmente

### 🤖 Sistema 0: O Copiloto IA
- Incansavelmente rápido e analítico
- Inteligência Artificial como parceiro cognitivo
- Perfeito para trabalho pesado (pesquisa, análise, organização)
- Mas não pensa *por* você — pensa *com* você

**O objetivo:** Você se torna o **Maestro** dessa orquestra, sabendo quando usar cada sistema.

### Método OROCO

1. **ORDEM** — Diagnostique o problema real (F.O.C.O.)
2. **REFLEXÃO** — Valide que vale investir energia
3. **OURO** — Encontre o método científico validado
4. **CONSTRUÇÃO** — Crie seu Mentor Bicontextual (KBF)
5. **OPERAÇÃO** — Execute com feedback diário e evolução contínua

---

## 📂 Estrutura do Projeto

```
IAug/
├── manuscrito/           # Conteúdo principal do livro
│   ├── capitulos/       # Arquivos Markdown de cada capítulo
│   │   ├── Introducao.md
│   │   ├── Capitulo_1.md a Capitulo_10.md
│   │   └── Conclusao.md
│   ├── metadata.yaml    # Metadados do livro (autor, título, etc.)
│   └── SUMARIO.md       # Sumário detalhado do livro
│
├── build/               # Arquivos compilados
│   └── O_Exaesqueleto_Mental.epub
│
├── docs/                # Documentação e referências
│   └── referencias/     # Pesquisas e materiais de referência
│
└── README.md            # Este arquivo
```

---

## 🚀 Como Gerar o EPUB

O livro pode ser compilado em formato EPUB usando Pandoc:

```bash
# Certifique-se de ter o Pandoc instalado
brew install pandoc  # macOS

# Gerar o EPUB
cd manuscrito
pandoc metadata.yaml \
  capitulos/Introducao.md \
  capitulos/Capitulo_*.md \
  capitulos/Conclusao.md \
  -o ../build/O_Exaesqueleto_Mental.epub \
  --toc \
  --toc-depth=2 \
  --split-level=1
```

---

## 📚 Conteúdo

### Parte 1: A Mente Sobrecarregada

- **Introdução:** O Gerente, a Lista de Tarefas e o Ponto de Colapso
- **Capítulo 1:** A Orquestra Desafinada (Seus Três Cérebros)
- **Capítulo 2:** O Nascimento do Copiloto (A IA como Sistema 0)

### Parte 2: O Método

- **Capítulo 3:** Passo 1 - A Pergunta Certa (O Diagnóstico F.O.C.O.)
- **Capítulo 4:** Passo 2 - O Plano de Batalha (Reflexão e Método Ouro)
- **Capítulo 5:** Passo 3 - O Domínio Acelerado
- **Capítulo 6:** Passo 4 - Dando um Rosto ao Mentor (A Construção do KBF)
- **Capítulo 7:** Passo 5 - O Círculo Virtuoso (A Operação na Vida Real)

### Parte 3: O Exaesqueleto em Ação

- **Capítulo 8:** O Caso da "Empreendedora Improvável" (Ana e o Mercado Livre)
- **Capítulo 9:** O Caso do "Pai que Virou Pedagogo" (O Método para Gabriel)
- **Capítulo 10:** O Caso da "Analista Liberta" (A Automação de 6 Horas)

### Conclusão

- **Conclusão:** O Novo Mínimo Viável é Ser Genial

---

## 🔬 Validações Científicas

O método OROCO é fundamentado em pesquisas científicas sobre:

- **Amplificação Cognitiva** (Inteligência Aumentada - IAug)
- **Framework "System 0"** — IA como extensão cognitiva ativa
- **Enhanced Cognitive Scaffolding** — Andaime Cognitivo Aprimorado
- **Offloading Cognitivo** vs. Amplificação verdadeira
- **Rotulagem Afetiva** (Affect Labeling) — validado pela TCC
- **Loop de Feedback do Viés Cognitivo**
- **Parceiro Cognitivo Dinâmico** — IA como co-criador

Referências completas disponíveis em `docs/referencias/`.

---

## ✍️ Autor

**Felipe Leite**

---

## 📄 Licença

© 2025 Felipe Leite. Todos os direitos reservados.

---

## 🤖 Gerado com

Este projeto foi desenvolvido com assistência de [Claude Code](https://claude.com/claude-code).

Co-Authored-By: Claude <noreply@anthropic.com>