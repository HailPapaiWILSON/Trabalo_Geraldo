## Do que se trata este artigo?

Este artigo investiga um problema pouco discutido sobre código gerado por IA: não basta o programa “funcionar”. Ele também precisa ser seguro, fácil de manter, eficiente e compreensível por humanos. Os autores querem descobrir se os modelos de IA realmente produzem código de boa qualidade nesses aspectos menos visíveis.

Para isso, eles combinaram três coisas: análise de mais de 100 estudos científicos, workshops com profissionais da indústria e testes práticos usando modelos como GPT-4o, Claude e DeepSeek em problemas reais de software. 

---

## O que eles descobriram?

* A pesquisa atual olha muito mais para “o código funciona?” do que para “o código é bom?”. Os autores mostram que a maior parte dos testes usados hoje mede apenas se o programa passa nos testes, ignorando problemas como segurança, organização do código e facilidade de manutenção. Isso significa que uma IA pode gerar algo aparentemente correto, mas que vira um pesadelo para equipes manterem depois. 

* Segurança é a característica mais estudada pelos pesquisadores, mas isso acontece em parte porque é mais fácil medi-la automaticamente. Cerca de 33,6% dos estudos encontrados focavam em segurança, enquanto atributos como confiabilidade e modularidade receberam pouca atenção. Na prática, isso cria uma visão distorcida da qualidade do código, porque os pesquisadores acabam estudando mais aquilo que ferramentas conseguem medir facilmente. 

* Um estudo citado no artigo encontrou vulnerabilidades em aproximadamente 40% dos programas gerados por IA em cenários de segurança críticos. Em termos simples: quase 2 em cada 5 programas criados pela IA tinham algum padrão considerado inseguro. Isso ajuda a explicar por que muitas empresas ainda hesitam em confiar totalmente em código gerado automaticamente. 

* Outro trabalho citado encontrou falhas de segurança em 27,3% dos códigos gerados. Essas falhas incluíam problemas sérios, como números aleatórios previsíveis e ataques de Cross-Site Scripting (quando um invasor injeta código malicioso em páginas web). O artigo também mostra que prompts melhores conseguiram corrigir até 55,5% dessas falhas. Isso indica que a forma como a IA é instruída muda muito a qualidade do resultado. 

* O desempenho do código depende fortemente de como o pedido é escrito para a IA. Sem instruções específicas, os modelos tendem a gerar soluções “óbvias”: funcionam, mas usam mais memória ou executam mais lentamente do que o necessário. Em outras palavras, a IA normalmente prioriza “dar uma resposta” antes de “dar a melhor resposta”. 

* Empresas se preocupam muito mais com manutenção e legibilidade do que os pesquisadores imaginavam. Nos workshops com profissionais, a principal preocupação não foi segurança ou velocidade, mas sim a dificuldade futura de entender e modificar o código gerado por IA. O medo é que as equipes acumulem “dívida técnica” — atalhos e código confuso que tornam sistemas cada vez mais difíceis de evoluir. 

* Os profissionais relataram que pequenos trechos gerados por IA costumam ser aceitáveis, mas sistemas maiores rapidamente ficam difíceis de entender. À medida que o projeto cresce, a IA começa a produzir código mais bagunçado, menos modular e mais difícil de manter. Isso sugere que gerar uma função pequena é muito diferente de gerar partes grandes de um software real. 

* Existe um conflito entre produtividade imediata e manutenção futura. A IA acelera o desenvolvimento hoje, mas pode aumentar o custo de manutenção amanhã. Os participantes dos workshops disseram que o problema deixa de ser “encontrar bugs” e passa a ser “entender o que a IA fez”. 

* Os autores testaram três modelos de IA em tarefas reais de programação e descobriram que todos ficaram muito abaixo das soluções humanas de referência. O Claude 4 Sonnet teve o melhor desempenho geral, resolvendo corretamente 36% dos problemas. O GPT-4o conseguiu gerar mais códigos “aplicáveis” ao projeto, mas resolveu corretamente apenas 16% das tarefas. O DeepSeek ficou no meio, com 20%. Isso mostra que mesmo modelos avançados ainda falham bastante em tarefas reais de engenharia de software. 

* Muitos erros não vieram da lógica do programa, mas da incapacidade da IA de lidar com o ambiente do projeto. Os pesquisadores observaram que os modelos frequentemente gastavam tentativas tentando corrigir problemas de importação, comandos de terminal e integração do sistema, em vez de melhorar o código em si. Isso sugere que o gargalo não é apenas “escrever código”, mas entender todo o contexto ao redor dele. 

* O código gerado pelas IAs introduziu muito mais problemas de manutenção do que o código humano equivalente. Nos testes, os patches humanos adicionaram apenas 30 recomendações de manutenção. Já os modelos de IA geraram mais de 400 alertas cada. Isso indica que o código da IA frequentemente cria estruturas confusas ou desnecessárias, mesmo quando resolve o problema corretamente. 

* O GPT-4o produziu código significativamente maior do que os humanos. Enquanto os patches humanos adicionavam em média 2,65 linhas, o GPT-4o adicionava cerca de 16,7 linhas. Isso sugere que modelos de IA tendem a resolver problemas com soluções mais verbosas e inchadas do que desenvolvedores humanos experientes. 

* O código gerado por IA também consumiu mais tempo e memória durante os testes. O GPT-4o, por exemplo, teve tempo médio de execução de 23,37 segundos contra 14,26 segundos das soluções humanas. O consumo de memória também quase dobrou em alguns casos. Na prática, isso significa programas potencialmente mais lentos e mais caros para rodar. 

* Tentar melhorar um aspecto do código frequentemente piorava outro. Quando os pesquisadores pediram explicitamente para a IA gerar código mais seguro, a taxa de sucesso funcional caiu bastante. Em outras palavras: ao focar demais em segurança, os modelos começaram a quebrar mais funcionalidades. Isso mostra que otimizar código gerado por IA é um equilíbrio delicado. 

* Mesmo assim, os prompts especializados tiveram alguns efeitos positivos. Quando a IA recebia feedback específico sobre desempenho ou manutenção, muitos programas ficaram mais rápidos, usaram menos memória ou reduziram problemas detectados por ferramentas automáticas. Porém, os resultados foram instáveis: às vezes melhoravam muito, às vezes pioravam. 

* O artigo conclui que hoje não existe um sistema padronizado para medir qualidade em código gerado por IA. Cada pesquisa usa métricas diferentes, ferramentas diferentes e definições diferentes. Isso dificulta comparar estudos e entender realmente quais modelos produzem software melhor. 

---

## Conclusão final

O principal recado do artigo é que “código que funciona” não é o mesmo que “código de qualidade”. Modelos de IA já conseguem resolver muitos problemas, mas ainda produzem código mais difícil de manter, potencialmente inseguro e frequentemente menos eficiente do que soluções humanas bem feitas.

Os autores defendem que o futuro da programação com IA dependerá menos de fazer a IA gerar código e mais de criar mecanismos confiáveis para verificar, corrigir e controlar a qualidade desse código automaticamente.
