# 4 Solução proposta

## 4.1 Sistema proposto

Com o objetivo de mitigar o problema proposto anteriormente, este trabalho se propõe a desenvolver um dispositivo embarcado com a capacidade de ler as taxas de poluentes no ar das regiões onde os ciclistas trafegam. Esses dados serão coletados pelo servidor e transformados em informação, tornando possível a visualização da mesma, bem como localizar _hotspots_ de má qualidade do ar. O sistema também será capaz de indicar se o ciclista está inalando mais ar poluído do que um usuário de transportes públicos ou privados e se o dano causado supera os benefícios para a saúde consequentes do exercício, além de sugerir rotas que desviem das regiões de picos de poluição.

O dispositivo embarcado na bicicleta visa ser portátil, de baixo consumo de energia, alta disponibilidade e persistir os dados no servidor. Para isso, ele se comunicará com a internet através do LoRaWAN (_Low Power Wide Area Network_), que consiste, como exposto nos capítulos anteriores, em uma rede de grande alcance e baixo consumo de energia.

## 4.2 Premissas

1. A pesquisa será baseada em dados obtidos no estado do Rio de Janeiro.
2. Será usada a rede LoRa.
3. Um protótipo será feito utilizando microcontroladores e sensores de baixo consumo de energia.
4. O grupo que será estudado na pesquisa será formado por ciclistas.
5. O dispositivo embarcado desenvolvido precisa ser portátil para acoplar na bicicleta.
6. Deverá ser desenvolvido uma ferramenta de visualização das informações.
7. O projeto deverá considerar a localização do usuário.