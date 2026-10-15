---
name: pt-br-linguagem-tecnica-controlada
description: Criar, revisar e simplificar textos técnicos em português brasileiro. Use em documentação de sistemas, instruções para usuários, procedimentos, mensagens de interface, artigos de ajuda, requisitos, tickets e comunicados técnicos.
---

# Português Brasileiro: Linguagem Simples e Técnica Controlada

## Objetivo

Escreva textos técnicos em português brasileiro que sejam fáceis de entender, diretos e precisos. Ajude o leitor a entender uma informação ou executar uma tarefa sem precisar interpretar frases vagas ou complexas.

Use esta skill em documentação de sistemas, manuais, tutoriais, procedimentos, mensagens de erro, textos de interface, instruções para equipes, requisitos, tickets, README, notas de versão e conteúdo de suporte.

## Relação com a ASD-STE100

A ASD-STE100 é um padrão de linguagem controlada para o inglês técnico. Esta skill adapta princípios de clareza, consistência e redução de ambiguidades ao português brasileiro. **Ela não é uma tradução oficial da ASD-STE100, não reproduz suas regras específicas de inglês e não certifica conformidade com esse padrão.**

Use o **Português Técnico Controlado (PTC)** como convenção editorial de trabalho: vocabulário consistente, termos definidos, frases diretas e instruções verificáveis. Trate o PTC aqui como uma prática interna de escrita, não como uma norma oficial publicada.

## Regras principais

1. **Considere o leitor.** Identifique quem vai ler o texto, o que precisa entender e qual ação precisa executar.
2. **Vá direto ao ponto.** Coloque a informação ou a ação principal no início. Evite introduções que não ajudam o leitor.
3. **Prefira palavras comuns e concretas.** Troque expressões burocráticas por verbos claros, sem perder precisão técnica.
4. **Trate cada frase como uma unidade de informação.** Se uma frase tiver várias ações, condições ou resultados, divida-a.
5. **Use a voz ativa.** Diga quem executa a ação. Prefira “O sistema valida o campo” a “O campo é validado pelo sistema”, salvo quando o agente não for relevante.
6. **Prefira verbos a substantivos abstratos.** Por exemplo, prefira “verifique os dados” a “realize a verificação dos dados”.
7. **Dê instruções explícitas.** Use verbos de ação como “Abra”, “Selecione”, “Informe”, “Marque”, “Clique”, “Salve” e “Confirme”, conforme a ação real.
8. **Evite ambiguidades.** Não use “ele”, “ela”, “isso”, “esse campo” ou “a opção anterior” quando houver mais de uma interpretação possível. Repita o nome exato quando necessário.
9. **Não varie termos por estilo.** Use sempre o mesmo termo para o mesmo conceito. Não alterne entre “pedido”, “solicitação” e “requisição” se todos indicarem o mesmo objeto do sistema.
10. **Preserve os nomes técnicos.** Mantenha nomes de telas, menus, rotas, endpoints, campos, tabelas, classes, variáveis, comandos e arquivos exatamente como são usados no sistema.
11. **Organize as condições.** Especifique quando uma regra se aplica, o que acontece e quais exceções existem. Não esconda condições importantes no meio de uma frase longa.
12. **Distinga obrigação, possibilidade e proibição.** Use “deve” para uma regra obrigatória, “pode” para uma opção permitida e “não pode” para uma proibição. Não use essas expressões como se fossem equivalentes.
13. **Mantenha frases curtas, sem criar frases telegráficas.** Como referência, procure ficar em torno de 20 a 25 palavras por frase. Divida antes disso quando houver mais de uma ideia ou risco de interpretação.
14. **Explique siglas e termos incomuns.** Na primeira ocorrência, escreva o nome por extenso quando isso ajudar o público. Depois, use a mesma forma em todo o documento.
15. **Use formatação funcional.** Prefira títulos descritivos, listas para itens e passos numerados para sequências obrigatórias. Destaque avisos apenas quando forem relevantes.
16. **Preserve os fatos.** Não invente comportamentos, causas, prazos, resultados, limitações ou regras para deixar o texto mais completo.
17. **Simplifique sem infantilizar.** O leitor deve receber a informação necessária, inclusive detalhes técnicos, restrições e exceções.
18. **Adapte o vocabulário ao público.** Evite jargão para usuários finais. Use termos técnicos com precisão quando o texto for destinado a desenvolvedores ou profissionais da área.

## Instruções para usuários

Ao descrever uma tarefa:

- Diga qual tela, menu ou recurso a pessoa deve acessar.
- Use os nomes exatos exibidos na interface.
- Coloque as ações na ordem correta.
- Mantenha uma ação principal por etapa.
- Informe pré-requisitos antes da ação que depende deles.
- Explique o resultado esperado quando isso ajudar a confirmar que a tarefa terminou.
- Informe o que fazer em caso de erro somente quando houver um procedimento conhecido.
- Não presuma que o usuário conhece regras internas do sistema.

**Exemplo de estilo**

Evite: “Para que seja possível efetuar a alteração desejada, deverá ser realizada a seleção do registro correspondente e, posteriormente, deverá ser acionado o recurso de gravação.”

Prefira: “Abra o cadastro. Selecione o registro que deseja alterar. Edite os campos necessários e clique em **Salvar**.”

O exemplo demonstra o estilo recomendado. Não substitua os nomes reais dos recursos do sistema por nomes genéricos em uma documentação final.

## Requisitos e instruções para desenvolvimento

Ao transformar uma solicitação em requisito técnico:

- Separe o contexto, o comportamento atual, o comportamento esperado e os critérios de aceite quando forem relevantes.
- Informe as rotas, telas, APIs e componentes envolvidos quando forem conhecidos.
- Descreva condições e exceções de forma testável: “Quando X ocorrer, o sistema deve fazer Y”.
- Separe o que precisa mudar do que deve permanecer igual.
- Peça a inspeção do fluxo existente antes de recomendar alterações quando a causa ainda não estiver confirmada.
- Não prescreva uma implementação específica se o requisito define apenas o resultado esperado.
- Não invente nomes de campos, tabelas, arquivos, métodos ou endpoints.
- Use blocos de código para comandos, JSON, SQL, nomes técnicos ou exemplos que precisem ser copiados sem alteração.
- Escreva critérios de aceite que possam ser verificados por uma pessoa ou por um teste.

## Mensagens de erro e avisos

Uma mensagem útil deve explicar, na medida em que os fatos forem conhecidos:

1. O que aconteceu.
2. Por que aconteceu, somente se a causa estiver confirmada.
3. O que a pessoa pode fazer em seguida.

Evite mensagens vagas, como “Erro inesperado”, quando houver uma descrição mais precisa. Não atribua uma causa provável como se fosse um fato.

Em avisos de risco, informe o perigo e a ação necessária. Não crie níveis de severidade nem altere avisos definidos por normas, contratos ou requisitos do produto.

## Terminologia controlada

Mantenha um glossário quando vários documentos descrevem o mesmo sistema. Para cada conceito, registre:

- termo preferido;
- significado no contexto do sistema;
- nomes alternativos que devem ser evitados;
- grafia e capitalização oficiais;
- nome exato na interface, quando aplicável.

Use os mesmos termos em telas, documentação, exemplos, mensagens e critérios de aceite. Não traduza identificadores de código nem altere nomes oficiais da interface sem solicitação.

## Fluxo de trabalho

1. **Entenda:** identifique o público, a finalidade, o formato e a ação ou informação principal.
2. **Separe os fatos:** preserve nomes, valores, condições, restrições, dependências e exceções.
3. **Estruture:** escolha títulos e listas que ajudem o leitor a localizar a informação.
4. **Escreva:** use frases diretas, verbos precisos e termos consistentes.
5. **Revise a clareza:** remova redundâncias, burocratês, ambiguidades e explicações que não ajudam a tarefa.
6. **Revise a precisão:** compare o texto com a solicitação ou fonte. Não complete lacunas com suposições.
7. **Entregue:** forneça o texto final no formato solicitado. Explique uma incerteza apenas quando ela afetar a compreensão ou a correção.

## Lista de verificação

- O público e o objetivo estão claros?
- A informação principal ou a ação aparece logo no início?
- Cada frase contém uma ideia principal?
- A pessoa sabe quem deve agir, o que fazer e onde fazer?
- As condições, os resultados e as exceções estão explícitos?
- Os termos são consistentes em todo o texto?
- Os nomes de telas, campos, rotas, arquivos e comandos foram preservados?
- O texto distingue regra obrigatória, opção e proibição?
- O texto mantém todos os fatos e limites da fonte?
- Alguma causa, comportamento ou promessa foi inventada?
- Um usuário do público-alvo consegue executar a tarefa sem adivinhar o próximo passo?

## Comportamento esperado

- Ao **criar** um texto, entregue diretamente o conteúdo solicitado.
- Ao **revisar**, corrija clareza, consistência, gramática e estrutura sem alterar o sentido.
- Ao **simplificar**, preserve termos técnicos necessários, restrições, exceções e detalhes relevantes.
- Ao **escrever requisitos**, prefira comportamentos verificáveis a soluções presumidas.
- Se houver uma lacuna técnica importante, não adivinhe. Faça uma pergunta objetiva ou identifique claramente a informação pendente.
- Não inclua comentários introdutórios, justificativas extensas ou várias versões, a menos que sejam solicitados.
