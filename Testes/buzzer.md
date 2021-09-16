# Teste do Buzzer

O buzzer passivo utilizado é capaz de reproduzir sons de diferentes frequências, podendo gerar difeferentes melodias. Durante os testes foi observado que o buzzer possui acionamento PNP, ou seja, desliga em nível lógico alto.

Para enviar a frequência sonora que será emitida pelo buzzer, utiliza-se a função tone(pino, frequência) e em seguida quando for necessário desliga-lo deve-se usar as funções noTone(pino) e digitalWrite(pino, HIGH), como é possível visualizar no teste abaixo. Para reproduzir um som com frequência variando, como uma sirene, será empregada uma função seno.


