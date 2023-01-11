# Fundamentos da Programação 2022 2023 - [IADE - UE](https://www.iade.europeia.pt/) <!-- omit in toc -->

Testes input/output referentes ao projeto em [https://github.com/IADE-FP/IADE-FP-2022-2023-Projeto].

Está incluído um executável (para Linux) exemplo de implementação.

Além das instruções previstas, inclui uma instrução `X`, que mostra o estado do tabuleiro, caso esteja um jogo a decorrer.

## Utilização dos testes

1. Executar o teste com o programa compilado

```
./main < iotests/RJ.in > RJ.mine.out
```

2. Comparar o resultado gerado com o resultado em iotests.

A comparação pode ser feita no VSCode, tal como indicado no enunciadodo projeto. Pode também ser feita no terminal, recorrendo ao comando `diff`:

```
diff iotests/RJ.out RJ.mine.out
```

Se os ficheiros forem iguais, não deve surgir output.

O `diff` pode ainda mostrar os dois ficheiros lado a lado, indicando as diferenças:

```
diff -y iotests/RJ.out RJ.mine.out
```
