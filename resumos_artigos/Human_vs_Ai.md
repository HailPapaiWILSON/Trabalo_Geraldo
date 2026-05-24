### Do que se trata este artigo?

Pesquisadores da Universidade de Nápoles analisaram mais de 500 mil trechos de código escritos por humanos e por três sistemas de inteligência artificial — ChatGPT, DeepSeek e Qwen — para entender quem produz código de melhor qualidade. Eles compararam três aspectos: quantos erros o código contém, quão vulnerável ele é a ataques e invasões, e quão complexo é em termos de estrutura.

---

### O que eles descobriram?

**O código de IA é mais simples — mas simples nem sempre é bom.**
O código gerado por IA é consistentemente mais curto e mais direto do que o humano: em média, tem quase 7 linhas a menos e usa cerca de 64 unidades de vocabulário ("tokens", que são as palavras e símbolos que compõem um programa) a menos por função. Isso pode parecer uma vantagem, mas na prática significa que a IA frequentemente escreve soluções rasas que ignoram casos excepcionais, situações de erro e lógica mais elaborada — o tipo de coisa que um programador experiente anteciparia.

**A IA comete erros diferentes dos humanos, não necessariamente menos.**
Humanos tendem a escrever código mais complexo, o que introduz problemas de manutenção — como funções difíceis de entender ou estruturas excessivamente emaranhadas. Já a IA produz erros mais repetitivos e mecânicos: declara parâmetros que nunca usa, deixa variáveis sem propósito, e insere comandos de depuração (instruções temporárias que os programadores usam para testar o código durante o desenvolvimento, mas que não deveriam aparecer no produto final). Esses problemas não travam o programa, mas indicam código gerado sem real compreensão do que está fazendo.

**O código de IA é significativamente mais inseguro.**
Essa é a descoberta mais preocupante. Em Python, os modelos de IA geraram cerca de 5 mil amostras vulneráveis a mais do que humanos. Em Java, essa diferença sobe para 18 mil. As vulnerabilidades mais comuns no código de IA incluem "injeção de comandos" (quando um programa aceita instruções maliciosas de fora sem verificar se são seguras) e "credenciais hardcoded" (senhas e chaves de segurança escritas diretamente no código, onde qualquer pessoa que acesse o arquivo pode vê-las). Essas são falhas sérias — elas estão na lista das 25 vulnerabilidades mais perigosas do mundo, segundo o órgão internacional que cataloga esse tipo de problema (MITRE). Em termos práticos: um sistema construído com esse código poderia ser invadido com técnicas relativamente simples.

**DeepSeek foi consistentemente o pior, ChatGPT o mais equilibrado.**
Entre os três modelos analisados, o DeepSeek produziu o código mais defeituoso e mais inseguro nas duas linguagens. Em Java, quase 20% de todo o código gerado por ele continha vulnerabilidades de segurança, contra 3% no código humano. O ChatGPT apresentou desempenho mais estável — ainda pior que humanos em segurança, mas com erros menos graves e mais previsíveis.

**A IA escreve bem em Python, mal em Java.**
Python é uma linguagem mais flexível e permissiva. Java é mais rígida e estruturada. Os modelos de IA se saíram melhor em Python — chegando a gerar menos amostras defeituosas que humanos nessa linguagem — mas tiveram dificuldade significativa com Java, produzindo em média 22 mil amostras defeituosas a mais. Isso sugere que a IA tem mais facilidade com linguagens que tolerem imprecisão e menos com aquelas que exigem estrutura rigorosa.

---

### Conclusão final

O código gerado por IA pode acelerar o desenvolvimento, mas introduz um perfil de risco distinto do humano — especialmente em segurança. Antes de colocar código de IA em produção, ele precisa ser revisado com essa diferença em mente: não basta verificar se funciona, é preciso verificar se é seguro.
