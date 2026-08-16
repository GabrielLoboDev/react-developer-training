# Tabelas em html

As tabelas são listas de dados em duas dimensões e são compostas por linhas e colunas. Portanto, são muito utilizadas para apresentar dados de uma forma organizada.

## Estrutura básica de uma tabela
``` html
<table border='1'>
    <thead>
        <tr>
            <th>Modelo</th>
            <th>Marca</th>
            <th>Valor</th>
        </tr>
    </thead>
    
    <tbody>
        <tr>
            <td>Peugeot 207</td>
            <td>Peugeot</td>
            <td>20.000</td>
        </tr>

        <tr>
            <td>Corsa</td>
            <td>Chevrolet</td>
            <td>19.000</td>
        </tr>
    </tbody>

    <tfoot>
        <tr>
            <td colspan="3">Valor total dos carro: 39.000</td>
        </tr>
    </tfoot>
</table>
```
- `border`: Define o tipo da borda da tabela.
- `colspan`: Mescla as colunas selecionas.
- `align`: Define o tipo de alinhamento nas células.