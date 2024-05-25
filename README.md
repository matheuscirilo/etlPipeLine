# Aplicação ETL para Web Scraping da Coleção da National Gallery of Art

## Visão Geral

Bem-vindo ao repositório da Aplicação ETL para Web Scraping da Coleção da National Gallery of Art! Este projeto foi desenvolvido para extrair, transformar e carregar (ETL) dados da página arquivada da coleção da National Gallery of Art, especificamente desta [página arquivada](https://web.archive.org/web/20121007172955/https://www.nga.gov/collection/anZ1.htm).

## Funcionalidades

- **Web Scraping**: Utiliza o BeautifulSoup4 para extrair dados da página especificada.
- **Transformação de Dados**: Processa e transforma os dados extraídos em um formato estruturado.
- **Carregamento de Dados**: Carrega os dados transformados em um banco de dados MySQL para fácil consulta e análise.
- **Mocking e Testes**: Implementa requests-mock e pytest para testar a funcionalidade da aplicação.

## Tecnologias Utilizadas

- [**BeautifulSoup4**](https://pypi.org/project/beautifulsoup4/): Uma biblioteca poderosa para extração de dados de arquivos HTML e XML.
- [**requests-mock**](https://pypi.org/project/requests-mock/): Uma biblioteca para simular o comportamento da biblioteca `requests`, permitindo testar a funcionalidade de web scraping sem acessar a URL real.
- [**pytest**](https://pypi.org/project/pytest/): Um framework que facilita a construção de casos de teste simples e escaláveis.
- **MySQL**: Utilizado como banco de dados para armazenar os dados transformados.
- [**decouple**](https://pypi.org/project/decouple/): Uma biblioteca para gerenciar configurações, permitindo separar configurações do código.

## Como Começar

### Pré-requisitos

Certifique-se de ter os seguintes itens instalados:

- Python 3.x
- Servidor MySQL

### Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seuusuario/ETLPipeLine.git
   cd ETLPipeLine
  
2. **Instale as dependências:**:
   ```bash
   pip install -r requirements.txt
  


