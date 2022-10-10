# Projeto Urna eletrônica do curso B7Web
Esta é a versão 1.0.0 do projeto de uma urna eletronica feito no curso de JavaScript do curso  B7web. O Objetivo é "simular" o funcionamento de uma Urna de votação.

## Funcionamento
Crie um JavaScrip ou Json com os candidatos a Governador e Presidente.
<br />Você pode definir quantos candidatos quiser desde que a variavel se chame **etapas**, Exemplo abaixo:

```go
let etapas = [
    {
        titulo: 'VEREADOR',
        numeros: 5,
        candidatos: [
            {
                numero: '38111',
                nome: 'Farley Lima',
                partido: 'ABC',
                fotos:[
                    {url:'38111.jpg', legenda: 'Vereador'}
                ]
            },
        ]
    },
    {
        titulo: 'PREFEITO',
        numeros: 2,
        candidatos: [
            {
                numero: '99',
                nome: 'Ciclano',
                partido: 'ABC',
                vice: 'Cic',
                fotos:[
                    {url:'99.jpg', legenda: 'Prefeito'},
                    {url:'99_2.jpg', legenda: 'Vice-Prefeito', small: true}
                ]
            },

        ]
    }
];
```

### .GIf EXEMPLO 
![snackbar](https://github.com/juniornsantos/urna_eletronica/blob/main/giff.gif)


## Support
Você pode obter suporte da comunidade por meio de:

<a href = "https://api.whatsapp.com/send?phone=5588998686890"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank"></a>
<a href = "https://t.me/JuniorNogueira"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" target="_blank"></a>
