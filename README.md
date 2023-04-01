<center>

### PONTIFÍCIA UNIVERSIDADE CATÓLICA DE MINAS GERAIS
### INSTITUTO DE CIÊNCIAS EXATAS E INFORMÁTICA
### UNIDADE EDUCACIONAL EAD
</center>
<center>

### Bacharelado em Sistemas de Informação
</center>
<center>

<br><br><br><br><br><br><br>
### Nathália Lopes Soares Bispo<br>Marilia<br>João Marcos Magalhães Füzessy Teixeira<br>Daniel<br>Luiz Andrade<br>Matheus<br><br><br><br><br>

</center>

<center>

### MUSICIAN'S TOOL<br><br><br><br><br><br><br><br><br><br><br><br>

</center>

<center>

Belo Horizonte<br>
2023<br>
</center>
<center>

### Nathalia Lopes Soares Bispo<br>Marilia<br>João Marcos Magalhães Füzessy Teixeira<br>Daniel<br>Luiz Andrade<br>Matheus<br><br><br><br><br>
</center>
<center>

### MUSICIAN'S TOOL<br><br><br><br><br>
</center>
<blockquote> 

Trabalho de Software apresentado como
requisito parcial à aprovação na disciplina
Projeto: Aplicações Web
</blockquote>
<br><br>
<center>

### Professor: Marco Rodrigo Costa
</center>
<br><br><br><br><br><br><br><br><br><br><br>
<center>

Belo Horizonte<br>
2023<br><br><br><br><br>
</center>
<center>

# SUMÁRIO<br><br>

</center>

1. [Apresentação](#apresentacao)

   1.1. [Problema](#problema)
   
   1.2. [Objetivo do trabalho](#objetivo-do-trabalho)
   
   1.3. [Justificativa](#justificativa)
   
   1.4. [Público alvo](#publico-alvo)
   
2. [Requisitos](#requisitos)

   2.1. [Requisitos Funcionais](#requisitos-Funcionais)
   
   2.2. [Requisitos não funcionais](#requisitos-funcionais)
   
   2.3. [Restrições](#restricoes)
   
3. [Projeto da solução](#projeto-da-solucao)

4. [Metodologia de trabalho](#metodologia-de-trabalho)

5. [Implementação da solução](#implementacao-da-solucao)

6. [Avaliação da Aplicação](#avaliacao-da-Aplicacao)

7. [REFERÊNCIAS](#referencias)
<br><br><br><br>



## 1. Apresentação <a name="apresentacao"></a> 
<br>

Desde o som produzido por uma onda, pelo uivo do vento passando por entre as árvores, por animais e trovões, até o simples barulho ritmado de gotas de chuva caindo sobre o solo. Todas essas sonoridades representam notas musicais que, por sua vez, são uma convenção humana, criada para facilitar a leitura de partituras, para criar uma linguagem própria que será traduzida em som. As notas, quando organizadas, originam acordes, e um conjunto de acordes geram um campo harmônico. (necessito de confirmação da veracidade técnica dessa informação)

A música faz parte do cotidiano dos seres humanos, e hoje já é reconhecidamente uma ciência com amplo campo de estudo e enorme complexidade e relevância no cenário educacional. Prova disto é que em 2008 houve uma alteração na Lei de Diretrizes e Bases da Educação Pública, onde, como versa o art. 1º, §6º da lei federal 11.769, “A música deverá ser conteúdo obrigatório(..)” dos componentes curriculares do ensino público.

### 1.1. Problema <a name="problema"></a> 
<br>

A teoria musical é complexa e extensa, inacessível para iniciantes por possuir uma linguagem bastante técnica e refinada. A leitura de partituras requer um arcabouço teórico bem desenvolvido e pleno conhecimento de conceitos como intervalos, escalas, harmonias, dentre outros. Diante de tantos pré-requisitos complexos e que requerem bastante esforço e tempo, observa-se uma lacuna enorme existente entre aqueles que já possuem total domínio de um instrumento, e os que querem aprender ou se aprimorar, o que pode gerar uma dificuldade de ensino, por parte dos experientes, e de aprendizado, por parte dos novatos. 

Diante desse cenário de aprendizado musical identificamos um problema que afeta tanto quem quer aprender quanto quem quer ensinar, a falta de ferramentas que auxiliem de forma simples e visual os conceitos musicais.

### 1.2. Objetivo do trabalho <a name="objetivo-do-trabalho"></a> 
<br> 

Oferecer um aplicativo que possa, de forma interativa, rápida e acessível, apoiar aqueles que querem aprender, ensinar, ou aperfeiçoar conceitos que envolvem a teoria musical.

Apoiar alunos, iniciantes e entusiastas a aprender teoria musical.

Tornar a teoria musical mais inclusiva e acessível para os que não possuem condições de arcar com um profissional particular. 

Facilitar a transmissão de conhecimento entre professor e aluno.

Auxiliar na implementação da teoria musical em instituições de ensino que enfrentam dificuldades ao passar por tal conteúdo.

### 1.3. Justificativa <a name="justificativa"></a>
<br> 

A teoria musical é um aspecto fundamental para qualquer pessoa que deseja se aprofundar no universo da música, e obrigatório no ensino público. A aplicação visa acelerar e difundir conhecimentos musicais de forma divertida e acessível, gerando mais motivação para alunos, em aprender, e professores, ensinar. O aplicativo também tem como foco reduzir as dificuldades daqueles que querem aprender sozinhos e sentem falta de recursos para tal. Existe uma dificuldade em se encontrar soluções de qualidade para aprender sobre o assunto, especialmente para os iniciantes.
Os resultados desse projeto beneficiam a sociedade por popularizar e dinamizar o acesso à educação musical, bem como a facilitar a aplicação do disposto na lei federal 11.769


### 1.4. Público alvo <a name="publico-alvo"></a>
<br> 

O aplicativo tem como público alvo estudantes de música de todos os níveis, músicos profissionais que desejam aprimorar habilidades em teoria musical e aplicar esse conhecimento em seu trabalho, e professores de música que podem o usar de forma a complementar o conteúdo lecionado em suas aulas.
<br> 

## 2. Requisitos <a name="requisitos"></a>
<br> 

### 2.1. Requisitos Funcionais <a name="requisitos-funcionais"></a>

- O aplicativo deve ter no mínimo dois modos diferentes, um para amadores e iniciantes, e outro para músicos já experientes;
- O aplicativo deve ser traduzido no mínimo para Português e Inglês;
- O aplicativo deverá ser responsivo para os mais variados tamanhos de tela, mesmo que isso signifique a ocultação de algumas funcionalidades; 
- O aplicativo deve conter, para iniciantes, exercícios básicos de música; 
- O aplicativo deverá conter um playground, onde seja possível o usuário interagir com a interface; 
  - Para o playground, apresentar as notas corretas de acordo com a escolha do usuário; 
  - Para o playground, ao menos dois instrumentos devem ser apresentados como opções de  escolha (violão, piano); 
  - Para o playground, o usuário poderá fazer o overlapping de no máximo 3 escalas no mesmo tom;
  - Para o playground, na escolha da interface do violão, o usuário poderá escolher entre afinações padrões, ou criar afinações personalizadas; 
  - Para o playground, dependendo das notas escolhidas, o aplicativo deverá gerar um código, que ficará disponível ao usuário, para que o mesmo possa guardar suas configurações para usá-las mais tarde; 
  - Para o playground, haverá um modo de construção de escalas totalmente manual, o aplicativo deverá gerar um código que guarde suas configurações;
<br> 

#### História de usuário 1: estudante de música iniciante.
História: Uma estudante de música iniciante que está procurando um aplicativo que possa ajudá-la a aprender os conceitos básicos de música de uma forma interativa. Ela deseja um modo para iniciantes no aplicativo para que possa começar a aprender música a partir do zero. Sofia prefere usar o aplicativo em português, pois é sua língua nativa.

#### História de usuário 2: músico profissional.
História: João é um músico experiente e está procurando um aplicativo que possa ajudá-lo a aprimorar suas habilidades musicais. Ele procura um modo avançado no aplicativo que possa desafiar suas habilidades e conhecimentos musicais. João prefere usar o aplicativo em inglês, pois é a língua comum usada no mundo da música.

#### História de usuário 3: estudante de música avançado.
História: Pedro é um estudante de música avançado que deseja usar um aplicativo que possa ajudá-lo a praticar diferentes escalas musicais de uma forma interativa. Ele quer um playground no aplicativo que possa ajudá-lo a tocar violão e piano, além de permitir o overlapping de escalas. Pedro também deseja criar afinações personalizadas para o violão, além de ter a capacidade de armazenar suas configurações de escalas manualmente para referência futura.


### 2.2. Requisitos não funcionais <a name="requisitos-funcionais"></a>

### 2.3 Restrições <a name="restricoes"></a>

## 3. Projeto da Solução <a name="projeto-da-solucao"></a>

## 4. Metodologia de trabalho <a name="metodologia-de-trabalho"></a>

## 5. Implementação da solução <a name="implementacao-da-solucao"></a>

## 6. Avaliação da Aplicação <a name="avaliacao-da-aplicacao"></a>

## REFERÊNCIAS <a name="referencias"></a>
