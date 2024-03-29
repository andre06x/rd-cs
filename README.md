# CustomerSuccess

## Como rodar os testes

É necessário ter instalado o Node.js junto ao npm

No terminal, execute os comandos:

```
cd rd-cs
npm install
npm test
```

## Ordem de solução:

- Remover os `customersAway` de `customerSuccess`.
- Ordenar os `customerSuccess` pelo score de menor para o maior.
- Percorrer os `customerSuccess` filtrando os `customers` com o `customerSucess score` maior ou igual ao `customer score` e que o `customer` já não tenha sido atendido.
- Inserir dados da filtragem junto ao `idCustomerSuccess` ao array de ranking.
- Adicionar os `customers` filtrados a um conjunto de identificação.
- Ordenar o ranking pelo tamanho de maior para o menor.
- Verificar se no ranking na primeira posição e na segunda possuem o mesmo tamanho, caso sim retorna 0.
- Caso não tenha esse empate, retorna o `idCustomersSucess` da primeira posição do ranking.
