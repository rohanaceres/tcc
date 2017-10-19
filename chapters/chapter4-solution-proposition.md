# Solução proposta

## Sistema proposto

Com o objetivo de mitigar o problema proposto anteriormente, este trabalho se propõe a desenvolver um dispositivo embarcado com a capacidade de ler as taxas de poluentes no ar das regiões onde os ciclistas trafegam. Esses dados serão coletados pelo servidor e transformados em informação, tornando possível a visualização da mesma, bem como localizar _hotspots_ de má qualidade do ar. O sistema também será capaz de indicar se o ciclista está inalando mais ar poluído do que um usuário de transportes públicos ou privados e se o dano causado supera os benefícios para a saúde consequentes do exercício, além de sugerir rotas que desviem das regiões de picos de poluição.

O dispositivo embarcado na bicicleta visa ser portátil, de baixo consumo de energia, alta disponibilidade e persistir os dados no servidor. Para isso, ele se comunicará com a internet através do LoRaWAN (_Low Power Wide Area Network_), que consiste, como exposto nos capítulos anteriores, em uma rede de grande alcance e baixo consumo de energia.

## Metodologia

Esta pesquisa utilizará o método dedutivo, desenvolvendo cadeias de raciocínio com premissas bem definidas para chegar a uma conclusão clara e objetiva. Além disso, este trabalho consiste em uma pesquisa quantitativa descritiva, ou seja, visa resolver um problema prático específico; analisar os dados, suas relações e impactos de forma concisa; e envolver estratégias de coleta de dados, neste caso, através de sensores, por amostragem não probabilística intencional, onde o grupo estudado será formado por ciclistas.

## Premissas

1. A pesquisa será baseada em dados obtidos no estado do Rio de Janeiro.
2. 