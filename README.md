# 📊 Sistema de Inteligência de Vendas e Performance de Dados

Este projeto simula um cenário real de análise de dados em uma livraria. O objetivo foi transformar dados brutos com inconsistências em um relatório estratégico de faturamento e impostos, automatizando processos que antes seriam manuais.

## 🚀 Funcionalidades do Projeto

O script realiza o ciclo completo de um profissional de dados (ETL):
1.  **Tratamento de Dados (Data Cleaning):** Correção de inconsistências em strings (remoção de espaços extras e padronização de maiúsculas/minúsculas) e tratamento de valores nulos (*NaN*).
2.  **Integração de Bases (Data Merge):** Cruzamento de dados de vendas com informações de fornecedores usando chaves relacionais.
3.  **Lógica de Negócio Automática:**
    * Cálculo de faturamento por item.
    * Classificação de performance de vendas (Categorias Diamante, Ouro e Prata).
    * Aplicação de regras tributárias diferenciadas por gênero literário.
4.  **Exportação de Resultados:** Geração automática de um dashboard em gráfico de barras e exportação da base final para **Excel**.

## 🛠️ Tecnologias Utilizadas

* **Python 3.10+**
* **Pandas:** Manipulação e tratamento de grandes volumes de dados.
* **NumPy:** Suporte matemático para operações com valores nulos.
* **Matplotlib:** Geração de visualizações gráficas.
* **Openpyxl:** Engine para exportação de arquivos `.xlsx`.

## 📈 Resultados Obtidos

O projeto permitiu identificar que a **Editora C** (Gênero Autoajuda) possui o maior volume de vendas, enquanto o gênero **Ficção** apresenta a melhor margem bruta por unidade.



## 📂 Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git](https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git)

