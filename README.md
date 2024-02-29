RESOLUÇÃO DE PROBLEMA DE PROGRAMAÇÃO LINEAR

Direto ao ponto.

O exercício a ser resolvido será esse: 

MAX Z = 350X1 + 300X2, também chamado de vetor Z ou função objetiva

Sujeito a 

R1: 1X1 + 1X2 <= 200
R2: 9X1 + 6X2 <= 1566
R3: 12X1 + 16X2 <=2880
R4: X1 >= 0
R5: X2 >= 0

1º passo: Precisamos definir as linhas que serão traçadas no plano cartesiano, relacionados as:

a) Restrições 
b) Função objetiva (vetor Z)

Obs.: Em relação a restrição 4 e 5, não serão definidas linhas para o plano cartesiano, pois se tratam de restrições de referência, o que significa que o valor das variáveis X1 e X2 devem ser maiores (>) ou iguais a zero.

Lembrando que o padrão do plano cartesiano sempre será nesse formato

	| f(y)
	|
	|
	|
	|
	|
	|___________________ f(x)

Precisamos definir o traçado de X1 e X2. Cada uma das variáveis são pontos a serem inseridos nas respectivas linhas. Entenda o coeficiente X1 como ponto X (na reta X) e X2 como Y (na abcissa Y).  

A regra básica para essa definição é que, se for resolver um ponto X, por exemplo X1, automaticamente, X2 deve ser zerado. 

Para resolver as restrições para traçá-las no plano cartesiano, siga a seguinte sentença:

Restrição 1 = 1X1 + 1X2 <= 200

Resolvendo X1 
Se X2 = 0, então
R1: 1X1 + 0 = 200
R1: 1X1 = 200
R1: X1 = 200/1 = 200

Resolvendo X2

R1: 1X1 + 1X2 <= 200 
Se X1 = 0 então 
R1: 0 + 1X2 = 200
R1: X2 = 200/1 = 200

A restrição 1 será representada no p.c. como f(x, y) = 200, 200

No gráfico isso deve ser feito da seguinte forma: 

[Figura 1 - Traçado A]

É importante, caso faça outros exercícios, fazer para cada restrição e função de x, uma linha com identificador único (ex.: uma cor diferente para cada linha, tipo isso) para fins de legibilidade e organização.

Resolvendo as demais restrições:

Restrição 2: 9X1 + 6X2 <= 1566

Resolvendo X1 
Se X2 = 0, então
R2: 9X1 + 0 = 1566
R2: 9X1 = 1566
R2: X1 = 1566/9 = 174

Resolvendo X2

Se X1 = 0, então
R2: 0 + 6X2 = 1566
R2: 6X2 = 1566
R2: X2 = 1566/6 = 261

F(x, y) = 174, 261

Restrição 3: 12X1 + 16X2 <=2880

Resolvendo X1 
Se X1 = 0, então
R3: 0 + 12X2 = 2880 
R3: X2 = 2880/12 = 240

Resolvendo X2

Se X1 = 0, então
R3: 0 + 16X2 = 2880 
R3: X2 = 2880/16 = 180

F(x, y) = 240, 180

Veja como fica o esquema logo abaixo: 

[Figura 2 - Esquema]

Agora vem o pulo do gato!

Precisamos resolver agora o traçado da função objetivo. É aí que está o pulo do gato.

Existe um conceito chamado vetor de gradiente (triângulo de cabeça pra baixo), em que os coeficientes de função objetiva (também chamado de vetor z) são definidos como X1 e X2 e devem ser inseridos no plano cartesiano. Ela é uma referência para onde o vetor está apontando para maximizar a solução.

A regra básica é:

A linha Z deve ter origem a partir do ponto 0, ou seja, no centro do plano cartesiano;
Se ns valores de X1 e X2 são iguais a 350 e 300, respectivamente, então a função gradiente Z é: f(x1, x2) = 350, 300

Confira como ficou o esquema:

[Figura 3 - Gradiente]

Só para fins de curiosidade, observe que o espaço de solução está na região em que todas as linhas estão situadas acima dela. Essa região é conhecida como factível. 

Agora precisamos encontrar as coordenadas para encontrar a solução ótima

Podemos fazer a interseção da linha na seguinte forma: 

[Figura 4 - Interseção manual]

Então f(x) = 122X1 + 78X2

E para finalizar, vamos fazer o cálculo da solução ótima:

Z = (350 * 122) + (300 * 78) 
Z =  42.700 + 23400 = 66100

A solução ótima é 66100.