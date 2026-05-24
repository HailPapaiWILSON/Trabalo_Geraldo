## 1. Do que se trata este artigo?

Este artigo investiga se o código de programação gerado por inteligências artificiais (como o ChatGPT ou o GitHub Copilot) é seguro ou se contém falhas que criminosos virtuais podem explorar. A pergunta central é: até que ponto o uso de IAs para escrever software representa um risco para a segurança digital?

## 2. O que eles descobriram?

Os pesquisadores analisaram dezenas de estudos sobre o assunto e chegaram a várias conclusões importantes. Aqui estão as principais:

**O código gerado por IA frequentemente contém falhas de segurança conhecidas.**  
Na prática, isso significa que, ao pedir para uma IA escrever um trecho de programa, há uma boa chance de ela produzir um código com os mesmos tipos de erro que já estão documentados como perigosos. Um estudo citado no artigo descobriu que **40% do código sugerido pelo Copilot (uma ferramenta da Microsoft) tinha vulnerabilidades**. Traduzindo: a cada cinco pedaços de código gerados por IA, dois podem conter um problema que um invasor poderia usar.

**A linguagem de programação faz muita diferença.**  
Código em Python (linguagem mais simples e moderna) tende a ser mais seguro do que código em C (linguagem mais antiga e de baixo nível, usada em sistemas operacionais). Os pesquisadores acreditam que isso acontece porque a IA foi treinada com mais exemplos bons de Python do que de C. Na prática, se você pedir para uma IA gerar um programa em C, o risco de falhas críticas (como vazamento de memória) é maior do que se pedir o mesmo programa em Python.

**A IA pode, sem querer, vazar dados pessoais no código que sugere.**  
Em experimentos, ferramentas como o Copilot geraram trechos que continham endereços de e-mail, senhas e até chaves privadas de criptografia – informações que estavam nos dados de treinamento da IA. Isso significa que, ao usar essas ferramentas, uma empresa pode acabar expondo acidentalmente informações sensíveis de terceiros.

**É possível usar a IA para criar códigos maliciosos, mas com limitações.**  
Criminosos virtuais podem usar IAs para gerar partes de vírus ou ransomwares. Porém, as IAs atuais não conseguem criar um programa malicioso completo do zero – elas produzem pedaços que precisam ser montados e corrigidos por um humano com conhecimento técnico. Ainda assim, isso reduz a barreira para pessoas menos experientes criarem ameaças.

**Os programadores confiam demais no código gerado por IA.**  
Um dos estudos citados mostrou que desenvolvedores que usaram assistentes de IA produziram mais código inseguro do que aqueles que programaram sozinhos. A razão parece ser psicológica: as pessoas acham que a IA está certa e deixam de verificar erros. Na prática, isso anula parte do ganho de produtividade, porque o código precisa ser revisado com cuidado redobrado.

**Existem tentativas de melhorar a segurança, mas nenhuma solução milagrosa.**  
Pesquisadores testaram estratégias como:
- Treinar a IA apenas com código de boa qualidade (o que reduz o tamanho do treinamento e piora o desempenho geral).
- Ajustar os “prompts” – os comandos que o usuário digita – para pedir explicitamente código seguro (funciona em parte, mas não garante).
- Usar ferramentas adicionais que varrem o código em busca de falhas depois que ele é gerado (recomendado, mas não resolve tudo).

Nenhuma dessas estratégias elimina completamente o risco.

## 3. Conclusão final

A IA é uma ferramenta útil para escrever código mais rápido, mas **não é confiável em segurança**: ela produz falhas conhecidas com frequência, pode vazar dados e gera uma confiança exagerada nos usuários. Por enquanto, qualquer código gerado por IA deve ser tratado como suspeito e passar por uma verificação de segurança rigorosa antes de ser usado em sistemas reais.
