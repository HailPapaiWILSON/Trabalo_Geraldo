**2 REFERENCIAL TEÓRICO I: FUNDAMENTOS DA INTELIGÊNCIA ARTIFICIAL E PRODUTIVIDADE**

A integração da Inteligência Artificial (IA) no desenvolvimento de software representa uma mudança de paradigma na Engenharia de Software, alterando a forma como sistemas são concebidos, implementados e mantidos (TOMAZ et al., 2026). Esta seção apresenta os conceitos fundamentais necessários para a compreensão desse fenômeno, abordando desde a evolução da IA até as métricas contemporâneas de produtividade.

**2.1 Inteligência Artificial**

A Inteligência Artificial é definida como uma classe de sistemas de aprendizado de máquina capazes de produzir resultados contextualmente coerentes a partir de padrões aprendidos em grandes conjuntos de dados (GURGUL et al., 2026). Historicamente, a pesquisa em Sistemas de Informação (IS) visualizava os artefatos de TI como ferramentas passivas controladas estritamente por agência humana (ZACHARIAS et al., 2026). No entanto, a evolução da área permitiu a transição de sistemas determinísticos, baseados em regras rígidas, para artefatos dotados de propriedades "agênticas" (ZACHARIAS et al., 2026).

Segundo Zacharias et al. (2026), a importância da IA reside na sua capacidade de simular processos cognitivos complexos, como abstração, inferência e síntese. Na economia moderna, o desenvolvimento de software tornou-se um domínio chave para entender e prever as capacidades da IA, servindo como um laboratório para a automação do trabalho intelectual (BECKER et al., 2025). A relevância estratégica da IA é impulsionada pela crença de que a velocidade de transformação de ideias em resultados de negócio é um diferencial competitivo crítico (BAKAL et al., 2025).

**2.2 Inteligência Artificial Generativa**

A Inteligência Artificial Generativa (GenAI) refere-se a uma subcategoria de tecnologia de IA que aprende com dados existentes para gerar autonomamente novos conteúdos significativos em diversos formatos, incluindo texto, imagens, áudio e código de programação (BRANDEBUSEMEYER et al., 2026; ZACHARIAS et al., 2026). Diferente da IA tradicional, que foca primordialmente em tarefas de classificação e regressão, a GenAI possui a capacidade de criar artefatos inéditos que não estão restritos a regras predefinidas (ZACHARIAS et al., 2026).

Zacharias et al. (2026) identificam quatro propriedades fundamentais que distinguem a GenAI das ferramentas tradicionais:
1.  **Propriedade Generativa:** Capacidade de criar soluções completas que não existiam anteriormente de forma predefinida.
2.  **Variabilidade:** Capacidade de gerar múltiplas saídas únicas a partir de um mesmo comando de entrada (*input*), suportando a exploração de diversas soluções.
3.  **Conversacionalidade:** Permite o engajamento interativo e sensível ao contexto por meio de linguagem natural.
4.  **Raciocínio Avançado:** Habilidade de interpretar informações ambíguas, inferir relacionamentos e gerar respostas logicamente consistentes.

A transição da IA tradicional para a generativa altera a relação entre humanos e máquinas de um modelo de "delegação" para um de "co-criação" (ZACHARIAS et al., 2026). Nesse cenário, o desenvolvedor deixa de ser um mero escritor de código para se tornar um supervisor e validador crítico de saídas geradas por parceiros digitais (ZACHARIAS et al., 2026; SIMKUTE et al., 2025 apud STRAY et al., 2025).

**2.3 Modelos de Linguagem de Grande Escala (LLMs)**

Os Modelos de Linguagem de Grande Escala (LLMs) são a tecnologia base que operacionaliza a IA Generativa moderna. Estes modelos são treinados em vastos conjuntos de dados, permitindo que sejam adaptados para uma ampla gama de tarefas de processamento de linguagem natural (TOMAZ et al., 2026). No contexto específico do desenvolvimento de software, modelos como os da série GPT, Claude e Gemini são treinados em grandes corpora de código provenientes de repositórios públicos, como o GitHub (CUI et al., 2025; BECKER et al., 2025).

O treinamento em dados públicos permite que o LLM aprenda práticas de codificação do mundo real, padrões de design e estilos em diversas linguagens de programação (CUI et al., 2025). O funcionamento geral baseia-se na análise do contexto fornecido pelo desenvolvedor — seja através de código existente ou comentários em linguagem natural — para gerar sugestões de trechos de código, documentação ou explicações (CUI et al., 2025). 

A relação entre LLMs e a geração de texto e código é intrínseca, pois os modelos tratam o código como uma forma de linguagem estruturada. Ferramentas integradas ao ambiente de desenvolvimento utilizam esses modelos para prever e completar sequências de caracteres, transformando a experiência de escrita de software em uma interação contínua entre o humano e o modelo (CUI et al., 2025; BAKAL et al., 2025).

**2.4 IA Generativa Aplicada ao Desenvolvimento de Software**

A aplicação da IA Generativa na Engenharia de Software estende-se por todo o Ciclo de Vida de Desenvolvimento de Software (SDLC), oferecendo o que a literatura denomina de "acessibilidades funcionais" (*functional affordances*) (ZACHARIAS et al., 2026). Tufano et al. (2026) mapearam uma taxonomia de 64 tarefas diferentes que desenvolvedores automatizam utilizando ferramentas como ChatGPT e GitHub Copilot.

As principais atividades auxiliadas incluem:
*   **Geração de Código:** Produção de *boilerplate code*, implementação de novas funcionalidades e prototipagem rápida (GURGUL et al., 2026; ZACHARIAS et al., 2026).
*   **Documentação:** Escrita de comentários de código, geração de arquivos README e especificações de API (TUfano et al., 2026; ZACHARIAS et al., 2026).
*   **Refatoração:** Sugestões para melhorar a estrutura e a manutenibilidade do código existente (TUfano et al., 2026).
*   **Depuração (*Debugging*):** Auxílio na localização de bugs, explicação de erros em *logs* e sugestões de correção (TUfano et al., 2026; GURGUL et al., 2026).
*   **Testes:** Geração automática de casos de teste unitário, integração e criação de dados sintéticos para testes (GURGUL et al., 2026; ZACHARIAS et al., 2026).

Exemplos de ferramentas citadas na literatura incluem o **GitHub Copilot**, **ChatGPT**, **Cursor**, **Amazon CodeWhisperer**, **Claude**, **Google Gemini/Bard** e **JetBrains AI Assistant** (GURGUL et al., 2026; CUI et al., 2025; ZACHARIAS et al., 2026). Tais ferramentas funcionam como "assistentes de codificação inteligentes" ou "parceiros de pareamento de IA" (*AI pair programmers*), operando tanto via interfaces de chat em navegadores quanto integradas diretamente às IDEs (*Integrated Development Environments*) (CUI et al., 2025; BAKAL et al., 2025).

**2.5 Produtividade na Engenharia de Software**

A produtividade em Engenharia de Software é um conceito complexo e multidimensional que tem sido objeto de estudo por décadas (STRAY et al., 2025). Tradicionalmente, é definida como a proporção entre a saída (*output*) e a entrada (*input*) de recursos (PETERSEN, 2011 apud STRAY et al., 2025). Contudo, métricas tradicionais focadas apenas em volume, como linhas de código (LoC), contagem de *commits* ou número de tarefas fechadas, são frequentemente criticadas por carecerem de contexto e validade (AFROZ et al., 2026; STRAY et al., 2025).

Para lidar com essa complexidade, a literatura contemporânea adota o framework **SPACE**, que propõe cinco dimensões para a avaliação da produtividade (FORSGREN et al., 2021 apud AFROZ et al., 2026):
1.  **Satisfação e Bem-estar (*Satisfaction and well-being*):** Percepção do desenvolvedor sobre seu trabalho e equipe.
2.  **Performance:** Resultados do processo de desenvolvimento, como velocidade de entrega e qualidade.
3.  **Atividade (*Activity*):** Volume de trabalho realizado (ex: *commits*, revisões de código).
4.  **Comunicação e Colaboração:** Como os desenvolvedores interagem e coordenam esforços.
5.  **Eficiência e Fluxo (*Efficiency and flow*):** Capacidade de progredir nas tarefas com o mínimo de interrupções.

A emergência da GenAI introduz a necessidade de distinguir entre o volume bruto de atividade e a "densidade de valor" do trabalho realizado (TOMAZ et al., 2026). Além disso, a literatura destaca o conceito de **DevEx** (*Developer Experience*), que foca na experiência centrada no desenvolvedor e como as ferramentas impactam o estado de fluxo e a carga cognitiva (NODA et al., 2023 apud BAKAL et al., 2025; BRANDEBUSEMEYER et al., 2026).

**2.6 Síntese do Referencial**

Os conceitos apresentados demonstram que a IA evoluiu de ferramentas passivas para sistemas generativos e agênticos, fundamentados em LLMs que possuem propriedades únicas de raciocínio e conversacionalidade (ZACHARIAS et al., 2026). A aplicação desses modelos na Engenharia de Software permite a automação de uma vasta gama de tarefas, desde a codificação rotineira até processos complexos de design e testes (TUfano et al., 2026). 

Essa transformação tecnológica impacta diretamente a produtividade, exigindo que as organizações transcendam métricas simplistas de volume e adotem frameworks holísticos como o SPACE (TOMAZ et al., 2026; AFROZ et al., 2026). A compreensão dessas bases fundamentais é essencial para analisar como o uso de ferramentas de IA generativa pode redefinir o papel do desenvolvedor e quais variáveis condicionam os ganhos reais de eficiência no desenvolvimento de software moderno.