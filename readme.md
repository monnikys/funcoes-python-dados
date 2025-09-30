# Funções Python para Análise de Dados

Este repositório contém uma coleção de funções Python desenvolvidas para resolver problemas comuns em análise de dados, como cálculo de potências, manipulação de listas, processamento de texto, análise de desempenho e tratamento de exceções.

## 📚 Conteúdo

### Análise de Estudantes
- Cálculo da média, maior e menor nota, e situação do aluno.
- Avaliação de testes objetivos comparando respostas com gabarito.
- Agrupamento de notas e pontuações com tratamento de erros em respostas inválidas.

### Desempenho de Futebol
- Cálculo de pontos e aproveitamento do time no campeonato considerando vitórias, empates e derrotas.
- Análise de gols marcados e sofridos.

### Processamento de Texto
- Filtragem de palavras com 5 ou mais caracteres em uma frase.
- Verificação de pontuações e tratamento de erros em listas de palavras.
- Normalização e concatenação de nomes.

### Manipulação de Listas e Tuplas
- Geração de quadrados dos números de uma lista usando `map()` e `lambda`.
- Identificação de múltiplos de 3 usando funções e list comprehension.
- Extração de elementos específicos de tuplas e criação de novas listas.
- Agrupamento de elementos de listas em tuplas e cálculo de somas.

### Dicionários e Agrupamentos
- Criação de dicionários a partir de listas usando dict comprehension.
- Contagem de ocorrências de elementos (como estados) e soma de valores (como número de funcionários) por chave.
- Filtragem de dados com condições específicas.

### Funções Matemáticas
- Cálculo de potência com `pow()` e raiz quadrada com `math.sqrt()`.
- Geração de números aleatórios usando `random`.

### Tratamento de Exceções
- Tratamento de erros como `ZeroDivisionError`, `ValueError`, `KeyError` e listas de tamanhos diferentes.
- Mensagens de erro personalizadas para indicar o problema encontrado.
- Uso de `try-except-finally` para validação de dados antes de cálculos.

### Utilitários Diversos
- Cálculo de tabuada de um número inteiro.
- Geração de tokens aleatórios com validação.
- Cálculo de gastos de viagem, incluindo hotel, gasolina e passeios.
- Cálculo de área de jardins circulares e valor total do gramado.

## 🔧 Tecnologias Utilizadas

- Python 3.x
- Bibliotecas padrão do Python (`math`, `random`)

## 🚀 Como Usar

1. Clone o repositório:

```bash
git clone https://github.com/monnikys/funcoes-python-dados.git
cd funcoes-python-dados
```

2. Execute os notebooks Jupyter para explorar as funções:

```bash
jupyter notebook
```

Ou execute os scripts Python diretamente:

```bash
python nome_do_script.py
```

## 📜 Exemplos de Uso

### Análise de Estudantes

```python
notas = [8, 7, 9, 6]
media, maior, menor, situacao = analise_estudantes(notas)
print(f"Média: {media}, Maior nota: {maior}, Menor nota: {menor}, Situação: {situacao}")
```

### Desempenho de Futebol

```python
gols_marcados = [2, 1, 3, 1, 0]
gols_sofridos = [1, 2, 2, 1, 3]
pontos, aproveitamento = desempenho_futebol(gols_marcados, gols_sofridos)
print(f"Pontos: {pontos}, Aproveitamento: {aproveitamento}%")
```

### Processamento de Texto

```python
frase = "Aprender Python aqui na Alura é muito bom"
palavras = processar_texto(frase)
print(palavras)
```

### Divisão de Colunas (Tratamento de Erros)

```python
pressoes = [100, 120, 140, 160, 180]
temperaturas = [20, 25, 30, 35, 40]
resultados = divide_colunas(pressoes, temperaturas)
print(resultados)
```

## 🢮 Testes

Os testes podem ser realizados executando os notebooks Jupyter ou os scripts Python diretamente. Certifique-se de ter o Jupyter instalado:

```bash
pip install notebook
```

E então, execute:

```bash
jupyter notebook
```

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Faça commit das suas alterações (`git commit -am 'Adiciona nova feature'`).
4. Envie para o repositório remoto (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## 📜 Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

