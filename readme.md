# Funções Python para Análise de Dados

Este repositório contém uma coleção de funções Python desenvolvidas para resolver problemas comuns em análise de dados, como cálculo de potências, manipulação de listas, processamento de texto e análise de desempenho.

## 📚 Conteúdo

- **Análise de Estudantes**: Cálculo da média, maior e menor nota, e situação do aluno.
- **Desempenho de Futebol**: Cálculo de pontos e aproveitamento do time no campeonato.
- **Processamento de Texto**: Filtragem de palavras com 5 ou mais caracteres em uma frase.
- **Manipulação de Listas**: Geração de quadrados dos números de uma lista, identificação de múltiplos de 3, e sorteio de frutas aleatórias.
- **Funções Matemáticas**: Cálculo de raiz quadrada e potência de números.
- **Utilitários Diversos**: Cálculo de tabuada, geração de tokens e concatenação de nomes.

## 🔧 Tecnologias Utilizadas

- Python 3.x
- Bibliotecas padrão do Python

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

## 📄 Exemplos de Uso

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

## 🧪 Testes

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

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.