# Cronômetro - Promoções
Esse plugin foi projetado pensando em libertar de uma vez por todas nosso famoso problemas com data.
Agora podemos criar um "contagem regressiva" de maneira extremamente simples, que funciona com qualquer timer (Anos, Semanas, dias, horas, minutos e segundos).

### Instalação do plugin
Para iniciar o plugin basta instalar o script no footer do seu website. A partir do carregamento você já tem a função global em seu browser.

    <script src='countdown.js'></script>

### Como utilizar
Dentro do seu Object Window agora tem uma função chamada **"timerCount"**

    window.timerCount() // {message: "Expired"}
    window.timerCount('') // {message: "Expired"}
    window.timerCount('2020-10-29T18:00:00') // {dias: 0, horas: 5, minutos: 44, segundos: 4}
    setInterval(() => { window.timerCount('2020-10-29T18:00:00') // {dias: 0, horas: 5, minutos: 44, segundos: 4} }, 1000)
