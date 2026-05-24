## Resumo do artigo sobre código gerado por IA

### 1. Do que se trata este artigo?

O artigo investiga se o código de programação produzido por inteligências artificiais — como o GitHub Copilot ou o ChatGPT — é realmente confiável. Ele tenta responder a uma pergunta prática: quando uma IA escreve um programa, esse programa funciona corretamente, é seguro contra ataques e será fácil de manter no futuro, ou ele esconde problemas que só aparecem depois?

### 2. O que eles descobriram?

A pesquisa reuniu dezenas de estudos e analisou mais de 211 milhões de linhas de código. As descobertas mais importantes são estas:

**Código gerado por IA costuma ter falhas de segurança graves.** Dependendo da forma como a medição é feita, entre 12% e 62% dos programas escritos por IA contêm pelo menos uma vulnerabilidade conhecida. Na prática, isso significa que, se uma empresa usar código da IA sem revisão cuidadosa, cerca de 1 a cada 3 ou 4 programas pode permitir que um invasor acesse dados ou assuma o controle do sistema. Em linguagens como C/C++, que exigem gerenciamento manual da memória, a taxa de vulnerabilidade chega a 41%.

**O problema de segurança está piorando rapidamente.** Entre dezembro de 2024 e junho de 2025, a quantidade de falhas de segurança encontradas em código gerado por IA aumentou dez vezes. Vulnerabilidades mais difíceis de detectar — como caminhos que permitem a um usuário comum ganhar privilégios de administrador — subiram mais de 300%. Isso significa que, mesmo que os erros mais óbvios estejam diminuindo, os erros mais perigosos estão se multiplicando.

**Se você pedir para a IA melhorar o próprio código repetidamente, a situação piora.** Um experimento mostrou que, após apenas cinco rodadas de refinamento automático (sem um humano no meio), o número de vulnerabilidades críticas aumentou 37,6%. Mesmo quando a IA é instruída a focar em segurança, o resultado não melhora — e às vezes piora. Na prática, isso quebra a intuição comum de que "quanto mais a IA revisa, melhor o código fica".

**O código gerado por IA está tornando os programas mais difíceis de manter no longo prazo.** Entre 2020 e 2024, a proporção de linhas de código que foram reorganizadas para ficarem mais limpas (chamada de "refatoração") caiu de 25% para menos de 10%. Ao mesmo tempo, a quantidade de trechos de código copiados e colados aumentou oito vezes — o que viola um princípio básico de boa engenharia: "não se repita". Na prática, uma empresa que adota IA sem controle verá seu sistema ficar cada vez mais bagunçado e caro de corrigir, com custos de manutenção estimados em quatro vezes o normal após dois anos.

**Os desenvolvedores confiam mais do que deveriam.** Apesar de apenas 33% dos programadores dizerem que confiam totalmente no código da IA, 60% aceitam as sugestões da IA sem fazer uma verificação completa. Há um fenômeno chamado "falsa sensação de segurança": programadores que usam IA classificam seu próprio código (gerado com ajuda da IA) como mais seguro do que ele realmente é. Na prática, isso significa que a ferramenta que acelera o trabalho também desarma o senso crítico de quem está revisando.

**A IA é ótima para problemas simples, mas falha em tarefas complexas do mundo real.** Em testes com funções curtas e bem definidas, as melhores IAs acertam mais de 90% das vezes. Porém, quando o desafio é resolver um problema real de um sistema grande (como corrigir um bug documentado por usuários), o índice de acerto cai para cerca de 45% em média, e para menos de 30% em tarefas completamente novas. Na prática, a IA é excelente para escrever pedaços pequenos de código repetitivo, mas não serve para arquitetar soluções completas.

### 3. Conclusão final

A IA acelera a produção de código de forma real e impressionante, mas esse ganho de velocidade vem acompanhado de mais falhas de segurança, mais bagunça estrutural e uma confiança exagerada por parte dos programadores. A principal lição é que o código gerado por IA não pode ser usado sem supervisão humana qualificada — o caminho seguro não é substituir programadores por IA, mas sim usar a IA para tarefas simples enquanto humanos mantêm o controle sobre segurança e arquitetura.
