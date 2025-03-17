# Fase 5 - FarmTech: Machine Learning e Computação em Nuvem

## Link - Vídeo de Demonstração
Link(https://www.youtube.com/watch?v=x6MZ3CZdJxc)

## Integrantes do Grupo
- Gabriela da Cunha Rocha (rm561041@fiap.com.br)
- Gustavo Segantini Rossignolli (rm560111@fiap.com.br)
- Thiago Lima Bernardes (rm560085@fiap.com.br)
- Vitor Lopes Romão (rm560111@fiap.com.br)

---

## Entrega 1: Machine Learning
### Descrição
Esta entrega tem como objetivo prever o rendimento de safras agrícolas, utilizando análise exploratória, clusterização e cinco modelos preditivos diferentes. A base de dados utilizada é o arquivo `crop_yield.csv`, fornecido no portal.

### Passos Realizados
1. **Análise Exploratória**:
   - Familiarização com os dados.
   - Identificação de tendências e outliers.
2. **Clusterização**:
   - Criação de clusters baseados em variáveis como umidade e temperatura.
3. **Modelagem Preditiva**:
   - Construção de cinco modelos preditivos utilizando diferentes algoritmos de Machine Learning.
   - Avaliação dos modelos com métricas adequadas.

### Resultados
Os resultados estão documentados no arquivo Jupyter, linkado abaixo, com detalhes sobre as análises, conclusões e limitações.

### Links
- [Notebook Jupyter](#) *(Insira o link do notebook executável)*
- [Vídeo Demonstrativo no YouTube](#) *(Insira o link do vídeo "não listado")*

---

## Entrega 2: Estimativa de Custos na AWS
### Descrição
Esta entrega tem como objetivo analisar e comparar os custos de hospedar uma API em diferentes regiões da AWS, com base nos seguintes requisitos:
- **Configurações**: 2 CPUs, 1 GiB de RAM, até 5 Gbps de rede, 50 GB de armazenamento (HD).
- **Regiões Comparadas**: São Paulo (BR) e North Virgínia (EUA).

### Passos Realizados
1. Utilização da AWS Pricing Calculator para estimar os custos.
2. Comparação dos valores entre as duas regiões.
3. Justificativa da solução escolhida, considerando restrições legais e desempenho.

### Análise
| Região                  | Custo Mês (USD)  | Custo Anual (USD)  | Latência Esperada | Observações                       |
|-------------------------|------------------|--------------------|-------------------|-----------------------------------|
| São Paulo (BR)          | $11.22           | $134.64            | Baixa             | Atende às restrições legais.      |
| Virgínia do Norte (EUA) | $6.88            | $82.56             | Alta              | Não atende restrições legais.     |

### Resultado
A solução escolhida foi **São Paulo (BR)**, devido a restrições legais para armazenamento no exterior, a região de São Paulo seria a escolha mais adequada, mesmo que o custo seja ligeiramente maior. Além disso, a proximidade geográfica pode garantir menor latência e acesso mais rápido aos dados dos sensores.

### Links
- [Vídeo Comparativo no YouTube](https://youtu.be/orOHmphvsqI) *(não listado)*

## Gráficos e Imagens
### Regiões utilizadas:
![image](https://github.com/user-attachments/assets/73922834-4782-4d9d-9fb7-990509dec722)
![image](https://github.com/user-attachments/assets/db18a01a-2ca0-4b16-b726-99d0b67859b9)

### Configurações básicas:
![image](https://github.com/user-attachments/assets/11391925-f975-4b10-ad77-b1ea8e517ec3)
![image](https://github.com/user-attachments/assets/5fc87c35-0dc4-4fda-976b-33d035e58b8d)
![image](https://github.com/user-attachments/assets/4832caa1-48fe-4909-848c-e524fb370410)

### Calculos de valores:
#### N. Virginia
![image](https://github.com/user-attachments/assets/a873ae98-02c1-46f6-8631-9c7b3b75bc1c)
![image](https://github.com/user-attachments/assets/1720d2b9-4eea-46d7-af94-cd98043788f7)

#### São Paulo
![image](https://github.com/user-attachments/assets/1e229118-6687-4ac7-a872-da35aea6d526)
![image](https://github.com/user-attachments/assets/8ff448f1-128a-4d05-9cf4-c67194b08c6c)

### Valores totais:
#### N. Virginia
![image](https://github.com/user-attachments/assets/6149f136-a1d4-4f20-8051-5ca0ab8664c0)
#### São Paulo
![image](https://github.com/user-attachments/assets/5feb1c3a-ad49-4e70-9b03-fbbd52b4e2df)

### Restrição de instâncias e armazenamentos na mesma região
![image](https://github.com/user-attachments/assets/93b65166-eea2-4fe6-9921-f2a259cb200e)

---

## Conclusão
- **Entrega 1**: Modelos de Machine Learning implementados com análises robustas.
- **Entrega 2**: Comparação de custos com justificativas técnicas para a escolha da melhor região.
- **Próximos Passos**: Continuação do desenvolvimento com foco em explorar ainda mais soluções na nuvem.

---

*Observação: Este repositório segue as diretrizes da FIAP e não será atualizado após o prazo de entrega.*
