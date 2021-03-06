# Genius-APS4

####Enunciado
Neste trabalho, é pedido aos alunos que programem uma versão simplificada do brinquedo Genius, utilizando obrigatoriamente a linguagem Java.

![](http://thumbs.buscape.com.br/jogos-diversos/estrela-genius_200x200-PU68158_1.jpg)

####Como se joga?
O brinquedo Genius é um jogo para um único jogador, este foi o primeiro jogo eletrônico vendido no Brasil. O objetivo do jogo é repetir, sem erros, a sequência de luzes e cores apresentada pelo brinquedo, que possui quatro botões de cores diferentes. A cada rodada, a sequência apresentada pelo brinquedo aumenta até atingir um valor máximo. Existem 3 tipos de jogos:  
* Repita a sequência;
* Crie sua própria sequência;
* Repita a sequência com tempo limitado ao tamanho máximo da sequencia em segundos.  

Existem também 4 níveis de dificuldade:
* Sequência de tamanho 8 no máximo;
* Sequência de tamanho 14 no máximo;
* Sequência de tamanho 20 no máximo;
* Sequência de tamanho 31 no máximo;

Caso o jogador acerte a sequência máxima, ele vence. Caso usuário erre algum botão de qualquer sequência, ele perde.

####Instruções
* O problema deve ser resolvido através de um programa em Java;
* O código-fonte deve estar devidamente comentado;
* Não serão aceitos trabalhos que caracterizem cópia (mesma estrutura e algumas pequenas modificações) de outro ou de códigos da internet;
* Eventualmente, após a entrega dos trabalhos serão marcadas entrevistas com cada um dos alunos para apresentação dos mesmos para o professor.

###O Que Deve Ser Implementado?
O brinquedo Genius, com seus 3 tipos de jogos e 4 níveis de dificuldade.
* Os elementos devem ser minimamente animados;
* A janela do jogo não poderá ser redimensionada;
* Deve ser criado um “módulo de pânico”
	* Caso o usuário coloque o mouse no canto inferior direito da janela, toda a interface do jogo deve ser substituída por um disfarce;
	* Para retornar ao jogo, o usuário deve clicar em uma parte específica da janela.
* O jogo deverá ser jogado também através do teclado;
* Há total liberdade quanto ao desenho da interface, no entanto, deve ser utilizado o maior número de componentes gráficos (AWT/Swing) quanto possível (pelo menos oito)
	* A não utilização de bom número de componentes acarretará em diminuição da nota.
* Também deverá ser criada uma base de dados com dados estatísticos das jogadas, como número de tentativas realizadas, número de tentativas assertivas, e número de tentativas não assertivas;
	* Deve permitir o usuário consultar as estatísticas armazenadas, por usuário, tipo de jogo e nível de dificuldade;
* No inicio do jogo deve ser solicitado um nome/apelido do usuário que irá jogar.
* Devem ser utilizadas classes interna e / ou interna anônima.
* O sistema deve ser constituído de pelo menos 03 classes públicas concretas.
* Deverá ser entregue uma documentação nos moldes da APS.
* O grupo deverá ser composto no formato da APS, no máximo quatro alunos.

####Avaliação
* Funcionamento adequado do programa e compilação (códigos que não compilem serão zerados, e warnings diminuirão a nota);
* Corretude (independente se gerado por IDE ou manualmente).
* Atendimento ao enunciado do trabalho;
* Comentários;
* Indentação do código;
* Usabilidade e adequação dos componentes da interface gráfica.

####Pontos Extras
Somente serão atribuídos pontos extras ao trabalho se a nota original for maior ou igual a 7.
* Melhor interface (somente um trabalho): 2pts;
* Efeitos Sonoros: 1pt.

#Como vamos fazer?
4 botões (obvio hahaha)

- [ ] Repita a sequência  
*Existe um limite para as jogadas ou o jogo continua até o jogador errar?!*  
* Dois vetores de N posições (tamanho é informado de acordo com a dificuldade)
	* Armazena a sequência random
	* Auxiliar que armazena a sequência de jogada  

_Alterar o botão para indicar qual foi pressionado_  
_Comparar os vetores a cada jogada_  

- [ ] Crie sua própria sequência  
* Dois vetores de N posições (tamanho é informado de acordo com a dificuldade)
	* Armazena a sequência random
	* Auxiliar que armazena a sequência de jogada  

_Alterar o botão para indicar qual foi pressionado_  
_Comparar os vetores a cada jogada_  

- [ ] Repita a sequência com tempo limitado ao tamanho máximo da sequencia em segundos  
* Dois vetores de N posições (tamanho é informado de acordo com a dificuldade)
	* Armazena a sequência random
	* Auxiliar que armazena a sequência de jogada  

_Alterar o botão para indicar qual foi pressionado_    
_Comparar os vetores a cada jogada_  
_Contar o tempo limite para repetir a sequência de acordo com a dificuldade_  
