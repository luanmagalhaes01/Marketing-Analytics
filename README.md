# Análise de Clientes para E-commerce

Este projeto utiliza dados de transações de um e-commerce (disponíveis no [Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)) para explorar o comportamento dos clientes e identificar padrões de compra, permitindo uma visão mais completa para estratégias de retenção e segmentação.

### Metodologias aplicadas:

1. **Análise de Cohort**:
   - Comparamos grupos de clientes com base na data da primeira compra, monitorando taxas de retenção e engajamento ao longo do tempo. Isso possibilita identificar momentos críticos em que há tendência de perda de clientes e permite intervenções estratégicas.

2. **Segmentação de Clientes (RFM e KMeans)**:
   - Usamos a análise RFM (Recência, Frequência, Monetário) para agrupar clientes de acordo com a data da última compra, a frequência de compras e o valor gasto. Em seguida, aplicamos a clusterização com KMeans sobre esses dados RFM para criar segmentos que representam perfis de comportamento, como clientes VIP, leais, ocasionais e inativos. Essa segmentação detalhada facilita campanhas de marketing direcionadas e personalizadas para cada perfil de cliente.

3. **Análise de Pareto**:
   - Aplicando o princípio 80/20, identificamos o grupo de clientes que gera a maior parte da receita. Estes clientes de alto valor são essenciais para o sucesso do negócio e podem ser alvo de programas exclusivos de engajamento e retenção.

🚀 Você pode conferir a apresentação detalhada no [Jupyter Notebook aqui](https://github.com/luanmagalhaes01/Marketing-Analytics/blob/main/Marketing%20Analytics.ipynb).
