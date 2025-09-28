## Sumário
1. Problema abordado e justificativa
2. Objetivos do sistema
3. Escopo do projeto
4. Visão geral da arquitetura
5. Tecnologias propostas
6. Integrantes da equipe e seus papéis

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