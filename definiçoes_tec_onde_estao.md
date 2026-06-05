### *Esses conceitos foram gerados com NotebookLM, logo estão sujeitos a mudanças drásticas e não devem ser levados como a palavra final.*



Com base nos artigos fornecidos, as definições fundamentais para o referencial teórico foram identificadas e consolidadas conforme solicitado.

---

## 1. Inteligência Artificial Generativa (GenAI)

### Artigos que definem o conceito
* Artigo 5 ("2512.19926v1.pdf")
* Artigo 7 ("2603.16975v1.pdf")
* Artigo 9 ("s12599-026-00998-y.pdf")

### Trechos relevantes encontrados
* **Artigo 5 (Seção 2):** "A IA Generativa (GenAI) refere-se à tecnologia de IA que aprende com os dados para gerar de forma autônoma conteúdos novos, significativos e contextualmente apropriados em várias aplicações".
* **Artigo 7 (Seção 1):** "GenAI refere-se a uma classe de sistemas de aprendizado de máquina capazes de produzir conteúdo original (como texto, imagens, código ou som) aprendendo padrões de grandes conjuntos de dados e gerando resultados contextualmente coerentes".
* **Artigo 9 (Seção 2.1):** "GenAI é um tipo de IA especializado na geração de novos dados em vários formatos, como texto, imagens e áudio... suas capacidades são sustentadas por um conjunto de propriedades distintas: suas propriedades generativas, conversacionais, de raciocínio avançado e de variabilidade".

### Definição consolidada baseada na literatura
A **Inteligência Artificial Generativa (GenAI)** é uma classe de sistemas de aprendizado de máquina especializada na produção autônoma de conteúdos originais e dados novos (texto, imagens, som e código-fonte). Diferente de ferramentas determinísticas tradicionais, a GenAI aprende padrões complexos a partir de grandes conjuntos de dados para gerar saídas contextualmente coerentes e significativas. Suas capacidades fundamentais baseiam-se em quatro propriedades distintas: a capacidade **generativa** de criar artefatos inéditos; a **variabilidade** para gerar múltiplos resultados únicos; a natureza **conversacional** para interação em linguagem natural; e o **raciocínio avançado** para simular processos cognitivos como abstração e síntese.

### Observações
Os autores convergem na ideia de autonomia e criação de conteúdo inédito. O **Artigo 9** é o mais influente na caracterização formal, ao decompor o conceito em propriedades técnicas específicas (generativa, variabilidade, conversacional e raciocínio) que fundamentam o uso da ferramenta no desenvolvimento de software.

---

## 2. Large Language Models (LLMs)

### Artigos que definem o conceito
* Artigo 6 ("2602.13766v1.pdf")
* Artigo 7 ("2603.16975v1.pdf")
* Artigo 8 ("2603.26277v1.pdf")

### Trechos relevantes encontrados
* **Artigo 6 (Seção 1):** Mentions "Tools that integrate Large Language Models (LLMs), such as GitHub Copilot".
* **Artigo 7 (Seção 1):** "Exemplos proeminentes incluem LLMs como o ChatGPT, que processam e geram linguagem natural".
* **Artigo 8 (Seção 1):** "O advento dos Modelos de Linguagem de Grande Escala (LLMs) mudou ainda mais o cenário da automação em ES: chatbots baseados em LLM... ou ferramentas dentro de Ambientes de Desenvolvimento Integrados (IDEs) como o GitHub Copilot permitem que os desenvolvedores recebam ajuda para um grande número de tarefas".

### Definição consolidada baseada na literatura
Os **Modelos de Linguagem de Grande Escala (LLMs)** são sistemas de inteligência artificial treinados em volumes massivos de dados para processar e gerar linguagem natural e código de programação. Eles representam a tecnologia subjacente que alimenta tanto chatbots conversacionais (como o ChatGPT) quanto assistentes integrados em ambientes de desenvolvimento (como o GitHub Copilot), permitindo a automação e o suporte a uma ampla gama de tarefas de engenharia de software, incluindo design de arquitetura e prototipagem.

### Observações
A literatura analisada utiliza o conceito de forma operacional e relacional, frequentemente associando LLMs como o "motor" por trás de ferramentas comerciais de assistência ao código.

---

## 3. Ferramentas de IA para Desenvolvimento de Software

### Artigos que definem o conceito
* Artigo 1 ("2501.13282v1.pdf")
* Artigo 5 ("2512.19926v1.pdf")
* Artigo 6 ("2602.13766v1.pdf")
* Artigo 10 ("ssrn-4945566.pdf")

### Trechos relevantes encontrados
* **Artigo 1 (Seção 12):** "O GitHub Copilot é lançado como 'um novo par programador de IA que ajuda você [desenvolvedores] a escrever códigos melhores'... ele extrai o contexto do código em que você está trabalhando, sugerindo linhas inteiras ou funções inteiras".
* **Artigo 5 (Seção 2):** "GitHub Copilot... pode auxiliar os desenvolvedores gerando, completando e modificando o código de programação com base no contexto da base de código e em comandos de linguagem natural".
* **Artigo 10 (Seção 2.1):** "Assistentes de IA para desenvolvimento de software oferecem sugestões de código inteligentes e preenchimento automático dentro de ambientes de desenvolvimento integrados".
* **Artigo 6 (Seção 1):** "Além da automação, os Modelos Fundamentais (FMs) atuam como colaboradores cognitivos, aumentando o raciocínio humano e transformando a forma como as equipes projetam, comunicam e entregam software".

### Definição consolidada baseada na literatura
As **Ferramentas de IA para Desenvolvimento de Software** (também referidas como assistentes de codificação ou assistentes de IA) são sistemas projetados para atuar como "parceiros programadores de IA" integrados aos ambientes de desenvolvimento (IDEs). Elas funcionam como **colaboradores cognitivos** que extraem contexto da base de código atual e utilizam comandos em linguagem natural para oferecer sugestões inteligentes, completar trechos, refatorar código, gerar testes e documentação. Sua função principal é aumentar o raciocínio humano e acelerar o desenvolvimento através de sugestões automáticas de linhas ou funções inteiras.

### Observações
Há uma convergência clara entre os autores (especialmente de **Ziegler et al.** e as descrições do GitHub) ao caracterizar essas ferramentas através da metáfora do **"IA Pair Programmer"**.

---

## 4. Produtividade no Desenvolvimento de Software

### Artigos que definem o conceito
* Artigo 3 ("2509.20353v2.pdf")
* Artigo 4 ("2510.24265v2.pdf")
* Artigo 6 ("2602.13766v1.pdf")

### Trechos relevantes encontrados
* **Artigo 3 (Seção 2.1):** "A produtividade é geralmente definida como 'a razão da saída dividida pela entrada' (Petersen, 2011). Exemplos de saídas incluem qualidade e quantidade em termos de funções, linhas de código, alterações implementadas, enquanto as entradas são os esforços necessários para criar essas saídas".
* **Artigo 4 (Seção 1):** "A produtividade no desenvolvimento de software é um sistema sociotécnico multidimensional. Não é simplesmente mensurável pelo volume de saída. Inclui qualidade do trabalho a longo prazo, bem-estar psicológico, colaboração em equipe, foco ininterrupto e satisfação com o trabalho".
* **Artigo 6 (Seção 2):** "A produtividade do desenvolvedor não é uma métrica singular, mas um construto complexo e multidimensional... medí-la de forma eficaz requer um modelo holístico que equilibre vários fatores".

### Definição consolidada baseada na literatura
A **Produtividade no Desenvolvimento de Software** é tradicionalmente definida como a relação entre **saída** (output: quantidade e qualidade de código, funções e alterações) e **entrada** (input: esforço e tempo necessários). No entanto, a literatura moderna a caracteriza como um **sistema sociotécnico multidimensional** e complexo, que não pode ser capturado por uma métrica singular. Ela abrange dimensões humanas e técnicas, incluindo a qualidade do software a longo prazo, o bem-estar psicológico do desenvolvedor, a eficácia da colaboração em equipe, a satisfação profissional e a capacidade de manter um estado de fluxo e foco ininterrupto.

### Observações
Existe uma divergência entre a visão clássica (baseada em volume/taxa de entrega) e a visão contemporânea defendida por autores como **Forsgren et al.** e **Afroz et al.**, que priorizam uma abordagem holística e sistêmica.

---

## 5. Framework SPACE

### Artigos que definem o conceito
* Artigo 4 ("2510.24265v2.pdf")
* Artigo 6 ("2602.13766v1.pdf")
* Artigo 3 ("2509.20353v2.pdf")

### Trechos relevantes encontrados
* **Artigo 6 (Seção 2):** "O framework SPACE fornece tal modelo, definindo a produtividade através de cinco dimensões principais: Satisfação e bem-estar (S), Performance (P), Atividade (A), Comunicação e colaboração (C), e Eficiência e fluxo (E)".
* **Artigo 4 (Seção 3.1):** Detalha as dimensões: **Satisfação e bem-estar** (percepção de realização e apoio); **Performance** (resultados percebidos e velocidade); **Atividade** (volume de trabalho, como commits e revisões); **Comunicação e colaboração** (interação e coordenação); e **Eficiência e fluxo** (progresso com interrupções mínimas).
* **Artigo 4 (Seção 2.1):** "Criticamente, o framework SPACE visualiza a produtividade como um sistema de dimensões interdependentes em vez de métricas isoladas".

### Definição consolidada baseada na literatura
O **Framework SPACE** é um modelo multidimensional e holístico para a medição da produtividade de desenvolvedores, que substitui métricas isoladas por um sistema de dimensões interdependentes. Ele propõe cinco dimensões fundamentais:
1.  **Satisfação e bem-estar (S):** Fulfillment, motivação e suporte à equipe.
2.  **Performance (P):** Resultados dos processos e velocidade.
3.  **Atividade (A):** Volume de trabalho realizado (ex: número de commits e itens fechados).
4.  **Comunicação e colaboração (C):** Interação e coordenação entre os membros da equipe.
5.  **Eficiência e fluxo (E):** Progresso no trabalho com o mínimo de interrupções e carga cognitiva controlada.

### Observações
Este framework é amplamente aceito como o padrão-ouro nos artigos analisados para evitar a "produtividade espúria" (aceleração superficial que esconde redistribuição de esforço). A autora mais influente citada é **Nicole Forsgren**.
