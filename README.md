# Projeto de Análise e Automação para Benefícios Fiscais de Ativos Imobilizados

## Descrição

Este projeto visa automatizar a análise de benefícios fiscais para ativos imobilizados no Estado do Pará. Utiliza um banco de dados para gerenciar informações sobre equipamentos e documentos comprobatórios, oferecendo uma análise mais ágil e precisa.

## Estrutura do Projeto

- `src/`: Contém os scripts principais do projeto.
  - `db_setup.py`: Configuração do banco de dados.
  - `data_analysis.py`: Análise de dados.
  - `report_generation.py`: Geração de relatórios.
- `data/`: Dados de exemplo.
- `reports/`: Relatórios gerados.

## Tecnologias Utilizadas

- **Banco de Dados**: SQLite
- **Linguagens de Programação**: Python
- **Bibliotecas**: pandas, openpyxl (para manipulação de arquivos Excel)
- **Ferramentas de Análise e Relatórios**: Excel

## Como Executar

1. **Configurar o Banco de Dados**:
   ```bash
   python src/db_setup.py
