# Análise estatística de base de dados de diabetes

O diabetes é uma doença crônica grave na qual os indivíduos perdem a capacidade de regular efetivamente os níveis de glicose no sangue e pode levar a uma redução na qualidade de vida e na expectativa de vida. Os individuos perdem a capacidade de metababolizar o açúcar  no organismo.

![imagem](imagens/diabetes.jpg)


## Organização do projeto

```
├── .gitignore         <- Arquivos e diretórios a serem ignorados pelo Git
├── ambiente.yml       <- O arquivo de requisitos para reproduzir o ambiente de análise
├── LICENSE            <- Licença de código aberto (MIT)
├── README.md          <- README principal para desenvolvedores que usam este projeto.
|
├── dados              <- Arquivos de dados para o projeto.
|
|
├── notebooks          <- Jupyter Notebooks.

|   └──src             <- Código-fonte para uso neste projeto.
|      │
|      ├── __init__.py  <- Torna um módulo Python
|      ├── config.py    <- Configurações básicas do projeto
|      └── estatistica.py  <- Funções criadas para especificamente para este projeto
|
├── referencias        <- Dicionários de dados.
|
├── Imagens         <- Imagem utilizada no projeto.

```

## Configuração do ambiente

1. Faça o clone do repositório.

    ```bash
    git clone git@github.com:FelipeLeal14/Modelo-Projeto-Teste.git
    ```

2. Crie um ambiente virtual para o seu projeto utilizando o conda.


      ```bash
      conda env create -f ambiente.yml --name <nome>
      ```
## Um pouco mais sobre a base

[Clique aqui](referencias/01_dicionario_de_dados.md) para saber mais sobre o dicionários de dados

## Resumo dos principais Resultados

O desenvolvimento da doença em sua maioria esta atrelado ao estilo de vida, alimentação, sedentarismo, tabagismo, e outras características. Entende-se também que a outras doenças como pressão pode ser precursora para o surgimento de diabetes.
