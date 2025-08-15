
> [!NOTE] Conteúdo
> - Requisitos funcionais
> - Requisitos não funcionais
> - Regras de negócio
> - Histórias de usuário ou casos de uso
> - Perfis de usuários

## **Requisitos Funcionais**

_(O que o sistema deve permitir ao usuário)_

### **1. Cadastro e organização de acervo**

- RF01 – Cadastrar itens (livros, revistas, DVDs, jogos, etc.) com informações como título, autor, editora, ano, ISBN, categoria e estado de conservação.
- RF02 – Buscar e preencher automaticamente os dados pelo ISBN usando APIs externas (Google Books, Open Library).
- RF03 – Editar e excluir registros do acervo.
- RF04 – Incluir capa/foto do item.
- RF05 – Classificar itens por categorias, etiquetas ou palavras-chave.
### **2. Gerenciamento de empréstimos**

- RF06 – Registrar empréstimo de item para um usuário.
- RF07 – Registrar devolução do item.
- RF08 – Controlar datas de retirada e devolução.
- RF09 – Emitir alertas de atraso.
- RF10 – Permitir reserva antecipada de itens.
### **3. Cadastro e controle de usuários/leitores**

- RF11 – Cadastrar usuários com dados básicos (nome, contato, documento).
- RF12 – Consultar histórico de empréstimos por usuário.
- RF13 – Bloquear temporariamente usuários com atrasos prolongados.
### **4. Relatórios e estatísticas**

- RF14 – Gerar lista de itens mais emprestados em determinado período.
- RF15 – Listar itens em atraso.
- RF16 – Gerar estatísticas de movimentação do acervo (novos cadastros, empréstimos, devoluções).
- RF17 – Exportar dados em formatos CSV ou XLSX.
### **5. Administração e configuração**

- RF18 – Criar e gerenciar usuários do sistema (bibliotecário, voluntário, administrador).
- RF19 – Personalizar logotipo e cores da interface.
- RF20 – Configurar parâmetros de empréstimo (prazo, limite de itens por pessoa).

---

## **Requisitos Não Funcionais**

_(Como o sistema deve funcionar)_

### **1. Usabilidade**

- RNF01 – Interface simples e intuitiva, adequada para usuários com pouca experiência em tecnologia.
- RNF02 – Design responsivo para uso em celular, tablet ou computador.
- RNF03 – Suporte a múltiplos idiomas (inicialmente português, com possibilidade de tradução).

### **2. Desempenho**

- RNF04 – Cadastro de item ou empréstimo deve levar no máximo 3 segundos para ser processado.
- RNF05 – Consultas no acervo devem retornar resultados em até 2 segundos.

### **3. Segurança**

- RNF06 – Autenticação por login e senha, com criptografia segura (bcrypt ou similar).
- RNF07 – Controle de acesso por perfil (ex.: voluntário não pode excluir itens).
- RNF08 – Proteção contra injeção de código e ataques comuns (SQL Injection, XSS, CSRF).
### **4. Infraestrutura**

- RNF09 – Disponível para instalação local ou em nuvem.
- RNF10 – Compatível com Docker para instalação rápida.
- RNF11 – Banco de dados PostgreSQL ou SQLite (para uso offline).

### **5. Manutenção e comunidade**

- RNF12 – Código aberto disponível no GitHub/GitLab, com documentação para desenvolvedores e usuários.
- RNF13 – Scripts automáticos para instalação e atualização.
- RNF14 – Registro de bugs e sugestões via sistema de issues.