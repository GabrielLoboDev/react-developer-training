# Media Query em CSS

É a utilização de Media Types com uma ou mais expressões envolvendo características de uma media para definir formatações para diversos dispositivos. Os browsers ou as aplicações lêem as expressões definidas na Query, caso o dispositivo em questão se encaixe nessas requisições o CSS será aplicado.

## Media types

Os media types definem para que tipo de media um certo código CSS é direcionado. O HTML foi gerado para ser portátil, ou seja, lido e interpretado por qualquer tipo de dispositivo. Só que cada dispositivo exibe o HTML de uma maneira, devido a fatores como, por exemplo, as dimensões da tela. Supondo que visitamos um site através de um desktop, ele não terá a mesmo reação de que se visitarmos por um dispositivo mobile.

## Utilizado Media Queries

```html
<style>
    @media (max-width: 600px)
    {
        .facet_sidebar
        {
            display: none;
        }
    }
</style>
```