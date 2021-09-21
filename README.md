# Converso-de-Ano-Luz-em-Km

function Converter() {
  var valorElemento = document.getElementById("valor");
  var valor = valorElemento.value;
  var valorEmAnosLuz = parseFloat(valor);
  var valorEmKm = valorEmAnosLuz / 9;
  console.log(valorEmAnosLuz);

  var elementoValorConvertido = document.getElementById("valorConvertido");
  var valorConvertido = " A distância em Ano-Luz é " + valorEmAnosLuz;
  elementoValorConvertido.innerHTML = valorConvertido;
}

function Converter2() {
  var valorElemento2 = document.getElementById("valor2");
  var valor2 = valorElemento2.value;
  var valorEmDoKm = parseFloat(valor2);
  var valorEmAnosLuz = valorEmDoKm * 9;
  console.log(valorEmDoKm);

  var elementoValorConvertido2 = document.getElementById("valorConvertido");
  var valorConvertido2 = " A distância em Km é " + valorEmAnosLuz;
  elementoValorConvertido2.innerHTML = valorConvertido2;
}
