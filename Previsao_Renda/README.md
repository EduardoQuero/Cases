# Projeto de Concessão de Cartões de Crédito 🌐💳

## Introdução

Olá, pessoal! Bem-vindos ao meu projeto de concessão de cartões de crédito. Aqui, desenvolvemos um modelo preditivo para identificar o risco de inadimplência, tornando as decisões financeiras mais seguras e informadas.

## Etapas do Projeto

### 1. Entendimento do Negócio (CRISP-DM)

Meu objetivo é criar um modelo preditivo que avalie o risco de inadimplência de clientes que solicitam cartões de crédito. Vamos juntos fornecer uma ferramenta valiosa para auxiliar os mutuários em suas decisões financeiras.

### 2. Entendimento e Preparação dos Dados (CRISP-DM)

#### Dicionário de Dados

- **sexo**: Gênero do cliente (M/F).
- **posse_de_veiculo**: Possui veículo (Y/N).
- **posse_de_imovel**: Possui imóvel (Y/N).
- **qtd_filhos**: Quantidade de filhos.
- **tipo_renda**: Tipo de renda.
- **educacao**: Nível de educação.
- **estado_civil**: Estado civil.
- **tipo_residencia**: Tipo de residência.
- **idade**: Idade em anos.
- **tempo_emprego**: Tempo de emprego em anos.
- **possui_celular**: Possui celular (1 = sim, 0 = não).
- **possui_fone_comercial**: Possui telefone comercial (1 = sim, 0 = não).
- **possui_fone**: Possui telefone (1 = sim, 0 = não).
- **possui_email**: Possui e-mail (1 = sim, 0 = não).
- **qt_pessoas_residencia**: Quantidade de pessoas na residência.
- **mau**: Indicador de mau pagador (True = mau, False = bom).

### 3. Análise Exploratória de Dados

Vamos explorar juntos! Distribuição da variável resposta (mau), gráficos de barras para variáveis categóricas e histogramas para variáveis numéricas estão no cardápio.

### 4. Pré-processamento dos Dados

Tratamento de dados faltantes, remoção de duplicatas e conversão de variáveis categóricas em dummy variables para deixar tudo tinindo!

### 5. Modelagem Preditiva 🚀

Vamos ao ponto forte! Criei e treinei um modelo Random Forest Classifier. A acurácia está na casa dos 70%, o que é promissor. Matriz de confusão, estamos de olho em você!

### 6. Conclusão

Concluímos que nosso modelo tem uma capacidade moderada de prever o risco de inadimplência. Para a próxima rodada, sugiro otimizar o modelo, explorar outras técnicas e considerar mais dados para fazer bonito!

## Instruções de Uso 🛠️

1. **Requisitos:**
   - Python 3.x
   - Bibliotecas: numpy, pandas, matplotlib, seaborn, scikit-learn

2. **Configuração do Ambiente:**
   - Instale as bibliotecas necessárias: `pip install numpy pandas matplotlib seaborn scikit-learn`

3. **Execução do Código:**
   - Execute o script Python `projeto_cartao_credito.py` para reproduzir a análise e treinar o modelo.

4. **Resultados:**
   - Os resultados do modelo, incluindo métricas de desempenho, serão exibidos no console.

## Contribuições 🤝

Contribuições são super bem-vindas! Se encontrar problemas ou tiver sugestões de melhorias, por favor, abra uma issue neste repositório.

## Licença 📜

Este projeto é distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais detalhes.

---
