# Dashboard de Gestão de Vendas
## Análise estratégica de países, produtos e segmentos para suporte à tomada de decisão

### Situação

A empresa possui dados de vendas distribuídos entre países, produtos e segmentos, mas sem indicadores claros sobre rentabilidade, desempenho por categoria e risco operacional. Isso dificultava decisões estratégicas e entendimento de onde estavam as melhores oportunidades.

<div align="Center">
<img src="https://github.com/user-attachments/assets/9d0ab335-6a61-45f7-8e0e-e7508c4e5e9b" width="350px" />
</div> 

---

### 📌 Objetivo

-	Identificar quais regiões, produtos e segmentos são mais lucrativos.
-	Encontrar pontos de prejuízo ou produtividade baixa.
-	Construir um pipeline de dados limpo e replicável.
-	Gerar visualizações claras para leitores não técnicos, sem perder rigor técnico.


---

### 🛠 Ferramentas Utilizadas
- **Python**
  - Pandas: Analise de dados
  - MatPlotLib: Geração de gráficos    

---

### 🔄 Pipeline de Dados
1. **Extração:** Excel (Fonte: [Daxus](https://www.daxus.com.br/treinamentos) ).
2. **Transformação:** ajuste dos dados no Python. 
3. **Modelagem:** criação de modelo relacional no Python.  
4. **Visualização:** Geração de Gráficos com MatPLotLib no Python.

<div align="Center">
<img src="https://github.com/user-attachments/assets/5392001b-58a6-43a3-a73a-57907c702e04" width="350px" />
</div> 

---

### 💡 Resultados e Impacto
- Margem de Lucro por País:
  -	A variação de margem entre países foi de apenas 3,18%.
  -	Interpretação: nenhum país é deficitário, mas a empresa não tem um mercado líder destacado.
  -	Oportunidade: expandir esforços onde custos são menores ou volume é maior.

<div align="Center">
<img src="https://github.com/user-attachments/assets/30d2e6e1-443a-45d8-ae73-43985932bf88" width="350px" />
</div> 

- Margem de Lucro por Produto:
  -	O “Produto 1” apresenta faturamento significativamente menor comparado aos demais.
  -	Possíveis causas: baixa demanda, preço não competitivo ou posicionamento inadequado.
  -	Recomendação: revisar estratégia comercial desse produto.

  
<div align="Center">
<img src="https://github.com/user-attachments/assets/f92568ae-c4c8-4c24-b8cf-24707cdd5db6" width="350px" />
</div> 

- Margem de Lucro por segmento:
  -	O segmento “Grandes Empresas” apresenta margem negativa de -4,88%, representando prejuízo.
  -	Implicação: custos operacionais altos ou precificação inadequada.
  -	Ação sugerida: revisão de contratos ou renegociação.

  
<div align="Center">
<img src="https://github.com/user-attachments/assets/baac2521-3a1a-4ce3-91a5-adf07dcb0e2c" width="350px" />
</div> 

<!--
Margem de Lucro por pais:
<img width="615" height="413" alt="Image" src="https://github.com/user-attachments/assets/30d2e6e1-443a-45d8-ae73-43985932bf88" />
Margem de Lucro por produto:
<img width="592" height="453" alt="Image" src="https://github.com/user-attachments/assets/f92568ae-c4c8-4c24-b8cf-24707cdd5db6" />
Margem de Lucro por segmento:
<img width="664" height="453" alt="Image" src="https://github.com/user-attachments/assets/baac2521-3a1a-4ce3-91a5-adf07dcb0e2c" />
Pipelina de Dados:
<img width="1536" height="1024" alt="Image" src="https://github.com/user-attachments/assets/5392001b-58a6-43a3-a73a-57907c702e04" />
Vendas:
<img width="1536" height="1024" alt="Image" src="https://github.com/user-attachments/assets/9d0ab335-6a61-45f7-8e0e-e7508c4e5e9b" />
-->
