# Modelos
modelos de codigos

## Bibliotecas:
numpy, pandas, pptk

### Cria cubo 3d

Utilizar def cube3d(l,val,rand,n_ma)

    '''
    Entrada:
    data = pandas dataframe
    l = lado do cubo
    val = valor atribuido para cada ponto (padrão '0')
    rand = True para atribuir valores aleatorios
    n_max = valor maximo aleatorio
    Saída:
    data = pandas dataframe com posição x,y,z e valor
    '''

<img width="258" alt="cube3d" src="https://user-images.githubusercontent.com/59963253/76451522-4fa69d00-63ae-11ea-9250-b68263d6243f.PNG">

### Cria rampa 3d

Utilizar def ramp(data,b,theta,d,reductor):

    ''' 
    Entrada:
    data = pandas dataframe
    b = altura inicial da rampa
    theta = angulo de inclinação (graus)
    d = largura da rampa
    Saída:
    data = valor de data com rampa
    '''

<img width="257" alt="rampa3d" src="https://user-images.githubusercontent.com/59963253/76451872-e1aea580-63ae-11ea-90f5-3001bd224589.PNG">
<img width="255" alt="rampa3d(2)" src="https://user-images.githubusercontent.com/59963253/76470031-63fa9200-63ce-11ea-956e-748c276255c3.PNG">

### Cria nuvem de pontos

Utilizar cloud(maxvalue,size):

    '''
    Entrada:
    maxvalue = valor máximo dos elementos
    size = tamanho da matriz [m,n]
    Saída:
    s = posicao x,y,z e valor [i,j]
    '''

<img width="256" alt="cloud1" src="https://user-images.githubusercontent.com/59963253/76475097-a1661c00-63dc-11ea-8351-daf51ee58bdc.PNG">
<img width="256" alt="cloud2" src="https://user-images.githubusercontent.com/59963253/76475103-a32fdf80-63dc-11ea-9c73-99e89ad63bda.PNG">
