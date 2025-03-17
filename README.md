# EDA - Análise Exploratória de Dados

Este repositório é uma coleção de projetos de Análise Exploratória de Dados (EDA) em Python, servindo como referência para estudantes, profissionais e entusiastas de ciência de dados.

## 📊 Projetos Disponíveis

- [Adult-income](./Adult-income): Análise de dados de renda de adultos
- [Amazon](./Amazon): Análise de dados da Amazon
- [Cirrhosis](./Cirrhosis): Análise de dados de cirrose
- [GlobalTemperatures](./GlobalTemperatures): Análise de temperaturas globais
- [Netflix](./Netflix): Análise de dados da Netflix
- [Student-perfomace](./Student-perfomace): Análise de desempenho de estudantes
- [Transfusion](./Transfusion): Análise de dados de transfusão de sangue

## 🧰 Estrutura Padrão dos Projetos

Cada projeto segue uma estrutura padrão:

```
projeto-nome/
├── data/                    # Dados brutos e processados
├── img/                     # Imagens e visualizações geradas
├── EDA-nome-projeto.ipynb   # Notebook Jupyter principal da análise
├── dict_data.ipynb          # Dicionário explicativo dos dados
├── requirements.txt         # Dependências necessárias
└── README.md                # Documentação específica do projeto
```

## 🚀 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/caiquemiranda/EDA-Exploratory-Data-Analysis-python.git
```

2. Navegue até o projeto de interesse e instale as dependências:
```bash
cd [nome-do-projeto]
pip install -r requirements.txt
```

3. Abra o notebook Jupyter para visualizar a análise:
```bash
jupyter notebook EDA-nome-projeto.ipynb
```

## 📚 Metodologia

Os projetos seguem uma metodologia comum de análise exploratória:

1. **Importação e Limpeza de Dados**: Carregamento dos dados, tratamento de valores ausentes e outliers
2. **Análise Descritiva**: Estatísticas resumidas e distribuições de variáveis
3. **Visualização de Dados**: Gráficos e visualizações para identificar padrões
4. **Correlações e Relacionamentos**: Análise de relações entre variáveis
5. **Insights e Conclusões**: Principais descobertas e possíveis próximos passos

## 🛠️ Tecnologias Utilizadas

Todos os projetos utilizam um conjunto comum de bibliotecas Python para análise de dados:

- **pandas**: Manipulação e análise de dados
- **numpy**: Computação numérica
- **matplotlib** e **seaborn**: Visualização de dados
- **scikit-learn**: Algoritmos de machine learning
- **scipy**: Funções científicas e estatísticas
- **plotly**: Visualizações interativas
- **statsmodels**: Modelos estatísticos

Cada projeto pode incluir bibliotecas adicionais específicas para seu domínio.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

- Adicionar novos projetos de EDA
- Melhorar análises existentes
- Corrigir erros ou problemas
- Sugerir novas técnicas ou abordagens

Para contribuir:
1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/nova-analise`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova análise'`)
4. Push para a branch (`git push origin feature/nova-analise`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob licença [MIT](LICENSE).
