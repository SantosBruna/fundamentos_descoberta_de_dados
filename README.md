# Projeto: Fundamentos da Descoberta de Dados

## 📊 Sobre o Projeto
Estudo de um dataframe de produtos de um supermercado do Chile,.

## 🎯 Objetivos
- Identificar categorias com médias muito mais altas e muito mais baixas do que a mediana
- Identificar qual o comportamento da média e mediana nas categorias com maior desvio
- Identificação de como é distribuição dos dados que possuem categorias com desvio padrão alto, baseados no boxplot
- Correlação da media de desconto de cada categoria e marca.
  
## 📁 Estrutura
- `notebooks/`: Análises em Jupyter
- `data/`: Datasets utilizados
- `visualizations/`: boxplot, gráfico de barras e mapa interativo

## 🛠️ Tecnologias
- Python 3.8+
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn, Plotly

## 📈 Resultados
- As únicas categorias que tiveram desconto são as que possuem um desvio padrão alto.
- A marca de beleza e cuidado pessoal são as que possuem a maior quantidade de marcas diferentes.
- Congelados tem uma grande quantidade de produtos e muitos produtos com preços altos, também é a categoria que tem a maior quantidade de descontos.
- A categoria com a maior presença de outiliers é a que tem a maior média de descontos.
- Nas categorias lacteos e beleza e cuidado vemos que o catalogo de cada um tem produtos com preços baixos mas outiliers de alguns produtos com preço acima da faixa.
- A categoria lacteos é o que tem a maior quantidade de produtos com preços altos. Isso faz com que a média seja alta, gerando uma diferença entre a mediana e a media e deixando o desvio padrão alto.
- Já os produtos congelados é onde tem a maior quantidade de produtos , sendo alguns deles com preços altos. Podemos confirmar isso devido ao tamanho da linha superior que é grande e a inferior não é visivel.
- Para a categoria de congelados vejos poucos outiliers que também eleva a media e como a amplitude é alta acabamos tendo uma diferença maior do que a de beleza e cuidados.
- Beleza e cuidados tem uma diversificação de produtos baixo e os produtos mais caros ainda são mais baratos do que os congelados.
- A categoria de comidas preparadas tem uma diferença da média e mediana negativa mas ainda assim menor do que as anteriores, indicando uma melhor distribuição.
- Esta categoria, de comidas preparadas, também tem alta amplitude pois o quadrado também é grande, embora a categoria de congelados tenha uma amplitude maior que a comidas preparadas.
- A categoria de comidas preparadas tem alguns outiliers, indicando a presença de poucos produtos mais caros no catálogo. No entanto a linha superior e inferior parecem ter o mesmo tamanho , o que indica que tem produtos muito baratos e muito caros. Por isso a diferença deu negativa, pois embora as linhas tenham o mesmo tamanho, a linha inferior chega a "0" enquanto a superior chega a "7000". Mesmo com os outiliers, a média se manteve baixa.

## 👩‍💻 Autora
Bruna S. R. Santos
- LinkedIn: www.linkedin.com/in/brunasrsantos
- Email: brunasrsantos@gmail.com

## 📝 Licença
MIT License
