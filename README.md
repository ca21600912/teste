# Paint (Episódio 1)

Aplicação de apoio à cadeira de Linguagens de Programação 2 da Universidade Lusófona.

## Requisitos do "cliente"

Para começar, o nosso "cliente" imaginário pretende uma aplicação gráfica que permita desenhar linhas no écran. 
Para tal, a aplicação deverá ter 4 botões: "seta cima", "seta baixo", "seta esquerda" e "seta direita", 
e logo no arranque desenhará um pixel no meio do écran.

## Como começar?

Terás que descarregar (clone) este projecto do github e abri-lo no Intellij. 
Segue as instruções que estão nos slides da aula 2.

## E depois?

Infelizmente, como rapidamente se aperceberão, a aplicação não está completa. 
Aliás, ela nem compila. 
O objectivo é torná-la compilável e a fazer o que o "cliente" pretende.

## Sugestão de passos a seguir

1. Resolver os erros de compilação
1. Correr a aplicação. Irás verificar que o único botão que funciona é a seta para a esquerda.
1. Implementar a "seta para baixo". Dica: Procura comentários do tipo `// TODO`. Normalmente eles indicam que alguma coisa ficou por implementar.
1. As imagens da seta para baixo e seta para o lado estão algures numa pasta do projecto. Descobre onde estão.
1. Nessa pasta coloca mais duas imagens chamadas "icon_up.png" (seta para cima) e "icon_right.png" (seta para a direita). 
Terás que ir buscar essas imagens na Internet. Dica: Usa o Google Images (https://www.google.com/imghp)
1. Acrescenta dois botões à barra de ferramentas com essas imagens, descobrindo como é que os outros dois botões foram 
criados e implementando algo semelhante. Para cada botão terás 3 operações: (1) criar o botão; (2) adicionar o botão à barra de ferramentas; 
(3) definir o que acontece quando se carrega nesse botão
1. Arranca novamente a aplicação e verifica que já aparecem 4 botões e que fazem o que é suposto
1. O que acontece quando carregas num desses botões tanto que a linha chega ao fim do écran? 
O programa começa a dar erros, conforme podes verificar na consola do Intellij.
1. Altera o programa de forma a que deixe de dar erros, verificando se a acção do botão fará com que a linha saia fora do écran. 
Dica: Lembra-te das constantes WIDTH e HEIGHT 

## Tirar o coelho da cartola

É sempre uma boa ideia superar as expectativas do nosso cliente, surpreendo-o com coisas giras que ele não pediu.

Algumas ideias:

1. Desenhar as linhas verticais a verde e as horizontais a vermelho.
1. Desenhar as linhas para a direita a tracejado.
1. Acrescentar botões para desenhar linhas oblíquas.
