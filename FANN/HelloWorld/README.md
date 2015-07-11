# Documentação

### Arquivos XOR

| Arquivo        | O que é?     |
| ------------- |:-------------:| 
| xor.data      | Arquivo com os dados de treinamento, neste exemplo foram utilizados o aprendizado de XOR |
| teste_xor.c      | Arquivo responsável pelo treinamento dos dados do XOR |
| run_xor_teste.c | Arquivo para testar os dados treinados do XOR |

### Testando XOR
```shell
gcc teste_xor.c -lfann -lm -o teste_xor && ./teste_xor
gcc run_xor_teste.c -lfann -lm -o run_xor_teste && ./run_xor_teste
```
------

### Arquivos AND

| Arquivo        | O que é?     |
| ------------- |:-------------:| 
| and.data      | Arquivo com os dados de treinamento, neste exemplo foram utilizados o aprendizado de AND |
| teste_and.c   | Arquivo responsável pelo treinamento dos dados do AND |
| run_and_teste.c | Arquivo para testar os dados treinados do AND |

### Testando AND
```shell
gcc teste_and.c -lfann -lm -o teste_and && ./teste_and
gcc run_and_teste.c -lfann -lm -o run_and_teste && ./run_and_teste
```
------

### Arquivos OR

| Arquivo        | O que é?     |
| ------------- |:-------------:| 
| or.data      | Arquivo com os dados de treinamento, neste exemplo foram utilizados o aprendizado de OR |
| teste_or.c   | Arquivo responsável pelo treinamento dos dados do OR |
| run_or_teste.c | Arquivo para testar os dados treinados do OR |

### Testando OR
```shell
gcc teste_or.c -lfann -lm -o teste_or && ./teste_or
gcc run_or_teste.c -lfann -lm -o run_or_teste && ./run_or_teste
```
------

### Arquivos NAND

| Arquivo        | O que é?     |
| ------------- |:-------------:| 
| nand.data      | Arquivo com os dados de treinamento, neste exemplo foram utilizados o aprendizado de NAND |
| teste_nand.c   | Arquivo responsável pelo treinamento dos dados do NAND |
| run_nand_teste.c | Arquivo para testar os dados treinados do NAND |

### Testando NAND
```shell
gcc teste_nand.c -lfann -lm -o teste_nand && ./teste_nand
gcc run_nand_teste.c -lfann -lm -o run_nand_teste && ./run_nand_teste
```
------