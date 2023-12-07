# TCC-3W: Repositório do Trabalho de Conclusão de Curso em Engenharia Eletrônica

Bem-vindo ao repositório do meu Trabalho de Conclusão de Curso (TCC) em Engenharia Eletrônica. Aqui, você encontrará os códigos desenvolvidos durante a pesquisa.

## Ferramentas Necessárias

Para executar os códigos deste projeto, serão necessárias duas ferramentas:

1. **Conda:** Um gerenciador de ambientes e pacotes em Python.
   - Instalação: [Guia de instalação do Conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)
   - Uso:
     ```bash
     conda create -n 3w python=3.8.10
     conda activate 3w
     conda install --file requirements.txt
     ```

2. **Google Colab (Drive):** Uma plataforma de notebooks interativos baseada em nuvem.
   - Uso: [Google Colab](https://colab.research.google.com/?utm_source=scs-index)

## Estrutura do Repositório

O repositório está organizado em três principais diretórios:

1. **Features:**
   - Contém um arquivo responsável por extrair as features do conjunto de dados 3W.
   - Arquivos: `all_features_data-s500-o150.pkl` e `all_features.csv`

2. **Models Training:**
   - Documenta o treinamento dos classificadores desenvolvidos durante a pesquisa.

3. **LSTM:**
   - Apresenta o treinamento de uma Rede Neural Recorrente do tipo LSTM.

## Como Contribuir

Se você deseja contribuir para este projeto, sinta-se à vontade para abrir issues, propor melhorias ou enviar pull requests. Sua colaboração é valiosa!

Agradeço por explorar este repositório e espero que seja útil para sua compreensão do meu trabalho de pesquisa em Engenharia Eletrônica.

Certamente! Aqui está uma sugestão de como você pode citar o artigo e referenciar o repositório em seu README:

## Referências

O código neste repositório utiliza o conjunto de dados 3W disponibilizado pelo autor Ricardo Emanuel Vaz Vargas. Para obter mais detalhes sobre o conjunto de dados e agradecer ao autor pela disponibilização, consulte o repositório oficial:

- **Repositório:** [3W Dataset Repository](https://github.com/ricardovvargas/3w_dataset)
- **Título:** A realistic and public dataset with rare undesirable real events in oil wells
- **Autores:** Ricardo Emanuel Vaz Vargas, Celso José Munaro, Patrick Marques Ciarelli, André Gonçalves Medeiros, Bruno Guberfain do Amaral, Daniel Centurion Barrionuevo, Jean Carlos Dias de Araújo, Jorge Lins Ribeiro, Lucas Pierezan Magalhães
- **Ano:** 2019
- **Journal:** Journal of Petroleum Science and Engineering
- **Volume:** 181
- **Páginas:** 106223
- **DOI:** [10.1016/j.petrol.2019.106223](https://doi.org/10.1016/j.petrol.2019.106223)
- **URL:** [Link para o artigo](http://www.sciencedirect.com/science/article/pii/S0920410519306357)
- **Palavras-chave:** Fault detection and diagnosis, Oil well monitoring, Abnormal event management, Multivariate time series classification
- **Resumo:** [Resumo do artigo]
