# Technical Writing Skills

Skills para ajudar assistentes de IA a criar e revisar documentação técnica com linguagem simples, clara e consistente — em inglês e em português brasileiro.

O objetivo é tornar instruções, procedimentos e informações técnicas mais fáceis de entender, sem perder precisão nem inventar comportamentos ou requisitos.

## Skills disponíveis

### ASD-STE100 — Simplified Technical English

**Pasta:** `asd-ste100-english/`

Ajuda a escrever, simplificar e revisar conteúdo técnico em inglês, seguindo princípios associados ao Simplified Technical English (STE): vocabulário controlado, frases diretas, ações explícitas e terminologia consistente.

A referência oficial identificada para esta skill é a **ASD-STE100 Issue 9, de 15 de janeiro de 2025**. Consulte o [site oficial da ASD-STE100](https://www.asd-ste100.org/) para obter o padrão e o dicionário oficiais.

> Esta skill é um guia prático de escrita. Ela não reproduz o padrão completo nem seu dicionário. Não declare conformidade total com a ASD-STE100 sem verificar as regras e o dicionário oficiais aplicáveis.

### Português Brasileiro — Linguagem Técnica Controlada

**Pasta:** `pt-br-controlled-language/`

Adapta princípios de clareza, consistência e redução de ambiguidades ao português brasileiro. Ajuda a produzir documentação de sistemas, instruções para usuários, requisitos, critérios de aceite, mensagens de interface, tickets e comunicados técnicos.

Esta adaptação usa **Português Técnico Controlado (PTC)** como uma convenção editorial proposta neste projeto. Ela **não é uma tradução oficial da ASD-STE100**, não reproduz suas regras específicas de inglês e não certifica conformidade com esse padrão.

## O que as skills ajudam a produzir

- Documentação técnica, manuais e tutoriais.
- Procedimentos e instruções passo a passo.
- Textos de ajuda, mensagens de erro e avisos de interface.
- Requisitos de software, tarefas de desenvolvimento e critérios de aceite.
- Notas de versão, comunicados e conteúdo de suporte.
- Revisões que eliminam ambiguidades, redundâncias e linguagem burocrática.

## Princípios de escrita

As skills orientam o assistente a:

- Preferir palavras claras e frases diretas.
- Descrever ações, condições e resultados de forma explícita.
- Manter os mesmos termos para os mesmos conceitos.
- Preservar nomes de telas, campos, rotas, APIs, arquivos, comandos e outros identificadores técnicos.
- Manter fatos, limites, pré-requisitos, avisos e exceções.
- Não inventar causas, comportamentos, requisitos nem resultados que a fonte não confirme.
- Revisar a clareza e a precisão antes de entregar o texto.

## Como usar

1. Escolha a skill conforme o idioma do conteúdo.
2. Copie a pasta correspondente para o local de skills ou instruções utilizado pelo seu assistente de IA.
3. Configure ou habilite a skill conforme as instruções da ferramenta utilizada.
4. Peça ao assistente para criar, revisar ou simplificar o conteúdo usando a skill escolhida.

A forma de instalação varia conforme a ferramenta. A presença de um arquivo `SKILL.md`, por si só, não garante compatibilidade automática com todos os assistentes.

## Exemplo

**Antes**

> Para que seja possível efetuar a alteração desejada, deverá ser realizada a seleção do registro correspondente e, posteriormente, deverá ser acionado o recurso de gravação.

**Depois**

> Abra o cadastro. Selecione o registro que deseja alterar. Edite os campos necessários e clique em **Salvar**.

O exemplo demonstra o estilo esperado. Em documentação real, mantenha os nomes exatos exibidos pelo sistema.

## Precisão e revisão humana

As skills ajudam a melhorar a escrita, mas não substituem a revisão de alguém que conheça o assunto. Verifique os fatos, os requisitos, as instruções operacionais e os avisos importantes antes de publicar ou usar a documentação.

No caso do inglês, linguagem simples não significa conformidade automática com a ASD-STE100. Para confirmar a conformidade, consulte a edição e o dicionário oficiais.

## Contribuições

Sugestões e contribuições são bem-vindas. Ao propor uma mudança, explique o problema que ela resolve e, quando possível, inclua um exemplo antes/depois. Preserve a distinção entre o padrão oficial em inglês e a adaptação para português brasileiro.

## Referências

- [ASD-STE100 — site oficial](https://www.asd-ste100.org/)
- [ASD-STE100 — downloads e solicitação do padrão oficial](https://www.asd-ste100.org/STE_downloads.html)

---

## English summary

This repository provides two AI writing skills for clearer, more consistent technical communication:

- **`asd-ste100-english/`** — a practical skill inspired by ASD-STE100 Simplified Technical English principles. It does not replace the official standard or dictionary and does not guarantee compliance.
- **`pt-br-controlled-language/`** — an adaptation of clear and controlled technical-writing principles for Brazilian Portuguese. It is not an official Portuguese version of ASD-STE100.

The skills support technical documentation, user instructions, procedures, software requirements, interface messages, and support content. Always review generated content for technical accuracy before publication or operational use.
