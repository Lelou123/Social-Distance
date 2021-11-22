# Social-Distance
Projeto de IOT distância social na pandemia 

Link Tinkercad: https://www.tinkercad.com/things/iAhF3wO8Wg2-distancia-social/


## Sobre o projeto:
  Esse é um projeto que tem como objetivo manter uma distância segura entre o usuário e outras pessoas em um período como o atual de pandemia.


### Componentes Utilizados:
- 1x Arduino Uno R3.
- 1x Pontenciômetro.
- 4x Resistores 220ohm.
- 1x Sensor de distância ultrassônico.
- 1x Sensor PIR.
- 1x Buzzer.
- 1x Led RGB.
- 1x LCD 16x2.
		

			
## Explicação importante sobre funcionamento:

   O pontenciômetro é utilizado para regular a claridade do display LCD impedindo bugs, deve ser mantido no quanto deseja a emissão de luz.
   Em caso de não apresentar imagem verifique o potenciômetro e o reinicie se necessário.

### Movimentação:		
			
PIR (Sensor de movimento)
- Se o PIR encontrar algum movimento sera considerado humano e irá retornar um valor 1 caso não o valor será 0 e nada ocorrerá.
			
Sensosr de distância ultrassônico:
- Se o resultado do PIR for = 1 e distancia do humano for menor que 200 cm irá emitir uma onda de som que dispará o buzzer e display emitindo um alerta para se afastar.
  
  
  ![Projeto IOT](https://user-images.githubusercontent.com/55301440/142933470-da6fa150-e9d3-4def-bfa1-de4c32cedd73.gif)
