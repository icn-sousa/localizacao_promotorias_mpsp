## Extração de dados das Promotorias Cíveis do MPSP

Este projeto possibilita a extração de informações das 340 Promotorias Cíveis do Ministério Público do Estado de São Paulo (MPSP) a partir do site [Encontre uma Promotoria](https://www.mpsp.mp.br/promotorias).

### **Descrição**

O [programa](https://github.com/icn-sousa/localizacao_promotorias_mpsp/blob/d4dda8a481065bc5a7b345b9db3c5c5fcfefc40f/promotorias_mpsp.ipynb) realiza a coleta dos seguintes dados:

- **Nomes das Promotorias**: Captura os nomes oficiais de cada uma das Promotorias.
- **Coordenadas Geográficas**: Obtém a latitude e a longitude correspondentes a cada Promotoria.

### **Objetivo**

A extração desses dados visa facilitar o acesso à informação e viabilizar análises sobre a distribuição das Promotorias Cíveis no Estado de São Paulo.

Os [dados extraídos](https://github.com/icn-sousa/localizacao_promotorias_mpsp/blob/d4dda8a481065bc5a7b345b9db3c5c5fcfefc40f/coordenadas_promotorias_mpsp.csv), salvos em um arquivo no formato CSV, podem ser utilizados no *software* [QGIS](https://www.qgis.org/) (Adicionar Camada de Texto Delimitado).

### **Licença**

Este projeto está licenciado sob a licença MIT.
