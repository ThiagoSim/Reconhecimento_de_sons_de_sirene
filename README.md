# Reconhecimento de sons de sirene
Utilização do modelo LSTM para classificação de sons de sirene.


- frequência dos áudios 44,2 KHz (fiz dowmsamplig para 2500 Hz)
- há 390 exemplos de sons de sirene e 390 de outros sons
- foi realizada normalização dos dados
- com extração de features MFCC, a acurácia obtida é alta (>98%) com apenas 2 coef. MFCC
- com dados brutos, a LSTM não convergiu (é necessário testar com números maiores de hidden units e com mais camadas)

Próximos passos: embarcar o modelo no microcontrolador
