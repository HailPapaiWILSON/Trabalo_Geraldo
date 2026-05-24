### 1. Do que se trata este artigo?

O artigo investiga se o código de programação gerado por inteligências artificiais (como o ChatGPT ou o Claude) é realmente seguro e bem feito, ou se contém erros ocultos. Os pesquisadores testaram cinco IAs diferentes, pedindo que cada uma resolvesse mais de 4 mil problemas de programação em Java, e depois analisaram a qualidade do código produzido com ferramentas automáticas de busca de defeitos.

### 2. O que eles descobriram?

**Os programas gerados por IA sempre têm problemas – mesmo quando funcionam.**  
Pode parecer que o código está correto porque ele passa nos testes básicos, mas a análise detalhada mostra defeitos em praticamente todos os exemplos. Por exemplo, o melhor modelo (Claude Sonnet 4) acertou 77% dos testes, mas cada programa que ele acertou continha, em média, mais de 2 problemas detectados pela ferramenta. Na prática, isso significa que uma empresa que use código gerado por IA sem revisão pode acabar com softwares que funcionam hoje, mas que são frágeis, inseguros ou difíceis de manter no futuro.

**Os problemas mais comuns são “maus cheiros” no código (indícios de má estrutura), mas também aparecem bugs e falhas graves de segurança.**  
A maioria dos defeitos (~90%) são coisas como código redundante, lógica muito complicada ou violações de boas práticas – problemas que tornam o software difícil de entender e modificar. Porém, cerca de 5–8% são bugs reais (que podem fazer o programa travar) e cerca de 2% são vulnerabilidades de segurança. O número parece pequeno, mas, considerando que uma única vulnerabilidade pode expor dados de clientes, isso representa um risco real. Por exemplo, todos os modelos geraram código com senhas escritas em texto claro dentro do programa (o que é um erro gravíssimo de segurança).

**Não existe relação entre quão bem a IA passa em testes de desempenho e quão seguro ou bem estruturado é o código que ela gera.**  
Um modelo pode tirar nota alta nos testes funcionais (acertar as respostas), mas produzir código cheio de falhas escondidas. Isso significa que, para quem escolhe uma IA para programar, olhar apenas para a “taxa de acertos” (como se fosse uma nota de prova) é enganoso. Um modelo menor e mais simples (OpenCoder-8B) produziu, por programa bem-sucedido, menos problemas do que um modelo muito maior e mais famoso (Claude Sonnet 4). Ou seja: maior nem sempre é melhor.

**As IAs cometem erros parecidos, independentemente do fabricante ou do tamanho.**  
Todas as cinco IAs analisadas apresentaram os mesmos tipos de defeito nas mesmas proporções aproximadamente. Isso sugere que o problema não é de uma IA específica, mas uma limitação fundamental da tecnologia atual: essas IAs aprendem com código existente na internet (que muitas vezes é antigo, mal escrito ou inseguro) e repetem esses padrões sem conseguir distinguir o que é seguro do que é arriscado. Um exemplo concreto: várias IAs sugeriram o uso de bibliotecas desatualizadas que contêm falhas de segurança conhecidas (chamadas CVEs).

**Problemas sérios se tornaram ainda mais frequentes em versões mais novas de um mesmo modelo.**  
Ao comparar duas versões do Claude (a 3.7 e a 4), os pesquisadores viram que a versão mais nova acertava mais testes (77% contra 72%), mas também produzia uma proporção maior de bugs e vulnerabilidades classificados como “bloqueadores” – os mais graves. Em outras palavras, melhorar o desempenho funcional não reduziu os defeitos; em alguns casos, piorou a severidade deles.

### 3. Conclusão final

Código gerado por inteligência artificial pode parecer funcional, mas quase sempre contém defeitos ocultos – incluindo falhas graves de segurança. Portanto, nenhum programa escrito por IA deve ser usado diretamente em produção sem passar por uma verificação rigorosa com ferramentas automáticas de análise de código.
