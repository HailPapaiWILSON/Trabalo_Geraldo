## 1. Do que se trata este artigo?

O artigo investiga uma pergunta simples, mas importante: código escrito com ajuda de IA realmente facilita o desenvolvimento sem criar problemas futuros?

Para responder isso, os autores usaram o GitHub GitHub Copilot para implementar 115 funcionalidades reais em 23 projetos Java de código aberto. Depois, mediram se o código ficou mais fácil ou mais difícil de manter ao longo do tempo. 

---

## 2. O que eles descobriram?

### A IA normalmente consegue “encaixar” novas funcionalidades sem bagunçar completamente a estrutura existente

Em 55,7% das classes analisadas, a IA adicionou funcionalidades sem alterar a “coesão” do código — isto é, sem transformar uma parte do sistema em algo confuso ou sem foco. Apenas 16,4% melhoraram estruturalmente, enquanto 27,9% pioraram. 

Na prática, isso significa que o Copilot geralmente consegue seguir a lógica local de um arquivo existente. Ele tende a entender “qual é a responsabilidade daquela classe” e adicionar código sem destruir completamente sua organização interna.

Mas o fato de quase 28% dos casos terem piorado também importa bastante. Em software, quando uma classe começa a acumular responsabilidades demais, ela vira um ponto difícil de entender, testar e modificar. Isso aumenta o risco de bugs futuros e torna a manutenção mais lenta.

---

### O maior problema não foi a organização interna — foi o aumento da dependência entre partes do sistema

O estudo mostrou que a IA preservou relativamente bem a hierarquia e a organização básica do código, mas aumentou o “acoplamento” (dependência entre componentes) e a complexidade das classes. 

Em termos simples: o código funcionava, mas frequentemente passava a depender de mais partes do sistema ao mesmo tempo.

Na prática, isso gera um efeito cascata. Uma mudança pequena em um componente pode obrigar alterações em vários outros arquivos conectados a ele. Isso deixa o software mais frágil e mais caro de evoluir.

É a diferença entre:

* adicionar uma peça nova em uma máquina organizada;
* ou adicionar uma peça puxando fios para todos os lados.

O sistema continua funcionando, mas fica mais difícil mexer nele depois.

---

### A IA frequentemente cria “code smells”

O estudo encontrou novos “code smells” em 57 das 115 funcionalidades implementadas — quase metade dos casos. 

“Code smell” (“cheiro de código”) é um sinal de má estrutura no software. Não é necessariamente um bug, mas é um indício de que aquele trecho pode causar problemas futuros.

Exemplos comuns:

* código duplicado;
* funções grandes demais;
* nomes confusos;
* classes fazendo responsabilidades demais;
* dependências excessivas.

Na prática, isso significa que o código da IA muitas vezes funciona hoje, mas cria uma “conta técnica” para o futuro. O sistema fica mais difícil de entender e modificar conforme cresce.

---

### Muitos desses problemas não eram leves

Dos novos problemas encontrados:

* 52,3% foram classificados como criticidade média;
* 27,1% foram classificados como alta criticidade. 

Isso é importante porque os problemas detectados não eram apenas detalhes cosméticos ou estilo de programação. Eles afetavam diretamente a qualidade estrutural do sistema.

Na prática, uma empresa usando IA para acelerar desenvolvimento pode acabar criando um software que cresce rápido, mas vai ficando cada vez mais caro de manter.

---

### Cada funcionalidade gerada pela IA frequentemente traz uma “taxa escondida” de manutenção

Os autores calcularam quanto tempo seria necessário para corrigir os problemas introduzidos pela IA.

O resultado médio foi de 38,1 minutos de refatoração (reestruturação do código para melhorar sua qualidade) por funcionalidade problemática. 

Isso parece pouco isoladamente, mas o impacto acumulado é grande.

Se uma equipe usa IA para gerar centenas de funcionalidades, esse tempo extra pode virar semanas inteiras gastas apenas limpando código ruim.

O estudo descreve isso como um “paradoxo de produtividade”:

* a IA acelera o desenvolvimento agora;
* mas cria dívida técnica (problemas estruturais acumulados) que cobra tempo depois.

---

### A IA ainda pensa mais no problema imediato do que na arquitetura geral do sistema

A conclusão central do estudo é que ferramentas como o Copilot são boas assistentes para tarefas locais e específicas, mas ainda não possuem uma visão arquitetural ampla do sistema. 

Na prática:

* a IA consegue implementar uma funcionalidade;
* mas não necessariamente escolhe a melhor forma estrutural de integrá-la ao sistema inteiro.

Ela tende a priorizar “fazer funcionar” em vez de “fazer funcionar de forma sustentável a longo prazo”.

---

### Revisão humana continua sendo necessária

O artigo reforça repetidamente que o código gerado por IA precisa de revisão humana rigorosa. 

Na prática, isso significa que empresas não podem simplesmente aceitar automaticamente tudo que a IA produz. O ganho real vem quando:

* a IA acelera partes repetitivas;
* e desenvolvedores humanos supervisionam arquitetura, organização e qualidade estrutural.

Sem isso, a velocidade inicial pode virar manutenção cara no futuro.

---

## 3. Conclusão final

O estudo mostra que IA para programação realmente acelera o desenvolvimento, mas frequentemente produz código mais complexo, mais conectado e mais difícil de manter ao longo do tempo.

A principal ideia do artigo é: hoje, ferramentas como o Copilot funcionam melhor como assistentes rápidos de implementação — não como arquitetos confiáveis de software.
