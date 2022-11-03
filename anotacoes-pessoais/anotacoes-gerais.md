# Psicologia das Cores 

- Escolher uma boa harmonia
- Escolher uma boa paleta de cores 

Tudo isso influencia no resultado final e na experiência do usuário. 

**Porque as marcas usam a cor "azul"?** 

**Ex:** Dell, HP, Facebook, Twitter, Curso em Vídeo ------> essa cor simboliza competência, sabedoria, calma e além disso, tem uma taxa de rejeição muito baixa. 

Evitar contrastes, pois causa cansaço visual. 

**TABELA DAS CORES E SUAS ASSOCIAÇÕES** 

![image](https://user-images.githubusercontent.com/96539606/198409616-e25113de-2753-43bc-9aea-7cc76fc56cb1.png)

## Classificação das Cores

![image](https://user-images.githubusercontent.com/96539606/198409521-e7307a03-27f1-4003-b395-9a71c48c81ce.png)


## Adobe Color

No site da adobe color, é possível: 

- Escolher uma paleta de cores com o disco de cores (códigos para o css)
- Capturar cores a partir de imagens (item extrair tema)
- Extrair degrade a partir de imagens
- Além disso, é possível explorar paletas profissionais (já feitas)
  - Para isso basta ir na aba superior do site em "explorar" em seguida "temas de cores"



## Paletton 

Outra ferramenta para trabalhar com cores, é possível: 

- Simular cores e paletas
- Simular as cores em um site. 



## Coolors 

Outra plataforma para escolher sua paleta de cores. 

Nesse site, é possível: 

- Escolher sua paleta de cores
- Apertando "espaço" você consegue uma nova paleta
- Selecionando o "cadeado" você consegue bloquear uma cor e apertar espaço novamente para escolher o restante da paleta de cores. 



## GIMP 

- Obtendo cores usando o GIMP
- Você precisa tirar um print do site, e selecionar a imagem no GIMP para obter o código. 



## Colorzilla

- Extensão para pegar códigos de cores de sites. 



## Tipografia 

- Parte da produção dos livros eram feitos por Monges Copistas.
- Necessidade de criar letras mais fáceis de ler
- Surge nossos estudos sobre tipografia - melhorar visualização, legibilidade das letras
- **TIPO** - Týpos - impressão
- **GRAFIA** - Graphía - escrita
- **Tipografia**: é o estudo de como vou escrever coisas no papel, mas atualmente em telas!   



### Anatomia das Letras 

- Letra "x" ponto de partida para desenhar as outras fontes, defini a altura base.    

- Serifa: são pequenos traços nos finais das letras.

  - Cria uma linha imaginária que o nosso cérebro percebe, facilitando a leitura.

- Filete: duas hastes e um arco.   






# BOX-MODEL - PRIMEIROS PASSOS 

Contextualização: tudo que está dentro do HTML está em "caixa", formando uma hierarquia de caixas. 

Uma caixa dentro da outra: **aninhamento** (uma coisa que cabe outra dentro e assim por diante).

**O que é o box?** 

Todo elemento visível em formato de caixa, podendo ter diversos tamanhos. 

Ex: h1. 



**CONCEITOS IMPORTANTES:**

**Heig<u>ht</u>**: ALTURA

**Wid<u>th</u>**: LARGURA

**Border:** linha que circunda o seu conteúdo - linha grudada no pontilhado do conteúdo.

**Padding**: espaço que fica entre a linha pontilhada e a borda, tem top, bottom, left, right. 

**Margin:** espaço que fica entre a borda e o espaço externo. 

**Outline:** traçado fora da margin. 

![O modelo caixa do CSS (Box Model) | by Silas Caimi | Medium](https://miro.medium.com/max/965/1*kGMWtZihmaUhxZI5ZVicLA.png)



![HTML Progressivo: Box Model (Modelo de Caixas) em CSS - Margin, Padder e  Border](https://3.bp.blogspot.com/-x3DnboKrOb8/Uxk5Cqdj1hI/AAAAAAAAA9w/bKPG5CtGDCM/s1600/box-model-modelo-caixa-css.png)



### TIPOS DE CAIXAS 

- Qual a diferença entre as caixas **box-level** e **inline-level**? 

**Box-level:** sempre se inicia em uma linha nova (quebra linha), e sempre ocupa a largura inteira do espaço -> sempre 100% do seu navegador. Já a altura é automática de acordo com o tamanho do conteúdo.

Exemplo: 

- Div
- H1 até o H6
- P
- Main
- Header
- Nav
- Article
- Aside
- Footer
- Form
- Vídeo

**Inline-level:** não pula para próxima linha, desenha a caixa na mesma linha continuando o conteúdo. 

**Exemplo:** 

- Span
- A
- Code
- Small
- Strong
- EM
- SUP
- SUB
- Label
- Button
- Input
- Select
- Img

![Elementos in-line e elementos block-level](data:image/jpeg;base64,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)





### Identificando caixas 

- User agent: configurações do próprio navegador

- Display-block: ele vai ser um elemento do tipo box-level, podendo mudar para outros valores como display: flex, inline-block.

- Border-width: largura da borda.

- Border-style:  tipo de estilo da borda, exemplo: solid, dashed, dotted(pontilhado), double (linha dupla), groove (borda 3D).

- Border-color: cor da borda.

- Ordem para organizar o padding: 

  - Em cima 
  - Direita
  - Em baixo
  - Esquerda

  OBS: como se fosse um relógio. 



### Personalizando uma caixa para inline ou level

Exemplo: 

  - Para personalizar um H1 que por padrão é box-level, basta:

    h1 {

    ​	display: inline;

    }

  - Outro exemplo, podemos usar um display inline block

    Se mantém na mesma linha, mas em bloco. 





