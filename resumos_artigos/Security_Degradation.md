**Do que se trata este artigo?**

Este artigo investiga o que acontece com a segurança do código quando você pede repetidamente para uma inteligência artificial (como o ChatGPT ou Copilot) “melhorar” um programa que inicialmente era seguro. Em vez de olhar apenas para o primeiro código gerado pela IA, os pesquisadores analisaram o que ocorre ao longo de várias rodadas de refinamento automático. A pergunta central é: iterar com IA realmente deixa o código mais seguro ou, ao contrário, cria novos problemas?

**O que eles descobriram?**

Os pesquisadores começaram com códigos seguros e pediram à IA para melhorá-los em até 10 rodadas seguidas, usando quatro tipos diferentes de instruções: focadas em velocidade, em adicionar funções novas, em segurança e em “melhorar de forma geral”.

A principal descoberta foi que **a segurança tende a piorar com o tempo**. Após apenas cinco iterações, o número de vulnerabilidades críticas aumentou 37,6%. Quanto mais rodadas, maior o acúmulo de falhas de segurança. Na prática, isso significa que um desenvolvedor que fica pedindo “melhora isso” repetidamente para a IA sem revisar com atenção pode acabar com um código que parece mais sofisticado, mas está ficando progressivamente mais perigoso.

Diferentes formas de pedir melhorias geram problemas diferentes. Pedidos focados em **eficiência** (deixar o código mais rápido) foram os que criaram mais falhas graves, especialmente problemas de memória. Pedidos para **adicionar funcionalidades** geraram o maior volume total de vulnerabilidades, muitas relacionadas a concorrência e validação de dados. Surpreendentemente, mesmo quando a pessoa pedia explicitamente para “melhorar a segurança”, a IA ainda introduzia novas falhas — muitas vezes complicando demais o código ou usando técnicas de segurança ultrapassadas ou incorretas.

Outra descoberta importante é que, conforme o código vai sendo modificado, ele fica mais complexo (mais linhas e estruturas mais complicadas), e essa complexidade extra está fortemente ligada ao aparecimento de mais falhas de segurança. O código parece “mais avançado”, o que pode dar uma falsa sensação de qualidade para quem está usando a IA.

**Conclusão final**

A mensagem mais importante deste artigo é clara: **iterar código com IA sem intervenção humana não melhora a segurança — muitas vezes piora**. A inteligência artificial é uma ferramenta poderosa, mas ainda precisa de revisão cuidadosa de pessoas experientes entre as melhorias para evitar que o “melhoramento” acabe criando novos riscos de segurança.
