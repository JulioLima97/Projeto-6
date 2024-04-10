Don't read Portuguese? [Read this page in English](https://github.com/JulioLima97/Projeto-6/blob/main/README-en.md)
# Projeto-6

## Descrição do Projeto
Neste projeto eu estou trabalhando como analista da Zuber, uma nova empresa de compartilhamento de caronas que está sendo lançada em Chicago. Minha tarefa é encontrar padrões nas informações disponíveis. Eu quero entender as preferências dos passageiros e o impacto de fatores externos nas corridas.  
Trabalhando com um banco de dados, você analisará dados de concorrentes e testará uma hipótese sobre o impacto do clima na frequência das viagens.

## Descrição dos dados
Um banco de dados com informações sobre corridas de táxi em Chicago:

tabela `neighborhoods`: dados sobre os bairros da cidade
- `name`: nome do bairro
- `neighborhood_id`: código do bairro

tabela `cabs`: dados sobre os táxis
- `cab_id`: código do veículo
- `vehicle_id`: a identificação técnica do veículo
- `company_name`: a empresa proprietária do veículo

tabela `trips`: dados sobre corridas
- `trip_id`: código da corrida
- `cab_id`: código do veículo que opera a corrida
- `start_ts`: data e hora do início da corrida (tempo arredondado para a hora)
- `end_ts`: data e hora do final da corrida (tempo arredondado para a hora)
- `duration_seconds`: duração da corrida em segundos
- `distance_miles`: distância percorrida em milhas
- `pickup_location_id`: código do bairro de retirada
- `dropoff_location_id`: código do bairro de entrega

tabela `weather_records`: dados sobre o clima
- `record_id`: código de registro meteorológico
- `ts`: grava data e hora (tempo arredondado para a hora)
- `temperature`: temperatura quando o registro foi feito
- `description`: breve descrição das condições meteorológicas, ex. "chuva leve" ou "nuvens esparsas"

## Bibliotecas
- pandas
- numpy
- scipy
  
Nota: Este projeto foi desenvolvido com base na orientação que recebi para aprimorar meu raciocínio lógico enquanto aluno. Como resultado, mantive incluso todas as ordens solicitadas relacionadas à orientação para realização dos cálculos necessários.
