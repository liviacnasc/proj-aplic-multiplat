## Sumário
1. Problema abordado e justificativa
2. Objetivos do sistema
3. Escopo do projeto
4. Visão geral da arquitetura
5. Tecnologias propostas
6. Integrantes da equipe e seus papéis
7. Cronograma para a próxima etapa

## Problema abordado e Justificativa

Muitas pessoas que desejam mudar de bairro em Fortaleza não têm informações centralizadas sobre qualidade de vida, infraestrutura, custo de moradia e sustentabilidade, pois esses dados estão espalhados (portais da prefeitura, IBGE, SSP-CE etc.) ou são de difícil interpretação. Com base nisso, decidimos criar um sistema que ajudaria a consolidar e comparar bairros da cidade, tornando a escolha mais consciente e sustentável, proporcionando uma melhor experiência aos moradores.
## Objetivos do sistema

Ajudar usuários na escolha de um bairro para morar, levando em consideração a infraestrutura, mobilidade, custo de vida e indicadores ambientais.
## Escopo do projeto
### Descrição

O projeto reúne dados públicos e fornece uma representação visual com tabelas e gráficos, a fim de facilitar a interpretação, comparando dois bairros da cidade de Fortaleza de escolha do usuário.

#### Categorias e Indicadores

Território

- Área
- Cobertura vegetal Urbana
- Regional

Socioeconômico

- IDH
- IDH Renda
- IDH Educação

População

Habitação

- Domicílios
- Condomínios

Mobilidade (implementação futura)

- Ciclovias
- Estações Bicicletar
- Pontos de ônibus Equipamentos de saúde


### Entregas e resultados

- Site responsivo (mobile e web):
    - Tela com um mapa, para que usuário possa selecionar dois bairros.
    - Exibição de dados em tabelas e gráficos.
- API Rest
### Fora do Escopo

- Machine learning para sugerir bairro ideal.
- Ranking completo de todos os bairros.
### Restrições do projeto

Projeto será exclusivo para a cidade de Fortaleza.
### Visão geral da arquitetura

A arquitetura em camadas será aplicada no projeto, de forma que seja um desenvolvimento rápido, mas que mantenha as responsabilidades dos componentes devidamente separadas.
### Tecnologias propostas

- FrontEnd: Vite e React
- Gráficos: Rechart.js
- Mapas: Leaflet e Open Street Map
- Runtime: Node.js
- Framework: Express
- Cliente http: Axios
- Testes: Jest
- Documentação: Swagger autogen & swagger-ui-express
- Banco de dados: PostgreSQL

### Integrante da equipe e seus papéis

Nome                    | Função     |
------------------------|--------------|
Ana Lívia  | Desenvolvedora    |
Fernando Henrique | Documentação |
Jesus Nathan | Documentação |
Rebeca Samia | Design Web e Mobile |

### Cronograma

#### Etapa 1
**Agosto/2025**

- Definição do escopo do projeto
- Requisitos funcionais e não funcionais
- Desenvolvimento inicial da API (rotas principais criadas)
- Design da interface

**Setembro/2025**

- Criação de controllers e serviços da API
- Estrutura de migrations e seeds do banco (com Node + PostgreSQL)
- Tratamento de erros
- Principais testes de integração e unitários com Jest
- Documentação de instalação local e setup de ambiente

#### Etapa 2

**Outubro/2025**
- Finalizar testes de integração e unitários
- Refinar o design da interface (wireframes finais ou protótipo navegável)
- Desenvolvimento do frontend
- Integração frontend e backend (primeiras telas consumindo a API)
- Atualizar documentação da API (Swagger/OpenAPI)

**Novembro/2025**

- Implementar painel de visualização de dados (gráficos, mapas, indicadores)
- Testes de usabilidade com usuários
- Revisão e ajustes finais na API e no frontend
- Documentação final consolidada
- Versão estável da aplicação pronta para entrega/apresentação