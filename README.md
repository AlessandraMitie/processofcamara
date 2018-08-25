# Respostas

1) Se você tivesse 5 diferentes arquivos de folhas de estilo, qual seria a melhor forma de integrá-los no site?
	Usaria alguma ferramenta ou extensão para juntar os arquivos em um número menor para minimizar requisições

2) Fale 3 formas de diminuir o page load (tempo de carregamento real e percebido).
 - Imagens nos formatos corretos, otimizadas e comprimidas
 - Arquivos CSS, HTML e JavaScript compactados
 - Otimizar o código HTML com linhas identadas

3) Quais ferramentas você usa para testar a performance do seu código?
	Diretamente pelo navegador Chrome (F12)
	Já ouvi falar sobre o JMeter, porém ainda não tive oportunidades de poder estudar e usar a ferramenta.

4) Considere o HTML5 como uma plataforma web aberta. Quais são os blocos de construção de HTML5?
	Header, footer, nav, section, article, aside.

5) Você pode explicar a diferença entre GET e POST?
	GET é um dos métodos mais utilizados para se transmitir (pegar/trazer) informações entre páginas. Os dados são enviados utilizando a linha de endereço da URL (no cabeçalho da requisição). Pelo fato dos dados serem enviados no cabeçalho da requisição, o tamanho de dados a serem enviados tem o limite de 255 caracteres.
	POST é geralmente utilizado quando se utiliza um formulário de dados e registros são criados. Os dados são encapsulados e enviados no corpo da requisição HTTP utilizando o buffer de memória.

6) Liste quantas propriedades display você puder lembrar.
 - display: block
 - display: inline
 - display: inline-block
 - display: table

7) Qual a diferença entre inline e inline-block?
	A propriedade inline faz com que os elementos HTML sejam renderizados dentro do bloco na mesma linha um do lado do outro
 	A propriedade inline-block faz com que os elementos sejam renderizados como bloco, e seja possível definir a altura e largura para o elemento

8) Qual a diferença entre elementos posicionados de forma relativa, fixa,
absoluta e estática?
 - position: fixed;
 	O elemento é posicionado e permanece sempre no mesmo lugar mesmo que haja rolagem na página
 - position: absolute;
 	O elemento é posicionado relativamente mais próximo de onde está contido. Se este elemento não possuir elementos ancestrais posicionados relativamente, ele usará o body como referência
 - position: static;
 	Por default os elementos HTML são posicionados de forma estática, de acordo com o fluxo da página
 - position: relative;
 	O elemento é posicionado em relação à sua posição normal, estaticamente, a menos que se adicione propriedades (top, bottom, left, right) no estilo do elemento

9) Qual a diferença entre .call e .apply?
	.call é um método de funções capaz de alterar o valor this. O primeiro parâmetro que recebe é o valor de this que será atribuído à função.
	.aplly invoca uma função com o valor this (contexto) e seu segundo parâmetro recebe um array dos parâmetros da função

10) Qual a diferença entre == e ===?
	"==" faz a comparação dos valores independente do tipo, pois o operador converte os tipos para que possa compará-los
	"===" faz a comparação dos valores e do tipo (int, string, etc) sem tentar converter os tipos