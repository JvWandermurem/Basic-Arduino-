# Arduino IDE
O código abaixo é o primeiro contato com a placa Arduido representando um "Hello Wolrd" da placa.


``` c++ 

void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  // turn the LED on (HIGH is the voltage level)
  delay(500);                      // wait for a second
  digitalWrite(LED_BUILTIN, LOW);   // turn the LED off by making the voltage LOW
  delay(500);                      // wait for a second
}

```
Abaixo há um print da tela mostrando o código no IDE arduino
<div align="center">
<sub><a name="f"></a>Figura 1- Codigo</sub>
<img src="\Assets\Codigo.png" width="100%">
<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>
<p>

Video demonstrativo do funcionamento da placa arduino, será necessário o download para visualisação do vídeo.

<div align="center">
  <a href="https://github.com/JvWandermurem/Basic-Arduino-/raw/refs/heads/main/Assets/gif%20arduino.mp4" download>
    Clique aqui para baixar o vídeo
  </a><br>
</div>

Abaixo há um print da tela mostrando o sistema em funcionamento
<div align="center">
<sub><a name="f"></a>Figura 2- arduino</sub>
<img src="\Assets\telaArduino.png" width="100%">
<sup>Fonte: Material produzido pelos autores (2024)</sup>
</div>
<p>
  