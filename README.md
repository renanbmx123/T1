# T1 Inteligencia Artificial
PUCRS - Escola Politécnica

Inteligência Artificial – Prof. Sílvia

## T1 – Labirinto

### 1. Definição: O trabalho 1 da disciplina de IA visa fixar e exercitar conceitos relativos a agentes e a algoritmos de busca. O trabalho consiste na simulação de um labirinto, no qual o agente deve encontrar o caminho que leva até a saída de um labirinto.

#### 2. Ambiente: O ambiente do agente é um Labirinto. Ele consiste em uma matriz 12 × 12 (Figura1 ). A entrada E será sempre na posição (0,0) e a saída entre na (11,11). A entrada e a saída são sempre conhecidas pelo agente, o que ele são sabe é o caminho, ou seja, a sequência de células que levam do seu estado inicial (E) ao estado final (S).

### 3. Movimentação do Agente: O agente pode se mover no labirinto, uma célula de cada vez em qualquer direção: ←→↑↓. Agentes não caminham sobre paredes do labirinto e nem as transpassam. As paredes estão representadas pelo caracter 1 (um). No arquivo, células vazias (livres) estão identificadas por 0 (zero). 

|----|
| E | 0 | 0 0 0 0 0 0 0 0 0 0

1 1 1 1 0 0 0 0 0 1 1 1
1 0 0 0 0 1 1 1 0 1 1 0
1 0 1 1 1 1 1 1 0 0 0 0
0 0 0 1 0 0 0 0 1 0 1 1
1 1 0 0 0 1 0 1 0 0 1 1
1 1 1 0 1 1 0 0 0 1 1 0
0 0 1 0 0 1 0 1 0 1 1 0
0 0 0 0 1 1 0 0 0 1 1 0
1 1 1 0 1 0 0 1 1 1 1 0
1 1 1 0 1 0 0 0 0 1 1 1
1 1 1 0 0 0 0 1 0 0 0 S
###### Exemplo arquivo para um labirinto 12x12


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
