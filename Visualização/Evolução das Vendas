import matplotlib.pyplot as plt

vendas_diarias = df.groupby('Data Venda')['Valor'].sum().reset_index()

plt.figure(figsize=(14, 5))
sns.lineplot(data=vendas_diarias, x='Data Venda', y='Valor')
plt.title('Evolução das Vendas de Títulos ao Longo do Tempo')
plt.xlabel('Data')
plt.ylabel('Valor Vendido (R$)')
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()
