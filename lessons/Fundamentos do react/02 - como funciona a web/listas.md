# Listas em HTML

As listas são muito importantes quando queremos listar alguns itens no site e também para a criação de menu de navegação;

## Tipos de listas

- Listas ordenadas
- Listas desordenadas
- Listas por definição

### Lista ordenada
``` html
<ol start='' type=''>
    <li></li>
    <li></li>
    <li></li>
</ol>
```
- `start`: define onde a lista deve começar.
- `type`: define o tipo da lista, ex.: Letras, númerica ou algarismos Romanos.

### Lista não ordenada
``` html
<ul>
    <li></li>
    <li></li>
    <li></li>
</ul>
```

### Lista por definição
``` html
<dl>
    <dt>Carro</dt>
        <dd>Veículo de 4 rodas</dd>
    <dt></dt>
        <dd>Veículo de 2 rodas</dd>
</dl>
```