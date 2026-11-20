# ads_prova_sistemas_embarcados
## Repositório destinado à prova de sistemas embarcados

### Integrantes
- Felipe dos Santos Fogaça
- Victor Takeyoshi Kieper Ezaki

### Projeto
Nosso projeto foi pensado em automatizar tarefas do dia a dia para que assim tenhamos mais comodidade e segurança.
- Geralmente os indivíduos à noite costumam ir de um cômodo à outro para beber água ou outra necessidade. Pensando nisso utilizamos o Sensor Ultrassônico para detectar a presença de algum indivíduo e ativar o Led que estará representando a lâmpada do ambiente.
- Ao invés de esperar começar a suar e ter o trabalho de ligar o ventilador ou ar condicionado utilizamos o Sensor de Temperatura e Umidade DHT11 para que quando o ambiente atingir 24ºC ligue um dos aparelhos conectados, em nosso projeto, utilizamos o Micro Servo Motor para simular.
- Para trazer segurança à nossa residência, utilizamos o Piezo para emitir o alerta de que a barreira criada por um LDR 5mm e o Laser, como fonte de energia foi ultrapassada por algo.

### Sensores
- Sensor Ultrassônico: O utilizamos para detectar a presença de algum indivíduo ao passar pelo ambiente que queremos iluminar.
  - R$15,00 [Acesse o Anúncio](https://www.mercadolivre.com.br/modulo-sensor-ultrassonico-distancia-hc-sr04-para-arduino/p/MLB64164978?pdp_filters=item_id%3AMLB5130062737&from=gshop&matt_tool=56164162&matt_word=&matt_source=google&matt_campaign_id=22090193744&matt_ad_group_id=194474654154&matt_match_type=&matt_network=g&matt_device=c&matt_creative=792355615410&matt_keyword=&matt_ad_position=&matt_ad_type=pla&matt_merchant_id=735128761&matt_product_id=MLB64164978-product&matt_product_partition_id=2495059736307&matt_target_id=pla-2495059736307&cq_src=google_ads&cq_cmp=22090193744&cq_net=g&cq_plt=gp&cq_med=pla&gad_source=4&gad_campaignid=22090193744&gbraid=0AAAAAD93qcDITpmvuw7Snlw20cEm4ilZq&gclid=Cj0KCQiA2frXBhC_ARIsAPTFcdOs1VgUxVy7q1RArAYtnQkxLoaQ6JUkKtoDWFLnFAitoeOBHg4Y2_oaAr5PEALw_wcB)
- Sensor de Temperatura e Umidade DHT11: O utilizamos para capturar a temperatura do ambiente e assim ativar o aparelho conectado ao ativar a temperatura de 24ºC
  - R$12,98 [Acesse o Anúncio](https://www.mercadolivre.com.br/sensor-dht11-duaitek-temperatura-umidade-arduino-0-50c-20-90/p/MLB32624358?pdp_filters=item_id%3AMLB5448241421&from=gshop&matt_tool=49835134&matt_word=&matt_source=google&matt_campaign_id=22090354217&matt_ad_group_id=194474655594&matt_match_type=&matt_network=g&matt_device=c&matt_creative=792355616874&matt_keyword=&matt_ad_position=&matt_ad_type=pla&matt_merchant_id=735125422&matt_product_id=MLB32624358-product&matt_product_partition_id=2499513569252&matt_target_id=pla-2499513569252&cq_src=google_ads&cq_cmp=22090354217&cq_net=g&cq_plt=gp&cq_med=pla&gad_source=4&gad_campaignid=22090354217&gbraid=0AAAAAD93qcBZ4hSi0G_JHr4KEMGgMquBP&gclid=Cj0KCQiA2frXBhC_ARIsAPTFcdNlvYuD-VTptE1GQ99K5vZ7Z-BJkTYt8yTVHmVSgkAkw93NZljxJ5waAleKEALw_wcB)
 - Sensor LDR 5mm: O utilizamos, pois o sensor é capaz de acionar o Piezo quando algo interromper a luminosidade fornecida pelo LED. 
   - R$0,50 [Acesse o Anúncio](https://www.piscaled.com.br/resistor-dependente-de-luz-sensor-de-luminosidade-ldr-5mm?utm_source=Site&utm_medium=GoogleMerchant&utm_campaign=GoogleMerchant&gad_source=4&gad_campaignid=19749890616&gbraid=0AAAAAC9K6bYtdAR5ZjultlzjjsMqq_boS&gclid=Cj0KCQiA2frXBhC_ARIsAPTFcdNRs5OFacyqCzrVNtP0TfPH3rC-ZAx615evuDxIdwdvFf099NloCOIaAprTEALw_wcB)

### Atuadores
 - LED: Utilizamos o Led como se fosse a lâmpada do do ambiente à ser acesa quando o Sensor Ultrassônico detectar a presença de alguém.
   - R$0,30 [Acesse o Anúncio](https://www.piscaled.com.br/led-alto-brilho-branco-5mm?utm_source=Site&utm_medium=GoogleMerchant&utm_campaign=GoogleMerchant&gad_source=4&gad_campaignid=19749890616&gbraid=0AAAAAC9K6bYtdAR5ZjultlzjjsMqq_boS&gclid=Cj0KCQiA2frXBhC_ARIsAPTFcdNbkG8gDHqXu0Pp6r8EwtXhWPvrTVZFrfORkIvfK4BU3JHfcdeoM8UaAt7QEALw_wcB)
 - Micro Servo Motor: O utilizamos para simular o Ventilador/Ar condicionado que deve ser ativado quando o DHT11 detectar que o ambiente atingiu 24ºC.
   - R$11,60 [Acesse o Anúncio](https://www.piscaled.com.br/micro-servo-motor-9g-sg90-towerpro-acessorios?utm_source=Site&utm_medium=GoogleMerchant&utm_campaign=GoogleMerchant&gad_source=4&gad_campaignid=19749890616&gbraid=0AAAAAC9K6bYtdAR5ZjultlzjjsMqq_boS&gclid=Cj0KCQiA2frXBhC_ARIsAPTFcdO4gLS89Ene4bGOK-QyYfXlbneaW5rFD-nvX10n5XkAf5TkjvSuLxgaAnt2EALw_wcB)
 - Piezo: Foi utilizado para emitir o alarme quando a barreira for rompida por algo.
   - R$9,67 [Acesse o Anúncio](https://www.google.com/aclk?sa=L&ai=DChsSEwi-3KnErZWYAxVAVUgAHcKrBSIYACICCAEQCxoCY2U&co=1&ase=2&gclid=Cj0KCQiA2frXBhC_ARIsAPTFcdNzm3dR39jM00bdSgxPp1OR300borseF03OXobmUxCh-rvwtn7GXdQaAqnZEALw_wcB&cid=CAASWuRoETiuoUm9dGC33n9xUTY9mpgGcdE0X3CfW5QMcr50ZldrJhF-hKVTNezGdL0IPTKLjtRWX-O4aRYtmMfPjmcR8ncuRIPK7j3AhlyweyzhN9zupDw4cOprCw&cce=2&category=acrcp_v1_32&sig=AOD64_2zXadMTT-IKrOPDIfAjHH_jGKxDQ&ctype=5&q=&nis=4&ved=2ahUKEwjt76fErZWYAxW3EbkGHQHrIYEQ9aACKAB6BAgMEGU&adurl=)
 - Laser: Utilizado como fonte de luminosidade para o LDR 5mm a fim de gerar a barreira.
   - R$1,92/un no kit de 5un por R$9,59 [Acesse o Anúncio](https://www.google.com/aclk?sa=L&ai=DChsSEwjxtpHfrZWYAxUXTkgAHc2wA7sYACICCAEQAxoCY2U&co=1&ase=2&gclid=Cj0KCQiA2frXBhC_ARIsAPTFcdMlWjpU1AbSUdOm6i2POlfJ4YgVd44M_2kwRBI3BhqOe0A1aXa7esQaAih5EALw_wcB&cid=CAASWuRo1pXiALRzOwh7urNb3j0vbjReKS2cwYtG3J-Ks0cLP4uuipaJoGZ4-2lKjHC_YC6okXQDTSrnRUuIfmDdVs4Y1MIKGNw_lgi4ZEl56XWabvS3B1Px-5ngew&cce=2&category=acrcp_v1_32&sig=AOD64_1sXUmJSXWH5-Ebw4houfHzNYw9CA&ctype=5&q=&nis=4&ved=2ahUKEwi7uY_frZWYAxVCBbkGHVWUNHoQ9aACKAB6BAgMECM&adurl=)
