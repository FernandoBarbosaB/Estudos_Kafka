## ⚙️ Estudos com Kafka


Este documento demonstra o desenvolvimento técnico de uma aplicação consumindo dados de um 'simulador' de temperatura de sensores através de um evento de streaming.

Utilizando como Python e Kafka


## 📦 Desenvolvimento


![image](https://user-images.githubusercontent.com/116772002/224562367-e3deb671-b24e-4d46-9da4-7af720df7be1.png)



Realizado a geração de dados de temperatura utilizando python para gerar esses dados para simulação...dados de medição de temperatura de equipamentos industriais
Utilizando Kafka para realizar a coleta de forma continua dos dados dos sensores.
Consumindo os registros de um cluster Kafka para análise dos dados.


### 🔩 Layout dos arquivos


|   **variável**  | **tipo** |    **descrição**   |
|:---------------:|:--------:|:------------------:|
|    id_sensor    |  string  | identificador do sensor       |
| id_equipamento  |  string  |  identificador do equipamento |
|     sensor      |  string  |    tag sensor                 |
|   data_evento   |  string  |      data da leitura          |
|   temperatura   |  float   |     aferição da temperatura   |

## 🛠️ Construído com

* [Python](https://www.python.org/) 
* [Apache Kafka](https://kafka.apache.org/) - Plataforma de Streaming



## 🏃 Autor


* **Fernando Barbosa** - *Engenheiro de Dados Jr* - [github](https://github.com/FernandoBarbosaB)
