# desarrolloSW
var nuevoParrafo = document.createElement("p"); // creo el nuevo elemento
nuevoParrafo.innerText = "Párrafo nuevo";

// Se va a crear el elemento con respecto al `h1 `del HTML, la posición se define con respecto a ese h1.

nodoH1.insertAdjacentElement('afterend', nuevoParrafo);   // agrego un elemento creado
nodoH1.insertAdjacentHTML('afterend', '<p id="two">Otro Párrafo</p>')
