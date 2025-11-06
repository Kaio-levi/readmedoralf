# Funcionalidades do projeto

* Cadastro de usuario
    telas de login e singup com jwt
    <img src="https://github.com/Kaio-levi/readmedoralf/blob/main/img/Catalogo.png">

* mostrar catalogo
    <img src="https://github.com/Kaio-levi/readmedoralf/blob/main/img/Catalogo.png">
* Suporte 24/7
    <img src="https://github.com/Kaio-levi/readmedoralf/blob/main/img/Suporte.png">
* Adicionar ao carrinho 
<img src="https://github.com/Kaio-levi/readmedoralf/blob/main/img/adicionarCarrinho.png">
* Realizar pagamento
<img src="https://github.com/Kaio-levi/readmedoralf/blob/main/img/finalizarCompra.png">
* Listagem paginada de jogos/usuários

<hr>

# Nome de cada integrante e responsabilidade

| Nome     | Função de cada integrante     |
|---------------|---------------|
| Arthur Bonna  | Ajudou no planejamento das sprints    |
| Davi Tonn   | Ficou responsaval da maior parte do front-end em angular   |
| Kaio Levi   | Planejamento das sprints e ajudou um pouco no back-end   |
| Lucas   | Ficou responsavel por maior parte do back-end   |

# Sprints 

**SPRINT 1 - SEMANA 30/09 A 06/10**

**Objetivo da Sprint:** Planejamento inicial e estruturação do projeto

**Atividades Realizadas:**
- Definição da divisão de tarefas do projeto (stack, conceitos, funcionalidades principais)
- Criação do Trello para organização das tarefas
- Planejamento do banco de dados com definição das entidades:
  - Usuario, Jogo, RequisitoSistema, Categoria, Imagem, Key, Carrinho-jogo, Carrinho, Pedido
- Início do desenvolvimento do backend em Spring Boot
- Criação das classes básicas das entidades

**Entregas:**
- Board Trello organizado
- Estrutura inicial do backend Spring Boot
- Classes das entidades criadas

---

**SPRINT 2 - SEMANA 07/10 A 13/10**

**Objetivo da Sprint:** Estruturação das camadas do backend

**Atividades Realizadas:**
- Criação das pastas service e controller
- Ajuste das relações entre entidades para modelagem correta do banco de dados
- Configuração das dependências do Spring Boot

**Entregas:**
- Camadas service e controller implementadas
- Relacionamentos entre entidades ajustados

---

**SPRINT 3 - SEMANA 14/10 A 20/10**

**Objetivo da Sprint:** Início do desenvolvimento frontend e continuidade do backend

**Atividades Realizadas:**
- **Davi:** Desenvolvimento do frontend com criação das telas:
  - Login
  - Cadastro
  - Carrinho
- **Lucas:** Continuação do desenvolvimento backend

**Entregas:**
- Telas básicas do frontend criadas
- Progresso no desenvolvimento backend

---

**SPRINT 4 - SEMANA 21/10 A 27/10**

**Objetivo da Sprint:** Implementação do sistema de autenticação

**Atividades Realizadas:**
- Implementação do sistema de login com JWT (JSON Web Token)
- Configuração da classe de segurança
- Criação da validação de token
- Criação da entidade Cargo para controle de acesso

**Entregas:**
- Sistema de autenticação JWT funcionando
- Controle de acesso implementado
- Entidade Cargo criada

---

**SPRINT 5 - SEMANA 28/10 A 03/11**

**Objetivo da Sprint:** Integração frontend-backend e início da implementação de pagamento

**Atividades Realizadas:**
- Integração completa entre back-end e front-end
- Início do desenvolvimento da tela de pagamento
- Correção de bugs na tela de produtos
- Correção do sistema de login/logoff do usuário

**Entregas:**
- Sistema integrado funcionando
- Tela de pagamento em desenvolvimento
- Bugs críticos corrigidos

---

**SPRINT 6 - SEMANA 04/11 A 10/11**

**Objetivo da Sprint:** Implementação do sistema de pagamento

**Atividades Realizadas:**
- Integração da loja com API de pagamento Trust Pay
- Testes e validação do fluxo de pagamento

**Entregas:**
- Sistema de pagamento integrado e funcionando
- Fluxo completo de compra finalizado

---

**RESUMO DAS SPRINTS:**

| Sprint | Período | Foco Principal | Entregas |
|--------|---------|----------------|----------|
| 1 | 30/09-06/10 | Planejamento e estruturação | Trello, Backend base |
| 2 | 07/10-13/10 | Camadas do backend | Services e Controllers |
| 3 | 14/10-20/10 | Frontend inicial | Telas login, cadastro, carrinho |
| 4 | 21/10-27/10 | Autenticação | JWT e segurança |
| 5 | 28/10-03/11 | Integração e pagamento | Sistema integrado, tela pagamento |
| 6 | 04/11-10/11 | Pagamento externo | API Trust Pay integrada |

# Grafico GANTT

<pre>```gantt
    title Diagrama de Gantt Detalhado - Desenvolvimento do Projeto
    dateFormat  YYYY-MM-DD
    axisFormat %d/%m
    
    section Sprint 1 (30/09-06/10)
    Definição de Stack & Conceitos :done, 2024-09-30, 2d
    Criação do Trello :done, 2024-10-01, 1d
    Planejamento do BD :done, 2024-10-02, 2d
    Backend Spring Boot Inicial :done, 2024-10-03, 3d
    
    section Sprint 2 (07/10-13/10)
    Criação Services :done, 2024-10-07, 3d
    Criação Controllers :done, 2024-10-09, 3d
    Ajuste Relações Entidades :done, 2024-10-11, 2d
    
    section Sprint 3 (14/10-20/10)
    Tela Login :done, 2024-10-14, 2d
    Tela Cadastro :done, 2024-10-15, 2d
    Tela Carrinho :done, 2024-10-17, 3d
    Desenvolvimento Backend :done, 2024-10-14, 5d
    
    section Sprint 4 (21/10-27/10)
    Implementação JWT :done, 2024-10-21, 3d
    Configuração Security :done, 2024-10-23, 2d
    Validação Token :done, 2024-10-24, 2d
    Entidade Cargo :done, 2024-10-25, 2d
    
    section Sprint 5 (28/10-03/11)
    Integração Back-Front :done, 2024-10-28, 3d
    Tela Pagamento :done, 2024-10-30, 4d
    Correção Bugs Produtos :done, 2024-10-30, 2d
    Correção Login/Logoff :done, 2024-10-31, 2d
    
    section Sprint 6 (04/11-10/11)
    Integração Trust Pay API :done, 2024-11-04, 4d
    Testes Pagamento :done, 2024-11-07, 3d``` </pre>