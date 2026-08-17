# AULA 002

# Respostas — Capítulo 2 de Sebesta

## 1. A genealogia das linguagens não é uma escada de progresso

A genealogia das linguagens de programação não pode ser vista como uma escada de progresso, na qual uma linguagem nova simplesmente substitui a anterior. As linguagens são criadas para atender a diferentes necessidades e domínios de aplicação, por isso uma linguagem antiga pode continuar sendo utilizada mesmo depois do surgimento de alternativas mais modernas. Além disso, uma linguagem pode influenciar outra ao incorporar conceitos desenvolvidos anteriormente, sem necessariamente eliminar sua antecessora.

Dois fatores históricos explicam isso. O primeiro é a existência de **diferentes áreas de aplicação**, pois uma linguagem pode ser mais adequada para determinado tipo de problema do que outra. O segundo é o **legado das linguagens existentes**, como programas, bibliotecas, ferramentas e conhecimento acumulado pelos programadores. Assim, mesmo que uma nova linguagem apresente vantagens, o custo de abandonar sistemas antigos pode ser muito alto. Portanto, a história das linguagens é marcada por influências e coexistência, e não por substituições sucessivas.

## 2. Importância do Plankalkül

O Plankalkül é importante para a história das linguagens de programação porque, apesar de não ter sido implementado em sua época, seu projeto antecipou várias características que posteriormente se tornariam comuns em linguagens de programação. Desenvolvido por Konrad Zuse, o Plankalkül mostrou que conceitos de linguagens de alto nível já estavam sendo imaginados antes mesmo de existirem condições práticas para implementá-los.

Entre os recursos antecipados pelo Plankalkül estão **estruturas de dados, tipos de dados, atribuição, arrays e estruturas de controle**, como condicionais. Um desses recursos, as estruturas de dados, possui grande importância porque permite organizar e manipular informações de maneira estruturada, em vez de trabalhar apenas com valores isolados. Isso é fundamental nas linguagens modernas, pois permite representar problemas complexos de forma mais organizada. Dessa maneira, o Plankalkül é relevante principalmente por sua importância conceitual e histórica.

## 3. Short Code, Speedcoding e A-0/A-1/A-2

Short Code, Speedcoding e os sistemas A-0, A-1 e A-2 surgiram como tentativas de diminuir a dificuldade de programar diretamente em linguagem de máquina. O **Short Code** utilizava uma forma mais simples e simbólica de representar operações, facilitando a escrita dos programas, embora dependesse de interpretação. O **Speedcoding**, desenvolvido para o IBM 701, também buscava facilitar a programação, fornecendo operações mais próximas da forma como os programadores pensavam e reduzindo a quantidade de código necessário. Já os sistemas **A-0, A-1 e A-2**, associados ao trabalho de Grace Hopper, procuravam facilitar a programação por meio da utilização e reutilização de rotinas, introduzindo uma forma inicial de tradução de instruções mais abstratas.

Não seria correto chamar esses sistemas simplesmente de compiladores modernos porque eles ainda não possuíam todas as características dos compiladores atuais. Alguns utilizavam interpretação, outros dependiam de bibliotecas de rotinas e seus mecanismos de tradução eram bastante limitados. Eles representam, portanto, etapas intermediárias da evolução entre a programação em linguagem de máquina e os compiladores de linguagens de alto nível que surgiriam posteriormente.

## 4. O projeto Fortran e a aceitação da tradução automática

O projeto Fortran precisou convencer os programadores de que um programa traduzido automaticamente poderia apresentar desempenho comparável ao de um programa escrito manualmente em linguagem de máquina. Na época, os computadores possuíam recursos limitados e havia a ideia de que somente um programador experiente, escrevendo diretamente em baixo nível, conseguiria produzir programas suficientemente eficientes. Por isso, para que Fortran fosse aceito, seu compilador precisava gerar código com desempenho adequado.

A principal vantagem do Fortran era permitir que os programadores escrevessem programas de maneira muito mais simples e produtiva, sem precisar controlar diretamente todos os detalhes da máquina. Isso reduzia o **custo e o tempo de programação**, mas essa vantagem só seria aceita se o desempenho não fosse prejudicado significativamente. Dessa forma, o sucesso do Fortran dependia do equilíbrio entre **eficiência do código gerado e produtividade do programador**. Quando ficou demonstrado que o compilador poderia produzir código eficiente, a utilização de uma linguagem de alto nível tornou-se muito mais atraente e o Fortran pôde ser adotado na computação científica.

## 5. Comparação entre Lisp e Fortran

Fortran e Lisp surgiram em contextos diferentes e foram projetadas para atender a necessidades distintas. O **Fortran** foi desenvolvido principalmente para a computação científica e numérica, tendo como foco a realização eficiente de cálculos matemáticos. Por isso, seus programas trabalham principalmente com números e estruturas adequadas ao processamento numérico, como arrays. O estilo de computação favorecido é, portanto, o cálculo numérico e a execução eficiente de operações matemáticas.

A **Lisp**, por outro lado, surgiu voltada para o processamento simbólico e para aplicações relacionadas à inteligência artificial. Sua representação de dados é baseada principalmente em **listas e símbolos**, permitindo manipular informações simbólicas de maneira bastante flexível. Lisp favorece operações sobre listas, processamento simbólico e o uso de recursos como recursão. Assim, enquanto Fortran foi projetada para tornar a computação numérica mais produtiva e eficiente, Lisp foi desenvolvida para facilitar a manipulação de símbolos e estruturas de dados complexas, mostrando que diferentes linguagens podem coexistir por atenderem a diferentes domínios.

## 10. Ortogonalidade, regularidade e simplicidade

Ortogonalidade é uma característica do projeto de uma linguagem que indica o quanto seus recursos podem ser combinados entre si de maneira consistente, sem criar regras especiais ou exceções. Uma linguagem ortogonal permite que diferentes construções sejam utilizadas juntas de forma previsível. O **ALGOL 68** é um exemplo de linguagem que buscou alto grau de ortogonalidade, permitindo combinar tipos, operadores e estruturas de maneira bastante regular.

Entretanto, **regularidade não significa necessariamente simplicidade**. O ALGOL 68 apresentava grande regularidade e muitos recursos que podiam ser combinados, mas justamente essa quantidade de possibilidades tornava a linguagem complexa para aprender e utilizar. Portanto, uma linguagem muito ortogonal não é automaticamente fácil de usar. A ortogonalidade facilita a compreensão das regras e reduz exceções, mas, quando existem muitos recursos e combinações possíveis, a linguagem ainda pode apresentar grande complexidade para o programador.

## 11. Influência de ALGOL, Pascal, C e Prolog

Uma cadeia de influência importante na história das linguagens pode ser representada por **ALGOL → Pascal → C**. O ALGOL teve grande influência no desenvolvimento das linguagens imperativas e introduziu conceitos importantes de estruturação de programas. Pascal foi desenvolvida posteriormente, recebendo forte influência de ALGOL e buscando oferecer uma linguagem estruturada, especialmente adequada ao ensino de programação. C também recebeu influência da tradição de ALGOL, principalmente em sua estrutura de controle, mas foi desenvolvida com forte preocupação com eficiência e programação de sistemas.

Essa linhagem é predominantemente **imperativa**, pois o programador descreve uma sequência de operações e mudanças de estado que devem ser realizadas. Prolog, por outro lado, segue uma proposta **declarativa e lógica**. Em vez de especificar detalhadamente como alcançar um resultado, o programador declara fatos e regras sobre determinado problema, e o sistema utiliza mecanismos de inferência para encontrar respostas. Assim, ALGOL, Pascal e C representam uma evolução de linguagens baseadas em procedimentos e comandos, enquanto Prolog apresenta uma forma diferente de expressar a solução, baseada em relações lógicas.

## 12. Base de conhecimento em Prolog

Uma pequena base de conhecimento em Prolog poderia ser representada, em linguagem natural, da seguinte forma: **João é estudante. Maria é estudante. Todo estudante é uma pessoa. Consulta: João é uma pessoa?** Em Prolog, os dois primeiros enunciados seriam fatos, a afirmação de que todo estudante é uma pessoa seria uma regra e a pergunta sobre João seria uma consulta.

Isso representa programação lógica porque o programa não apresenta uma sequência de instruções dizendo ao computador exatamente como descobrir a resposta. Em vez disso, ele descreve **fatos e relações**, e o sistema utiliza essas informações para realizar uma inferência. A partir do fato de que João é estudante e da regra de que todo estudante é uma pessoa, Prolog consegue concluir que João é uma pessoa. Portanto, não se trata apenas de armazenar dados, mas de representar conhecimento que pode ser utilizado para obter novas informações por meio de regras lógicas.

## 13. Ada e sistemas críticos

Ada foi desenvolvida a partir de requisitos relacionados a sistemas de grande escala, especialmente sistemas nos quais **confiabilidade e segurança** eram muito importantes. Em sistemas críticos, erros de programação podem causar consequências graves, por isso a linguagem precisava oferecer mecanismos que ajudassem o programador a detectar erros e organizar programas complexos. Nesse contexto, o sistema de tipos de Ada possui um papel importante, pois permite verificar de forma rigorosa a utilização dos dados e detectar determinados erros durante a compilação.

Os **pacotes** também contribuem para a organização e manutenção de sistemas grandes, permitindo dividir o programa em unidades bem definidas e separar interfaces de implementações. Já os mecanismos de **concorrência** são importantes porque muitos sistemas críticos precisam executar várias atividades simultaneamente, como controlar diferentes sensores, dispositivos ou processos. Dessa forma, tipos rigorosos, pacotes e concorrência contribuem para tornar os programas mais organizados, verificáveis e confiáveis, características essenciais no desenvolvimento de sistemas críticos.

## 14. Objetos em Smalltalk, C++ e Java

Em **Smalltalk**, os objetos são o elemento central da linguagem. Praticamente toda a computação é organizada em torno de objetos que recebem mensagens, e a orientação a objetos está profundamente integrada ao modelo da linguagem. **C++**, por sua vez, incorporou recursos de orientação a objetos a uma linguagem que já existia, o C. Dessa forma, C++ precisava manter grande compatibilidade com C, ao mesmo tempo em que acrescentava classes, herança, polimorfismo e outros recursos orientados a objetos. Essa preocupação com a compatibilidade contribuiu para a grande adoção da linguagem, mas também tornou seu projeto mais complexo.

**Java** também utiliza objetos como elemento fundamental, mas adotou uma estratégia diferente em relação à portabilidade. Em vez de depender diretamente do código de máquina de cada computador, Java utiliza uma **máquina virtual**, que executa o código intermediário produzido pelo compilador. Assim, um mesmo programa pode ser executado em diferentes sistemas que possuam uma máquina virtual Java compatível. Portanto, Smalltalk apresenta uma orientação a objetos mais integrada ao projeto da linguagem, C++ combina orientação a objetos com a herança de C, e Java combina orientação a objetos com uma estratégia voltada à portabilidade.

## 15. Java e a expansão da Web

A primeira aplicação de Java não foi a Web. A linguagem foi originalmente desenvolvida no contexto do projeto **Green**, da Sun, com o objetivo de ser utilizada em dispositivos eletrônicos e sistemas embarcados. Entretanto, o crescimento da Web criou um novo contexto no qual algumas características de Java se tornaram especialmente interessantes, principalmente sua portabilidade e o modelo de execução baseado em uma máquina virtual.

Com a expansão da Web, Java passou a ser associada à possibilidade de executar o mesmo código em diferentes plataformas, o que era uma vantagem importante em um ambiente formado por computadores e sistemas operacionais variados. Assim, uma mudança no contexto tecnológico fez com que uma linguagem inicialmente criada para outro objetivo encontrasse uma aplicação de grande importância. Esse caso mostra que o sucesso de uma linguagem não depende apenas de suas características originais, mas também de **mudanças nas necessidades do mercado e da tecnologia**, que podem criar novos usos e impulsionar sua adoção.
