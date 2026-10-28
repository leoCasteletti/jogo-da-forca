# Jogo da Forca em C

Jogo da forca no terminal, feito no curso técnico do SENAI.

- Palavra sorteada de um arquivo (`palavras.txt`)
- 5 erros e o jogador é enforcado
- Desenho da forca a cada rodada
- Ao final, opção de cadastrar uma palavra nova no arquivo

## Rodando

```bash
gcc forca.c -o forca
./forca
```

O arquivo `palavras.txt` precisa estar na mesma pasta. A primeira linha é a quantidade de palavras; as seguintes, uma palavra por linha, em maiúsculas.

## Conceitos praticados

Ponteiros, vetores de `char`, leitura e escrita de arquivos (`fopen`, `fscanf`, `fprintf`, `fseek`), funções em arquivo de cabeçalho e números aleatórios com `srand`/`rand`.
