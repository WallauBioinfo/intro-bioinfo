# intro-bioinfo

Sejam bem vindos a disciplina Disciplina eletiva: Introdução à Bioinformática – Análise de sequências e genomas completos.
Este repositório é destinado a disponibilização arquivos e scripts usados nas aulas.

## Cronograma

O conteúdo está organizado no cronograma abaixo.

| Dia        | Turno | Aula                                                                                                                                                                                                        | Professor                      | Conteúdo                                                                          |
|------------|-------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------|-----------------------------------------------------------------------------------|
| 08/04/2024 | Manhã | Abertura do curso com apresentações sobre a dinâmica das aulas e introduções individuais dos participantes. Introdução a computação, conceitos de sistemas operacionais e linguagem de programação – colab. | Tulio Campos - Gabriel Wallau  | [Dia 1](https://github.com/WallauBioinfo/intro-bioinfo/tree/main/classes/dia_1)   |
| 08/04/2024 | Tarde | O poder da linha de comando: como navegar no ambiente e automatizar/gerenciar tarefas: instalando pacotes, monitorando jobs, paralelização, navegando na estrutura de diretórios, pipelining, bash script.  | Tulio Campos - Gabriel Wallau  |                                                                                   |
| 09/04/2024 | Tarde | Gerenciado de pacotes e pipelines com conda, containers (Docker e Singularity) e orquestradores de pipelines (NextFlow).                                                                                    | Gabriel Wallau – Wilson Junior | [Dia 2](https://github.com/WallauBioinfo/intro-bioinfo/tree/main/classes/dia_2)   |
| 10/04/2024 | Manhã | Gerenciado de pacotes e pipelines com conda, containers (Docker e Singularity) e orquestradores de pipelines (NextFlow) - Prática.                                                                          | Gabriel Wallau – Wilson Junior | [Dia 3](https://github.com/WallauBioinfo/intro-bioinfo/tree/main/classes/dia_3)   |
| 10/04/2024 | Tarde | Softwares básicos e bancos de dados de sequência para recuperar/submeter e manipular sequências.                                                                                                            | Gabriel Wallau                 |                                                                                   |
| 11/04/2024 | Tarde | Bash oneliner; EMBOSS; pipelines básicos no bash, NCBI, EMBL-EBI, UNIPROT, SWISSPROT, ENTREZ.                                                                                                               | Gabriel Wallau                 | [Dia 4](https://github.com/WallauBioinfo/intro-bioinfo/tree/main/classes/dia_4)   |
| 12/04/2024 | Manhã | Métodos de alinhamento de sequências.                                                                                                                                                                       | Gabriel Wallau                 | [Dia 5](https://github.com/WallauBioinfo/intro-bioinfo/tree/main/classes/dia_5)   |
| 12/04/2024 | Tarde | Alinhamento par a par e múltiplo.                                                                                                                                                                           | Gabriel Wallau                 |                                                                                   |
| 15/04/2024 | Manhã | Introdução aos métodos filogenéticos.                                                                                                                                                                       | Gabriel Wallau                 | [Dia 6](https://github.com/WallauBioinfo/intro-bioinfo/tree/main/classes/dia_6)   |
| 15/04/2024 | Tarde | Reconstrução de filogenias.                                                                                                                                                                                 | Gabriel Wallau                 |                                                                                   |
| 16/04/2024 | Tarde | Sequenciamento de alto desempenho: fatos e desafios.                                                                                                                                                        | Tulio Campos                   | [Dia 7](https://github.com/WallauBioinfo/intro-bioinfo/tree/main/classes/dia_7)   |
| 17/04/2024 | Manhã | Analisando dados de sequenciamento de alto desempenho.                                                                                                                                                      | Tulio Campos                   | [Dia 8](https://github.com/WallauBioinfo/intro-bioinfo/tree/main/classes/dia_8)   |
| 17/04/2024 | Tarde | Montagem de genomas: de novo vs por referência.                                                                                                                                                             | João Pitta                     |                                                                                   |
| 18/04/2024 | Tarde | Montagem de genomas virais e bacterianos                                                                                                                                                                    | João Pitta                     | [Dia 9](https://github.com/WallauBioinfo/intro-bioinfo/tree/main/classes/dia_9)   |
| 19/04/2024 | Manhã | Predição gênica e anotação funcional                                                                                                                                                                        | Beatriz Toscano                | [Dia 10](https://github.com/WallauBioinfo/intro-bioinfo/tree/main/classes/dia_10) |
| 22/04/2024 | Manhã | Alinhamento concatenados e múltiplos marcadores - Filogenômica.                                                                                                                                             | Wilson Junior                  | [Dia 11](https://github.com/WallauBioinfo/intro-bioinfo/tree/main/classes/dia_11) |
| 22/04/2024 | Tarde | Concatenação (Concatenator) e alinhamento múltiplo, métodos de reconstrução filogenética rápida.                                                                                                            | Wilson Junior                  |                                                                                   |
| 23/04/2024 | Tarde | Apresentações de artigos e discussão                                                                                                                                                                        |                                |                                                                                   |
| 24/04/2024 | Manhã | Apresentações de artigos e discussão                                                                                                                                                                        |                                |                                                                                   |

## Bibliografia

## Básica

1. Jin Xiong. Essential Bioinformatics. Cambridge University Press, The Edinburg Building, Cambridge CB2 2RU, UK. 2006.
2. Leandro Marcio Moreira. Ciências genômicas: fundamentos e aplicações. Sociedade Brasileira de Genética. Ribeirão Preto - São Paulo. 2015. 403 p.
3. Hugo Verli. Bioinformática da Biologia à Flexibilidade Molecular. Sociedade Brasileira de Bioquímica e Biologia Molecular. 1. ed, São Paulo, 2014.

## Artigos para discussão

[1](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3861042/) – El-Metwally et al 2013. Next-Generation Sequence Assembly: Four Stages of Data Processing and Computational Challenges. PLoS Computational Biology

[2](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0017915) – Zhang et al. 2011. A practical Comparison of De Novo Genome Assembly Software Tools for Next-Generation Sequencing Technologies. PLoS One

[3](https://pubmed.ncbi.nlm.nih.gov/32962098/) – Ejgu et al. 2020. Review on the Computational Genome Annotation of Sequences Obtained by Next-Generation Sequencing. Biology (MDPI)

[4](https://academic.oup.com/sysbio/article/66/2/218/2670096) – Bogusz and Whelan 2017. Phylogenetic tree estimation with and without alignment: new distance methods and benchmarking. Systematic Biology

[5](https://pubmed.ncbi.nlm.nih.gov/35454135/) – Chao et al 2022. Developments in Algorithms for Sequence Alignment: A Review. Biomolecules (MDPI).ls

## Coordenação da disciplina

Dr. Gabriel da Luz Wallau

Dr. Tulio de Lima Campos

