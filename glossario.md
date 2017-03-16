### Glossário da Computação Concorrente, Paralela e Distribuída

Este glossário foi elaborado pelos alunos do curso de MAC5742-0438, no
primeiro semestre de 2015.

### A

#### Apache Hama

O Apache Hama é um framework de propósito geral, escrito em Java, baseado no
modelo Bulk Synchronous Parallel (BSP), que roda em cima do Apache Hadoop e
permite a criação de algoritmos massivamente paralelos para computação
científica, em diversas áreas, como matrizes, grafos e aprendizado de máquina.

#### Apache Spark

De forma geral, o Apache Spark é uma engine rápida, escrita em Scala, para
processamento de grandes volumes de dados em um cluster de computadores. Scala
é uma liguaguem funcional que roda na JVM. Surgiu como um projeto da AMPLab de
Berkeley em 2009, tendo como principal criador Matei Zaharia em sua tese de
doutorado.

#### Apache Storm

O Apache Storm é uma ferramenta distribuída para computação em tempo-real. Ele
pode ser utilizado em áreas como realtime analytics, machine learning e
computação contínua, conseguindo consumir e processar grande quantidade de
dados e também oferecer confiabilidade nesse processamento. Tem como pontos
importantes a tolerância a falhas e a escalabilidade semelhante ao Apache
Hadoop, e também a possibilidade de se utilizar qualquer linguagem no
desenvolvimento do seu código Storm.

#### ARM

Arquitetura ARM (primeiramente Acorn RISC Machine, posteriormente Advanced RISC
Machine) é uma arquitetura de processador de 32 bits usada principalmente em
sistemas embarcados. São processadores que visam a simplificação das
instruções, com o intuito de atingir a máxima eficiência por ciclo, podendo
realizar tarefas menores com ciclos mais curtos, e uma maior ordenação das
operações dentro do núcleo de processamento. Muito usada na indústria e na
informática, seu desenvolvimento se deu visando obter o melhor desempenho
possível, com a limitação de ser simples, ocupar pouca área e ter baixo consumo
de energia.

#### Autotuning

Autotuning, significando ajuste automático consiste no impacto das
características de arquiteturas, problemas e algoritmos em um domínio para
definir um espaço de busca que pode ser explorado por diferentes técnicas de
optimização ou aprendizado de máquina.

### C

#### Charm++

Charm++ é uma ferramenta de HPC desenvolvida pela Universidade de Illinois que
busca aumentar a produtividade de desenvolvedores que trabalham com esse tipo
de aplicações. Charm++ foi desenvolvida em cima da linguagem C++, utilizando o
paradigma de orientado a objetos com o objetivo de fornecer portabilidade
eficiente, tolerância a latência, balanceamento de carga dinâmico, reuso e
modularidade.

#### Codelet

Descreve um kernel computacional que pode ser implementado em múltiplas
arquiteturas como CPU e dispositivos CUDA e OpenCL.

#### Computação distribuída

Um sistema distribuído é um sistema de software onde os componentes estão
localizados numa rede de computadores, se comunicando e coordenando ações por
troca de mensagens.

#### Computação paralela

Computação paralela é uma forma de computação onde diversos cálculos são
executados simultaneamente, operando sobre o princípio que um grande problema
pode ser dividido em problemas menores, que então podem ser resolvidos de forma
concorrente ("em paralelo").

#### Computação Quantica

A ideia Computação Quântica foi introduzida por Richard Feynman no artigo
"Simulating Physics with Computers" onde o autor discute o problema em simular
fenômenos quânticos com computadores clássicos em termos de desempenho. Para
simular um sistema quântico com n variáveis seria necessária a quantidade
proibitiva de 2n variáveis num computador comum! Logo a maneira natural de
simular um sistema quântico deve ser justamente utilizar um computador que
consiga tirar proveito das propriedades quânticas.

#### CUDA

CUDA é uma plataforma de computação paralela e um modelo de programação
inventados pela NVIDIA. Ela permite aumentos significativos de performance
computacional ao aproveitar a potência da unidade de processamento gráfico
(GPU).

### D

#### Deep Learning

A ideia do deep learning é que o aprendizado seja feito como o cérebro humano
faria. Deep learning utiliza algoritmos de aprendizado não­ supervisionado.
Isto é, dada uma entrada de características do que se deseja classificar, sem
nenhuma informação prévia de dados similares já classificados, e o algoritmo
define uma classificação para a entrada. A principal diferença entre machine
learning tradicional que utiliza algoritmos  não­ supervisionados e deep
learning é o método utilizado para extração de características  relevantes para
a classificação. Deep learning está intimamente ligado à big data

### G

#### Gargalo de Von Neumann

(em inglês Von Neumann Bottleneck) nome dado, na Arquitetura de Von Neumann, à
limitação da taxa de transferência entre a CPU e a memória em comparação com a
quantidade de memória. Esta transferência é menor do que a taxa com que o
processador consegue trabalhar e menor do que a quantidade de memória em geral
disponível. Isto faz com  que a CPU seja forçada a esperar por dados que
precisam ser transferidos para ou a partir da memória. 

#### Go Lang

Em 2007 foi criada a linguagem de programação Go em resposta a alguns problemas
enfrentados por ele ao desenvolver sistemas que trabalham com a sua
infraestrutura. Estes problemas surgiram a partir do uso de processadores
multinúcleos, sistemas distribuídos em redes, computação massiva e modelo de
computação web, que apesar de tornar a computação muito mais potente, também
agregou uma série de complexidades.
Características como linguagem compilada, garbage-collector, estaticamente
tipada, lidar com concorrência, síntaxe simples dentre outras, foram reúnidas
nesta nova linguagem denominada Go!

#### Google Brain

O projeto de inteligência artificial usando deep learning da Google, o Google
Brain, já tem mostrado resultados desde 2012. Em um dos primeiros trabalhos
publicados pela equipe da Google liderada por Andrew Ng em 2012, eles relataram
os primeiros resultados que o projeto obteve utilizando deep learning. Este
trabalho foi uma prova de conceito, pois eles 
queriam determinar se era possível criar um algoritmo para reconhecimento de faces e outros objetos com base em imagens não catalogadas e sem prover nenhum tipo de informação para o algoritmo se a imagem continha ou não uma face. 

#### Graph500

É uma nova lista que tenta classificar supercomputadores usando aplicações
reais de grafos e redes neuronais. 
A lista Graph 500 tem seu origem nos resultados obtidos por investigações feitas por pesquisadores do laboratório Sandia dos E.E.U.U, em particular do Richard Murphy. Em primeiro lugar, Richard Murphy pesquisou a diferença no padrão de acesso a memória de benchmarks focados em operações de ponto-flutuante, em operações com inteiros e outras aplicações usadas no laboratório Sandia [4]. Nestes experimentos se analisam características como a localidade espacial, localidade temporal e a quantidade de dados diferentes acessados por cada aplicação.

#### Grau de paralelismo

Número máximo de processadores que podem estar computacionalmente ativos em um
determinado instante de tempo, durante a execução de um programa.

### I

#### INRIA

Institut national de recherche en informatique et en automatique  (French
Institute for Research in Computer Science and Automation)

### J

#### Julia

O desenvolvimento de Julia começou em 2009 e uma versão de código aberto foi
divulgado em fevereiro de 2012. Seus criadores Jeff Bezanson, Stefan Karpinski,
Viral Shah e Alan Edelman alegam que o desenvolvimento de Julia veio da
necessidade de uma linguagem que agrupasse o melhor uma s ́erie de linguagens
excelentes para alguns aspectos da computação científica, mas não tão boas para
outros aspectos.

### I

#### LLVM

O LLVM (anteriormente Low Level Virtual Machine) é uma infraestrutura de
compilação projetada como um conjunto de bibliotecas reutilizáveis com
interfaces bem definidas. É escrito em C++ e é projetado para otimizar o código
em tempo de compilação, ligação (link) e execução de programas escritos em
linguagens de programação arbitrárias.  Originalmente implementando C e C++,
sua arquitetura permitiu a expansão para outras linguagens posteriormente,
incluindo Objective-C, Fortran, Ada, Haskell, bytecode Java, Python, Ruby,
ActionScript, GLSL, Julia, entre outras.

### M

#### Memcapacitor

Componente eletrônico de duplo terminal que permite armazenar carga elétrica e
mudar sua capacitância dependendo das últimas tensões aplicadas sobre ele. De
forma semelhante aos memristores, os memcapacitores podem processar e memorizar
dados, além de apresentar a vantagem de permitirem a reciclagem de energia.

#### Memcomputação

Termo originado de memória + computação. Modelo de computação que defende que é
possível processar e realizar armazenamento nos mesmos componentes físicos, sem
que haja interferência entre o processamento e o armazenamento de dados. A
proposta inicial foi desenvolvida por  Leon O. Chua em 1971, ao criar o
conceito de componente chamado de memristor. Posteriormente, em Dezembro de
2008, Chua propôs outros hipotéticos componentes chamados de memcondutor e
memindutor, baseados na equação geral dos sistemas memristivos. Juntos, estes
três componentes (memristor, memcapacitor, memindutor) são chamados de
memelementos.

#### Memristor

Componente eletrônico passivo de duplo terminal, que altera o seu estado
(resistência) conforme a quantidade de carga elétrica que flui através dele. O
memristor é definido também como um componente eletrônico passivo de duplo
terminal, mas que altera o seu estado (resistência) conforme a quantidade da
carga elétrica que flui em si (apresentando como comportamento um ciclo de
histerese pinçado no plano voltagem-corrente). Quando a corrente elétrica flui
em uma direção
através do circuito, a resistência aumenta. Porém se a corrente elétrica flui em direção contrária, a resistência diminui.

#### Message Passing Interface

É uma biblioteca de comunicação padrão na computação paralela e distribuída.
Esse padrão é baseado no consenso do Fórum MPI, que tem mais de 40 organizações
participantes, incluindo fornecedores, pesquisadores, desenvolvedores de
software, bibliotecas e usuários.
No padrão MPI, uma aplicação é constituída por um ou mais processos que se comunicam, acionando-se funções para o envio e recebimento de mensagens entre os processos. Inicialmente, na maioria das implementações, um conjunto fixo de processos é criado. Porém, esses processos podem executar diferentes programas. Por isso, o padrão MPI é algumas vezes referido como MPMD (multiple program multiple data).

#### Modelo BSP

O modelo BSP (Bulk Synchronous Parallel) é um modelo de computação paralela
introduzido por Leslie Valiant em 1990. O modelo BSP oferece uma simples
abstração de arquiteturas paralelas. Onde um processador está encarregado de
distribuir tarefas a um conjunto de processadores que executam computações
locais e se comunicam de forma global, caso necessário. Ao terminarem a tarefa
os processadores aguardem os outros numa barreira de sincronismo, para poderem
executar a próxima tarefa. Isto é chamado como um super-passo (do inglês
superstep). Um algoritmo BSP consiste de um número arbitrário de super-passos.
Todos os processadores são sincronizados entre super-passos.

#### Modelo CGM

Dehne et al. no ano 2002 estudaram o problema do desenho de algoritmos
geométricos paralelos escaláveis para os casos de granularidade grossa ou
coarse grained. O modelo CGM  é muito ótimo ou ao menos eficiente para um
grande rango de problemas do radio n/p, com n o tamanho do problema e p o
número de processadores.

#### Modelo LogP

O modelo LogP foi proposto por David Culler  et. al. no 1993 e foi nomeado LogP
propriamente pelas variáveis do modelo. O s autores perceberam que o modelo
PRAM não é realista devido a la falta de parâmetros para representar os custos
de comunicação nas aplicações, especialmente para aplicações distribuídas. A
seguir serão explicados cada um dos parâmetros usados para descrever um sistema
paralelo segundo o modelo LogP:

- L: Limite superior da latência, ou retraso, incurrida na comunicação de uma
  mensagem desde uma fonte a um processador destino.

- o: Overhead - tempo durante o qual um processador está ocupado no envio o
  recebo de uma mensagem, durante esse tempo ele não pode fazer computações.

- g: Gap - Tempo mínimo entre transmissões de mensagens consecutivas ou entre o
  recebimento de mensagens consecutivas; o reciproco de $g$ corresponde à
  largura de banda do processador.

- P: Número de Processadores.

#### Modelo PRAM

O mode PRAM (Parallel Random Access Machine) foi divulgado por Steven Fortune e
James Wyllie em 1976. O Modelo PRAM é uma extensão simples da computação
paralela do modelo RAM para a computação sequencial. Esse modelo consiste de um
conjunto infinito de processadores, uma memória centralizada global e infinita,
um conjunto de registradores de entrada e um programa finito representado pela
máquina de Turing ou a aplicação paralela. 

A vantagem do PRAM é sua simplicidade e sua similaridade ao modelo sequencial
de Von Neuman. O processador pode ler o escrever somente uma endereço em um
tempo. O custo de escrita é igual ao custo de leitura, e também é igual o custo
de qualquer operação executada pelo processador. Porém de sua simplicidade,
devido ao incremento da brecha entre o processamento e à velocidade de
comunicação, esse modelo tornou se cada dia mais irrealista. 

### P

#### Program Profiling

É um método para a análise dinâmica da execução de um programa. Pode-se medir,
por exemplo, o desempenho, o uso de memória, o uso de instruções específicas, e
a frequência e duração de chamadas de função. A ferramenta que realiza o
Profiling é chamada de Profiler.

#### Promises

Como definição ao geral de promise pode-se dizer que se trata de uma abstração
para programação concorrente que permite a realização ao de chamadas
assíncronas de funções, composição de chamadas e controle de execuções.  Não há
padronização ao quanto à terminologia utilizada pelas implementações nas
diferentes linguagens de programação. De acordo com essa definição, pode-se
dizer que promise  é uma referência que armazenar ́a o resultado da execução ao
de um deferred, que  ́e uma computação assíncrona ainda não concluída.

### R

#### RamCoud

O projeto RAMCloud é um software que roda em um cluster de servidores comuns
(commodity servers). Esse cluster é composto de uma coleção de servidores de
armazenamento e um coordenador. Cada servidor de armazenamento é dividido em
duas componente principais: a componente principal ou master é responsável por
atender às requisições de leitura e escrita; a componente secundária ou backup
é responsável por manter em disco uma cópia dos dados de outras componentes
principais de outros servidores.

#### Rust

Rust é uma linguagem de programação bem recente. A versão 1.0 que promete a
estabilidade sintática e semântica da linguagem no futuro foi liberada agora em
maio de 2015.  Começado como projeto particular do funcionário da Mozilla
Graydon Hoare e depois apoiado pela Mozilla para ajudar no desenvolvimento de
uma nova browser engine "Servo"[ser] Rust foi anunciada pela primeira vez em
2010.

A ideia principal que levou a criação de Rust é a ideia de uma linguagem de
programação para o desenvolvimento de sistemas (de baixo nível) que tenha um
modelo de memória seguro e que inclua também elementos modernos como por
exemplo pattern matching, tipos algébricos, funções de ordem maior (closures) e
genéricos. Os princípios gerais que guiam o desenvolvimento da linguagem são:
não deixar a segurança de memória ser comprometida, abstrações não devem custar
nada no tempo de execução, praticidade é a chave[des].

### S

#### Scala

A linguagem de programação Scala é uma linguagem multi-paradigma, oferecendo
recursos de programação orientada a objetos e de programação funcional. Ela é
compilada para bytecode Java para interpretação pela JVM, podendo também rodar
no Android, e tem desempenho similar ao de Java.As principais ferramentas são
software livre, disponíveis sob licenças permissivas (Apache e BSD). Classes
escritas em Java e em Scala podem ser misturada livremente, o que permite o uso
de bibliotecas, arcabouços e outras ferramentas Java existentes diretamente em
Scala. Ao mesmo tempo, ferramentas desenvolvidas em Scala podem ser utilizadas
em Java.

#### SLURM 

SLURM, ou Simple Linux Utility for Resource Management ("utilitário simples
para gerenciamento de recursos em Linux", em tradução livre), é um sistema de
software livre, sob licença GNU GPLv2, para escalonamento de tarefas. O Slurm
começou a ser desenvolvido em 2002 como colaboração o entre o Lawrence
Livermore National Laboratory, a Linux NetworX, a HP e o Groupe Bull. Sua
principal motivação foi estabelecer a existência de um bom gerenciador de
recursos livre e com desenvolvimento suportado primariamente por entidades
interessadas em computação de alto desempenho.

Hoje em dia é comum ver seu nome grafado simplesmente como Slurm, em minúsculas
e sem expansão do acrônimo, possivelmente em decorrência do fato de que
atualmente ele pode ser instalado em diversos sistemas operacionais modernos
baseados em Unix, como a família BSD, Mac OS X e Solaris, e não requer
modificação no kernel para sua instalação. É desenvolvido em linguagem C e
conta com mais de 500 mil linhas de código.

#### Speedup

Fator que representa o ganho de velocidade de  processamento de uma aplicação
quando executada por n processadores. Quanto maior o valor, mais rápido o
código paralelo é em comparação com o mesmo código não-paralelizado. A equação
básica de speedup é:  S_n=T_s/T_n, na qual S_n é o valor do speedup, T_s é o
tempo de execução do código serial (isto é, não-paralelizado) e  T_n é o tempo
de execução do mesmo código paralelizado. No entanto, independentemente da
quantidade de processadores utilizados, o valor de speedup é limitado (podendo
ser predito pela Lei de Amdahl).

#### StarPU

Uma biblioteca de programação para arquiteturas híbridas.

### T

#### Task

Consiste na aplicação de um Codelet em um conjunto de dados.

#### Tempo sequencial

Tempo gasto por um programa quando executado em um único processador da máquina
em estudo.

#### Thread

Linha de execução, é uma forma de um processo dividir a si mesmo em duas ou
mais tarefas que podem ser executadas concorrentemente.  Cada thread tem o
mesmo contexto de software e compartilha o mesmo espaço de memória (endereçado
a um mesmo processo-pai), porém o contexto de hardware é diferente. Sendo assim
o overhead causado pelo escalonamento de uma thread é muito menor do que o
escalonamento de processos. Entretanto, algumas linguagens (C, por exemplo) não
fornecem acesso protegido à memória nativa (sua implementação fica a cargo do
programador ou de uma biblioteca externa) devido ao compartilhamento do espaço
de memória.

#### Tuning

Tuning, significando ajuste, é uma técnica usada para o melhoramento e
otimização de aplicações informáticas. Tuning é a melhoria do desempenho de um
sistema, sendo tipicamente um sistema computacional. A motivação para tal
atividade quase sempre é um problema de desempenho. 

### U

#### Unidade de Processamento Gráfico

Um processador dedicado especialmente para a renderização de gráficos em tempo
real.  Ao contrário das CPUs, possuem um número bem maior de núcleos de
processamento, criados para desempenhar um grande número de tarefas
paralelamente. Atualmente, as três maiores fabricantes de GPUs são a Intel, a
NVIDIA e a ATI.
