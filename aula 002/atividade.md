### 1. A genealogia das linguagens não é uma escada de progresso.

A genealogia das linguagens não representa uma evolução linear em que uma linguagem simplesmente substitui a anterior. Linguagens diferentes surgiram para resolver problemas e atender a necessidades específicas, e muitas continuam sendo utilizadas mesmo depois do surgimento de linguagens mais novas.

Dois fatores históricos que permitem essa influência sem substituição são **a especialização por domínio** e **a compatibilidade com sistemas existentes**. Uma linguagem pode ser muito adequada para determinada área, como COBOL para aplicações comerciais, e continuar sendo utilizada. Além disso, empresas podem possuir grandes sistemas antigos, tornando muito caro ou arriscado substituí-los. Assim, uma linguagem nova pode influenciar outra ao incorporar suas ideias, sem necessariamente eliminar seu uso.

### 3. Short Code, Speedcoding e A-0/A-1/A-2

**Short Code** buscava facilitar a programação, permitindo representar operações de forma mais próxima da linguagem humana em vez de utilizar diretamente códigos de máquina. Porém, seu processamento era relativamente lento.

**Speedcoding**, desenvolvido para o IBM 701, também tinha o objetivo de facilitar a programação, utilizando abreviações e operações pré-programadas para reduzir o trabalho do programador.

Já os sistemas **A-0, A-1 e A-2**, associados a Grace Hopper, tinham como objetivo permitir que o programador utilizasse símbolos e nomes em vez de precisar escrever diretamente instruções de máquina. Eles ajudaram a desenvolver a ideia de tradução automática de programas.

Chamá-los simplesmente de **compiladores modernos** seria impreciso porque eram sistemas pioneiros, com recursos muito mais limitados. Eles não possuíam todas as características e mecanismos encontrados nos compiladores atuais, mas foram importantes para a construção do conceito de tradução automática de linguagens de programação.

### 7. COBOL e FLOW-MATIC

COBOL foi criada principalmente para o **processamento comercial**, portanto precisava ser compreensível para programadores e profissionais ligados às empresas. Por isso, sua sintaxe foi projetada para ser mais próxima da linguagem natural, facilitando a leitura dos programas.

A linguagem também possuía estruturas específicas para representar **registros e dados comerciais**, como informações de clientes, funcionários e transações. Isso combinava com a necessidade de processar grandes quantidades de dados organizados.

COBOL recebeu forte influência da **FLOW-MATIC**, criada por Grace Hopper. A FLOW-MATIC já utilizava comandos próximos da linguagem inglesa e influenciou a preocupação de COBOL com a legibilidade e com a descrição de operações de processamento de dados. Dessa forma, o domínio comercial e o público-alvo tiveram influência direta nas principais características de COBOL.

### 8. BASIC e PL/I

**BASIC** foi criada com o objetivo de tornar a programação mais acessível, especialmente para estudantes e usuários que não eram especialistas. Seu projeto priorizou a **simplicidade de aprendizado e de utilização**, mesmo que isso significasse abrir mão de alguns recursos encontrados em linguagens mais complexas.

**PL/I**, por outro lado, buscou ampliar o alcance da programação reunindo recursos de diferentes áreas. Ela procurava atender tanto aplicações científicas quanto comerciais, incorporando características de linguagens como FORTRAN e COBOL.

Assim, o compromisso de BASIC foi principalmente entre **simplicidade e poder de expressão**, enquanto PL/I buscou equilibrar **generalidade e complexidade**, tentando atender vários tipos de aplicações em uma única linguagem.

### 9. APL, SNOBOL e SIMULA 67

As três linguagens seguiram direções diferentes:

* **APL**: tinha como foco a **computação matemática e manipulação de arrays**. Sua principal contribuição foi uma notação extremamente compacta, permitindo realizar operações complexas com poucas expressões.
* **SNOBOL**: foi voltada principalmente para o **processamento e manipulação de textos e padrões**. Sua contribuição duradoura foi a força de seus mecanismos de reconhecimento e manipulação de padrões.
* **SIMULA 67**: tinha foco em **simulação de sistemas**. Sua contribuição mais importante foi o desenvolvimento de conceitos relacionados à **programação orientada a objetos**, especialmente classes, objetos e herança, que influenciaram diversas linguagens posteriores.

Portanto, cada uma contribuiu para uma área diferente: APL para arrays e matemática, SNOBOL para processamento de textos e SIMULA para a evolução da orientação a objetos.

### 13. Ada e sistemas críticos

Ada foi desenvolvida pensando principalmente em aplicações de grande escala e sistemas que exigiam **alta confiabilidade**, como sistemas militares e de tempo real. Por isso, seus recursos foram projetados para reduzir erros e facilitar a manutenção de programas complexos.

Seu sistema de **tipos** é rigoroso, permitindo detectar muitos erros durante a compilação. Os **pacotes** ajudam a organizar grandes sistemas em módulos, facilitando a manutenção e separando interfaces de implementações.

Além disso, Ada possui mecanismos de **concorrência**, importantes para sistemas que precisam executar várias atividades simultaneamente e responder dentro de determinados limites de tempo.

Esses recursos estão diretamente relacionados aos sistemas críticos, nos quais uma falha pode causar consequências graves. Assim, Ada priorizou **confiabilidade, organização e controle** em vez de apenas facilidade de programação.

### 14. Smalltalk, C++ e Java

Em **Smalltalk**, os objetos são o elemento central da linguagem. Praticamente toda a computação é organizada em torno de objetos que recebem mensagens, tornando a orientação a objetos uma característica fundamental da linguagem.

**C++** também incorporou a orientação a objetos, mas precisou manter uma forte relação com **C**. Por isso, permitiu utilizar recursos de programação orientada a objetos sem abandonar grande parte da estrutura e compatibilidade da linguagem C. Isso facilitou a adoção por programadores que já utilizavam C, mas também tornou a linguagem mais complexa.

**Java** adotou a orientação a objetos como parte fundamental de seu projeto e buscou principalmente a **portabilidade**. Em vez de depender diretamente do código de máquina de cada computador, os programas Java são executados pela máquina virtual Java (JVM), permitindo que o mesmo programa seja executado em diferentes plataformas.

Assim, Smalltalk priorizou a pureza da orientação a objetos, C++ buscou combinar orientação a objetos com a tradição de C, e Java priorizou orientação a objetos juntamente com portabilidade.

### 15. Java e a Web

A primeira aplicação de Java não estava relacionada diretamente à Web. A linguagem foi inicialmente desenvolvida para aplicações em dispositivos e sistemas embarcados, no projeto que deu origem à linguagem.

Com o crescimento da **Web**, porém, surgiu um novo contexto no qual as características de Java se tornaram muito interessantes. Sua portabilidade e o conceito de executar código por meio da máquina virtual permitiram que a linguagem fosse utilizada em diferentes computadores e ambientes.

Assim, a Web mudou o cenário e criou uma oportunidade para Java. Isso demonstra que o sucesso de uma linguagem não depende apenas de suas características técnicas: **mudanças no contexto tecnológico podem criar novos usos e aumentar muito a adoção de uma linguagem**.

### 17. C# comparada com Java e C++

C# foi criada no ambiente **.NET** como uma linguagem moderna, incorporando ideias de linguagens anteriores e procurando evitar alguns de seus problemas.

Uma decisão importante foi utilizar **gerenciamento automático de memória**, semelhante ao Java. Isso reduz a necessidade de o programador controlar manualmente a memória, diminuindo problemas como vazamentos de memória e erros de acesso.

Outra decisão foi oferecer recursos de orientação a objetos e recursos modernos mantendo uma relação com conceitos conhecidos de **C++**, mas com uma linguagem mais controlada e segura. C# procurou evitar algumas das complexidades e problemas de baixo nível de C++, enquanto oferecia recursos mais modernos.

Dessa forma, C# buscou combinar a produtividade e segurança associadas a linguagens como Java com recursos e familiaridade herdados da família C/C++, dentro da plataforma .NET.
