## background
- Define um fundo para o nosso elemento
- Sua área de atuação é a caixa toda 
- por padão, é transparente

### Exemplos 
- Usar cores sólidas
- Usar imagens
- controlar
  - a posição das imagens,
  - se elas se repetem ou não
  - o tamanho delas na caixa
- Usar cor e imagem juntas
- usar cor gradiente  

# Values
background-repeat: repeat-x;
background-repeat: repeat-y;
background-repeat: repeat;
background-repeat: space;
background-repeat: round;
background-repeat: no-repeat;

# Podemos usar 2 valores: horizontal | vertical 
background-repeat: repeat space;
background-repeat: repeat repeat;
background-repeat: round space;
background-repeat: no-repeat round;

# Principais valores
background-position: top;
background-position: bottom;
background-position: left;
background-position: right;
background-position: center;

# Para mudar o tamanho da imagem do background usamos a propriedade background-size.

/* Values */
background-size: cover;
background-size: contain;

/* Podemos usar 2 valores, o primeiro é para a largura da imagem e o segundo é para a altura */
background-size: 40% auto;
background-size: 2em 25%;
background-size: auto 8px;
background-size: auto auto;