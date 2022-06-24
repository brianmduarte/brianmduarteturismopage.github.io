# Brasil Turismo
 Olá, Devs! Este é o meu projeto integrador realizado a partir das orientações da Prof. Karen Santos. (DIO) onde pude realizar algumas aplicações do conceito de "containers", assim como suas propriedades aplicadas via CSS (display, flex-direction, flexflow, justify-content, etc.)
 
 Segue link da page: https://brianmduarte.github.io/brianmduarteturismopage.github.io/

 Abaixo algumas anotações importantes sobre essa propriedade:

Flex Container: é a tag que envolve os itens, será nela que iremos aplicar a propriedade “display:flex”. Transforma todos os seus itens filhos em flex itens. Pode ser aplicada em qualquer tag (div, span, h1, h2, e até mesmo um link).

Propriedades relacionadas:
•	Display
•	Flex-direction
•	Flex-wrap
•	Flex-flow
•	Justify-content
•	Align-items
•	Align-content

Flex Item: São os elementos filhos diretos do Flex Container. E também podem se tornar flex container.
•	Flex-grow, flex-basis, flex-shrink, flex, order e align-self.

Estrutura básica do FLEX WRAP
É a propriedade que define se os itens devem ou não quebrar a linha.
Por padrão eles não quebram linhas, isso faz com que os flex itens sejam compactados além do limite do conteúdo.

•	Nowrap: é o padrão, não permite a quebra de linha;
•	Wrap: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado.
•	Wrap-reverse: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado, porém na direção contrária da linha acima.


Estrutura básica e prática com FLEX FLOW
É um atalho para as propriedades flex-direction e flex-wrap.
Porém seu uso não é tão comum, visto que, quando mudamos o flex-direction column, mantemos o padrão do flex-wrap que é nowrap.

Estrutura básica do JUSTIFY CONTENT
Essa propriedade vai se encarregar de alinhar os itens dentro do container de acordo com a direção pretendida e tratar da distribuição de espaçamento entre eles.
OBS: caso seus itens esteja ocupando 100% de todo o container, ela não se aplica.

Variações:
•	Flex-start: início do container
•	Flex-end: final do container
•	Center: ao centro do container
•	Space-between: cria um espaçamento igual entre os elementos.
•	Space-around: os espalhamentos do meio são duas vezes maiores que o inicial e final.

Estrutura básica e prática com ALIGN ITEMS
- Trata-se do alinhamento dos flex itens de acordo com o eixo do container. 
- O alinhamento é diferente para quando os itens estão em colunas ou linhas.
- Também permite o alinhamento central no eixo vertical. 

Tipos de alinhamento:
•	Center: alinhamento dos itens no centro
•	Stretch: padrão, e os flex itens cresçam igualmente
•	Flex-start: alinhamento dos itens no início
•	Flex-end: alinhamento dos itens no final
•	Baseline: alinhamento de acordo com a linha base da tipografia.

Estrutura básica e prática com ALIGN CONTENT

Align-content: é a propriedade responsável por tratar o alinhamento das linhas do container em relação ao eixo vertical do container.
Precisamos que: 
•	O container utilize quebra de linhas;
•	A altura do container seja maior que a soma das linhas dos itens.

Tipos de alinhamento:
•	Center: alinhamento dos itens ao centro
•	Stretch: é o padrão e os flex itens crescem igualmente;
•	Flex-start: alinhamento dos itens no início;
•	Flex-end: alinhamento dos itens no final;
•	Space-between: cria um espaçamento igual entre os elementos;
•	Space-around: os espaçamentos do meio são duas vezes maiores que o inicial e final.


Estrutura básica e prática com FLEX GROW
Define a proporcionalidade de crescimentos dos itens, respeitando o tamanho de seus conteúdos internos.
! OBS: não irá funcionar caso tenhamos adicionado JUSTIFY-CONTENT ao nosso flex container.


Estrutura básica e prática com FLEX BASIS
É a propriedade que estabelece o tamanho inicial do item antes das distribuições de espaço restante dentro dele, usando como base o conteúdo interno disposto.
•	Auto: caso o item não tenha tamanho, este será proporcional ao conteúdo do item.
•	Px, %, em,...: são valores exatos previamente definidos.
•	0 (zero): terá relação com a definição do flex-grow;

Estrutura básica e prática com FLEX SHRINK
É a propriedade que estabelece a capacidade de redução ou compressão do tamanho de um item.

Estrutura básica e prática com FLEX
Esta propriedade é um atalho ou abreviação de escrita para as propriedades: grow, shrink e basis.

Estrutura básica e prática com ALIGN SELF
É a propriedade que estabelece o alinhamento de MODO INDIVIDUAL sobre um determinado item.

Valores possíveis: 
- auto: valor padrão, irá respeita a definicação de align-items do container;
- flex-start: ao início do container;
- flex-end: ao final do container
- center: relativo ao centro de acordo com o eixo;
- stretch: ocupa todo os espaços relativo;
- baseline: utiliza a linha base da tipografia.
