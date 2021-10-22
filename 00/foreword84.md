# Prefácio de Estrutura e Interpretação de Programas de Computador, 1984

Educadores, generais, nutricionistas, psicólogos e programa de pais. Exércitos, estudantes e algumas sociedades são programados. Um ataque a grandes problemas emprega uma sucessão de programas, muitos dos quais surgem no caminho. Esses programas estão repletos de problemas que parecem ser específicos ao problema em questão. Para apreciar a programação como uma atividade intelectual em si mesma, você deve recorrer à programação de computadores; você deve ler e escrever programas de computador – muitos deles. Não importa muito sobre o que os programas tratam ou quais aplicativos eles atendem. O que importa é quão bem eles executam e quão suavemente eles se encaixam com outros programas na criação de programas ainda melhores. O programador deve buscar a perfeição da peça e a adequação da coleção. Neste livro, o uso de "programa" está focado na criação, execução e estudo de programas escritos em um dialeto do Lisp para execução em um computador digital. Usando Lisp, restringimos ou limitamos não o que podemos programar, mas apenas a notação para nossas descrições de programa.

Nosso tráfego com o assunto deste livro nos envolve com três focos de fenômenos: a mente humana, coleções de programas de computador e o computador. Todo programa de computador é um modelo, incubado na mente, de um processo real ou mental. Esses processos, decorrentes da experiência e do pensamento humanos, são imensos em número, intrincados em detalhes e, a qualquer momento, apenas parcialmente compreendidos. Eles são modelados para nossa satisfação permanente raramente por nossos programas de computador. Assim, embora nossos programas sejam coleções discretas de símbolos cuidadosamente elaboradas à mão, mosaicos de funções interligadas, eles evoluem continuamente: nós os mudamos conforme nossa percepção do modelo se aprofunda, amplia, generaliza até que o modelo finalmente atinge um lugar metaestável dentro de outro modelo com o qual nós lutamos. A fonte da alegria associada à programação de computador é o desdobramento contínuo na mente e no computador de mecanismos expressos como programas e a explosão de percepção que eles geram. Se a arte interpreta nossos sonhos, o computador os executa sob a forma de programas!

Com todo o seu poder, o computador é um mestre de tarefas severo. Seus programas devem ser corretos, e o que desejamos dizer deve ser dito com precisão em cada detalhe. Como em qualquer outra atividade simbólica, nos convencemos da verdade do programa por meio do argumento. O próprio Lisp pode receber uma semântica (outro modelo, a propósito), e se a função de um programa pode ser especificada, digamos, no cálculo de predicados, os métodos de prova da lógica podem ser usados ​​para fazer um argumento de correção aceitável. Infelizmente, conforme os programas se tornam grandes e complicados, como quase sempre acontece, a adequação, consistência e correção das próprias especificações tornam-se abertas a dúvidas, de modo que argumentos formais completos de correção raramente acompanham programas grandes. Uma vez que grandes programas crescem de pequenos, é crucial que desenvolvamos um arsenal de estruturas de programa padrão de cuja exatidão temos certeza – nós os chamamos de expressões idiomáticas – e aprendamos a combiná-los em estruturas maiores usando técnicas organizacionais de valor comprovado. Essas técnicas são tratadas em detalhes neste livro, e entendê-las é essencial para a participação no empreendimento prometeico chamado programação. Mais do que qualquer outra coisa, a descoberta e o domínio de técnicas organizacionais poderosas acelera nossa capacidade de criar programas grandes e significativos. Por outro lado, uma vez que escrever programas grandes é muito trabalhoso, somos estimulados a inventar novos métodos para reduzir a massa de funções e detalhes a serem ajustados em programas grandes.

Ao contrário dos programas, os computadores devem obedecer às leis da física. Se eles desejam ter um desempenho rápido – alguns nanossegundos por mudança de estado – eles devem transmitir elétrons apenas a pequenas distâncias (no máximo 1½ pés). O calor gerado pelo grande número de dispositivos tão concentrados no espaço deve ser removido. Uma requintada arte de engenharia foi desenvolvida com equilíbrio entre a multiplicidade de funções e a densidade de dispositivos. Em qualquer caso, o hardware sempre opera em um nível mais primitivo do que aquele em que desejamos programar. Os processos que transformam nossos programas Lisp em programas de "máquina" são eles próprios modelos abstratos que programamos. Seu estudo e criação fornecem uma grande compreensão dos programas organizacionais associados à programação de modelos arbitrários. É claro que o próprio computador pode ser modelado dessa forma. Pense nisso: o comportamento do menor elemento físico de troca é modelado pela mecânica quântica descrita por equações diferenciais cujo comportamento detalhado é capturado por aproximações numéricas representadas em programas de computador executados em computadores compostos de ...!

Não é apenas uma questão de conveniência tática identificar separadamente os três focos. Mesmo que, como dizem, esteja tudo na cabeça, essa separação lógica induz uma aceleração do tráfego simbólico entre esses focos cuja riqueza, vitalidade e potencial são excedidos na experiência humana apenas pela evolução da própria vida. Na melhor das hipóteses, os relacionamentos entre os focos são metaestáveis. Os computadores nunca são grandes ou rápidos o suficiente. Cada avanço na tecnologia de hardware leva a empresas de programação mais massivas, novos princípios organizacionais e um enriquecimento de modelos abstratos. Todo leitor deve se perguntar periodicamente "Para que fim, para que fim?" – mas não pergunte com muita frequência, para não deixar de lado a diversão da programação para a prisão de ventre de uma filosofia agridoce.

Entre os programas que escrevemos, alguns (mas nunca o suficiente) executam uma função matemática precisa, como classificar ou encontrar o máximo de uma sequência de números, determinar a primalidade ou encontrar a raiz quadrada. Chamamos esses programas de algoritmos, e muito se sabe sobre seu comportamento ótimo, particularmente com respeito aos dois parâmetros importantes de tempo de execução e requisitos de armazenamento de dados. Um programador deve adquirir bons algoritmos e expressões idiomáticas. Mesmo que alguns programas resistam a especificações precisas, é responsabilidade do programador estimar, e sempre tentar melhorar, seu desempenho.

Lisp é um sobrevivente, tendo estado em uso por cerca de um quarto de século. Entre as linguagens de programação ativas, apenas Fortran teve uma vida mais longa. Ambas as linguagens têm suportado as necessidades de programação de importantes áreas de aplicação, Fortran para computação científica e de engenharia e Lisp para inteligência artificial. Essas duas áreas continuam a ser importantes, e seus programadores são tão dedicados a essas duas linguagens que Lisp e Fortran podem continuar em uso ativo por pelo menos mais um quarto de século.

Lisp muda. O dialeto Scheme usado neste texto evoluiu do Lisp original e difere deste último em vários aspectos importantes, incluindo escopo estático para vinculação de variável e permitindo que funções produzam funções como valores. Em sua estrutura semântica Scheme é tão parecido com Algol 60 quanto com os primeiros Lisps. Algol 60, que nunca mais será uma linguagem ativa, vive nos genes de Scheme e Pascal. Seria difícil encontrar duas linguagens que sejam a moeda de comunicação de mais duas culturas diferentes do que aquelas reunidas em torno dessas duas linguagens. Pascal é para a construção de pirâmides – estruturas imponentes, de tirar o fôlego, estáticas construídas por exércitos empurrando blocos pesados ​​no lugar. Lisp é para a construção de organismos – estruturas imponentes, de tirar o fôlego e dinâmicas construídas por esquadrões que ajustam miríades flutuantes de organismos mais simples no lugar. Os princípios de organização usados ​​são os mesmos em ambos os casos, exceto por uma diferença extraordinariamente importante: A funcionalidade exportável discricionária confiada ao programador Lisp individual é mais do que uma ordem de magnitude maior do que a encontrada nas empresas Pascal. Os programas Lisp aumentam as bibliotecas com funções cuja utilidade transcende o aplicativo que os produziu. A lista, a estrutura de dados nativa do Lisp, é a grande responsável por esse crescimento de utilidade. A estrutura simples e a aplicabilidade natural das listas se refletem em funções que são surpreendentemente nãoidiossincráticas. Em Pascal, a abundância de estruturas de dados declaráveis ​​induz uma especialização dentro de funções que inibe e penaliza a cooperação casual. É melhor ter 100 funções operando em uma estrutura de dados do que 10 funções operando em 10 estruturas de dados. Como resultado, a pirâmide deve permanecer inalterada por um milênio; o organismo deve evoluir ou perecer.

Para ilustrar essa diferença, compare o tratamento do material e dos exercícios deste livro com o de qualquer texto do primeiro curso usando Pascal. Não tenha a ilusão de que este é um texto digerível apenas no MIT, peculiar à raça ali encontrada. É precisamente o que um livro sério sobre programação Lisp deve ser, não importa quem seja o aluno ou onde seja usado.

Observe que este é um texto sobre programação, ao contrário da maioria dos livros Lisp, que são usados como preparação para o trabalho em inteligência artificial. Afinal, as preocupações críticas de programação da engenharia de software e da inteligência artificial tendem a se aglutinar à medida que os sistemas sob investigação se tornam maiores. Isso explica por que existe um interesse tão crescente pelo Lisp fora da inteligência artificial.

Como seria de se esperar de seus objetivos, a pesquisa em inteligência artificial gera muitos problemas de programação significativos. Em outras culturas de programação, essa enxurrada de problemas gera novas linguagens. De fato, em qualquer tarefa de programação muito grande, um princípio de organização útil é controlar e isolar o tráfego dentro dos módulos de tarefa por meio da invenção da linguagem. Essas linguagens tendem a se tornar menos primitivas à medida que nos aproximamos dos limites do sistema onde nós, humanos, interagimos com mais frequência. Como resultado, tais sistemas contêm funções complexas de processamento de linguagem replicadas muitas vezes. Lisp tem uma sintaxe e semântica tão simples que a análise pode ser tratada como uma tarefa elementar. Assim, a tecnologia de análise quase não desempenha nenhum papel em programas Lisp, e a construção de processadores de linguagem raramente é um impedimento para a taxa de crescimento e mudança de grandes sistemas Lisp. Finalmente, é essa mesma simplicidade de sintaxe e semântica que é responsável pelo fardo e pela liberdade suportados por todos os programadores Lisp. Nenhum programa Lisp de qualquer tamanho além de algumas linhas pode ser escrito sem estar saturado com funções discricionárias. Inventar e ajustar; ter ajustes e reinventar! Brindamos ao programador Lisp que escreve seus pensamentos entre parênteses.

*- Alan J. Perlis, New Haven, Connecticut*