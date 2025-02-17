# Plantio_direto
Este repositório armazena código utilizado em um experimento que tenta detectar de foram não supervisionada solo mecanicamente revirado com imagens de satélite de baixa resolução (30m por pixel). Utilizando U-Net e K-Means em imagens de 16 bandas espectrais com baixa cobertura vegetal. A detecção do solo arado será utilizada em estudos futuros de serie histórica.

O Step_1 é script para baixar baixa da região goiana com 16 bandas espectrais e notebooks com as seguintes funcionalidades. Do Step 2 até o 4 correspondem aos notebooks responsáveis por calcular os índices, mascaras e divisão do dataset. O Step_5 e 6 testam diferentes combinações de hiperparametros.
