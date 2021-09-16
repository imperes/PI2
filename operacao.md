# Operação

Durante as etapas anteriores, foi descrito todo o processo de construção do projeto para que fosse possível chegar a essa última etapa da abordagem CDIO. 
As intruções e modo de operação do sistema serão descritas e demonstradas nessa etapa.

### Manual

Para a inicialização do sistema, conecta-se o Arduino ao computador via USB e por meio da IDE do Arduino faz-se a compilação do código fonte do sistema. A comunicação com o usuário é realizada pelo monito serial do Arduino, no qual serão exibidas as mensagens de comando enviados pelo teclado. As teclas de controle e suas respectivas ações são exibidas a seguir:

![Manual](./Figuras/manual.png)

Menu de comandos


Como podemos verificar, o objetivo principal do trabalho foi alcançado. A aplicação de diversas tecnologias com o intuito de automatizar a residência maquete foi concluido, o sistema de alarme funcionando, e valores de temperatura e umidade devidamente apresentados.
Erros e Problemáticas

Como todo protótipo, o produto uma vez que é atendido o seu objetivo geral, está passível de erros e questões problemáticas secundárias. Erros estes de segunda ordem, ou seja, que não afetam o funcionamento principal do produto. Neste texto ressalto duas questões problemáticas principais relacionadas ao funcionamento do projeto acima demonstrado. A primeira é a interferência no servo motor vísivel pelas trepidações a cada momento de leitura do módulo Bluetooth. E a segunda, está relacionada ao acionamento involuntário e aleatório de algumas luzes de determinados comôdos, ocasionados no momento de troca da tela no aplicativo. Erro este gerado, pois, na troca da tela o dispositivo é desconectado temporariamente e reconectado em seguida, essa reconexão gera então esse erro. Estas questões são pontos de incentivo para melhor estudo e pesquisa futuros, utilizando os equipamentos necessários para verificá-los e posteriormente atualizar e implementar tais melhorias a maquete.
