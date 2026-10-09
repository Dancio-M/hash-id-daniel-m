# Demo — Hash ID

## Projeto
Ferramenta CLI em Python que sugere formatos de hash a partir de prefixo,
comprimento e conjunto de caracteres, apresentando candidatos e confiança.

## Resultados
Implementei os desafios 1.1 a 2.3: novas regras de identificação, saída JSON,
entrada por arquivo ou stdin, modos hashcat e alertas para entradas que
provavelmente não são hashes. Os 57 testes e as verificações de lint passaram.

## Conclusão
A identificação por formato ajuda a orientar a análise, mas o comprimento
sozinho não confirma o algoritmo. A ferramenta apresenta candidatos e explica
os sinais usados.

## Vídeo
[Assistir à demonstração](https://www.youtube.com/watch?v=y5H9iuGDhto)