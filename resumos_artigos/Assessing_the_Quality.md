### Do que se trata este artigo?

Pesquisadores da PUC Minas testaram três sistemas de inteligência artificial amplamente usados — ChatGPT, Gemini e Claude — para descobrir qual deles escreve código de computador de melhor qualidade. O objetivo não era apenas saber qual acerta mais as respostas, mas entender se o código produzido é fácil de manter, rápido de executar e livre de problemas estruturais ocultos.

---

### O que eles descobriram?

**O Gemini foi o mais certeiro.** Dos 527 problemas testados, o Gemini resolveu 514 corretamente — o melhor resultado entre os três. Ele também foi o mais rápido na execução: seus programas rodaram em média em 35,6 milissegundos, contra 41,5 do ChatGPT. Na prática, isso significa que, se uma empresa usasse o Gemini para gerar código de produção (código que roda em servidores reais), teria mais chance de receber uma solução funcional logo de início, e ela seria mais veloz.

**O Claude produziu o código mais limpo e organizado.** Uma métrica importante em programação é a "complexidade ciclomática" — grosso modo, quantos caminhos diferentes a execução de um programa pode tomar. Quanto mais alta, mais difícil é entender, testar e corrigir o código. O Claude registrou a menor média (7,67), contra 8,45 do ChatGPT. Além disso, o Claude gerou menos "code smells" — nome técnico para padrões ruins no código que, embora não causem erros imediatos, criam dor de cabeça futura para quem precisar modificar ou corrigir o programa. O Claude tinha em média 4,88 problemas desse tipo por solução, enquanto ChatGPT e Gemini chegaram a quase 6. O Claude também precisou de menos tentativas para chegar a uma resposta correta, o que indica que suas soluções tendem a ser mais consistentes desde o início.

**O ChatGPT resolveu mais tipos diferentes de problemas e foi o mais eficiente no uso de memória.** Seus programas consumiram menos memória (63,2 KB em média, o menor dos três). Para aplicações que precisam rodar em dispositivos com recursos limitados, isso pode ser uma vantagem real. Porém, o ChatGPT foi o que gerou código estruturalmente mais problemático — mais complexo e com mais "code smells" — o que significa maior custo de manutenção a longo prazo.

**Nenhum modelo é perfeito para todos os cenários.** As diferenças entre os modelos foram mais acentuadas em problemas que exigem raciocínio elaborado, como programação dinâmica e algoritmos gulosos. Já em tarefas mais diretas — manipulação de listas e texto, por exemplo — os três performaram de forma parecida.

---

### Conclusão final

Não existe uma IA "melhor" de forma absoluta: o Gemini é a escolha mais acertada quando o objetivo é resolver problemas rapidamente e com alta taxa de sucesso; o Claude é preferível quando a qualidade e a facilidade de manutenção do código importam mais; e o ChatGPT se destaca quando se busca variedade de soluções com baixo consumo de memória — desde que se esteja disposto a revisar o resultado com mais cuidado.
