# Fase 5 - FarmTech: Machine Learning e Computação em Nuvem

## Integrantes do Grupo
- Gustavo Segantini Rossignolli (gsrxyz@gmail.com)
- [Adicione outros integrantes, se houver]

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
- **Regiões Comparadas**: São Paulo (BR) e Virgínia do Norte (EUA).

### Passos Realizados
1. Utilização da AWS Pricing Calculator para estimar os custos.
2. Comparação dos valores entre as duas regiões.
3. Justificativa da solução escolhida, considerando restrições legais e desempenho.

### Análise
| Região                  | Custo Mês (USD)  | Custo Anual (USD)  | Latência Esperada | Observações                       |
|-------------------------|------------------|--------------------|-------------------|-----------------------------------|
| São Paulo (BR)          | $17.38           | $208.56            | Baixa             | Atende às restrições legais.      |
| Virgínia do Norte (EUA) | $10.13           | $121.56            | Alta              | Não atende restrições legais.     |


A solução escolhida foi **São Paulo (BR)**, devido a restrições legais para armazenamento no exterior, a região de São Paulo seria a escolha mais adequada, mesmo que o custo seja ligeiramente maior. Além disso, a proximidade geográfica pode garantir menor latência e acesso mais rápido aos dados dos sensores.

### Links
- [Vídeo Comparativo no YouTube](https://www.youtube.com/watch?v=dg5bIIl_sUI) *(não listado)*

### Gráficos e Imagens
*Inclua gráficos de comparação de custos gerados a partir da calculadora.*

---

## Conclusão
- **Entrega 1**: Modelos de Machine Learning implementados com análises robustas.
- **Entrega 2**: Comparação de custos com justificativas técnicas para a escolha da melhor região.
- **Próximos Passos**: Continuação do desenvolvimento com foco em explorar ainda mais soluções na nuvem.

---

*Observação: Este repositório segue as diretrizes da FIAP e não será atualizado após o prazo de entrega.*
