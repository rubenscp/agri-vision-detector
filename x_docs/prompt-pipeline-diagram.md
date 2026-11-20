Prompt para geração do Diagrama do Pipeline:

Considere um projeto Python com as seguintes principais atividades:

1) pre-processamento de imagens de um dataset específico de doença de plantas a fim de criar as anotações no formato YOLO e Pascal VOC, bem como tentar balancear os conjuntos de treinamento, validação e teste.

2) treinamento e ajuste fino de diversos modelos de detecção de objetos como os vários modelos da família YOLO, DETR e SSD

3) seleção de um ou mais detectores de objetos conforme critérios a serem definidos como os de melhor performance ou basedo em critérios de divrsidade entre detectores. Essa etapa utilizará somente o conjunto de validação do dataset de imagens.

4) Fusão das predições dos detectores selecionados utilizando o conjunto de teste do dataset incluindo as métricas de desempenho do resultado final da fusão tardia.

5) Inferencia dos detectores seleconados e fusão tardia para um conjunto de imagens completamente desconhecido a fim de ser utilizado em processos de suporte à decisão no melhoramento de cultivares como arroz, feijão, soja, dentre outras.

A partir desse contexto e do pipeline descrito acima, proponha uma estrutura de projeto Python que considere todas as atividades acima organizando em pastas e módulos python de gestão do pipeline. Gere uma imagem do pipeline e uma descrição textual dessa estrutura de pastas.