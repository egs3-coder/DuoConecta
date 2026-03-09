## 📌  **DuoConecta**

Sistema educacional com foco em trilhas de aprendizagem, microconteúdos e relatórios, desenvolvido com metodologia ágil e gerenciamento visual de tarefas.

## 👥 **Membros da Equipe**

| Nome | Função | Identificação |
| :--- | :--- | :--- |
| Ewerton Guilherme | Product Owner & Front End | 🔵💻 Liderança/Desenvolvimento |
| Emily Marques | Scrum Master | 🟢 Agilidade |
| Vitória Gabrielly | Scrum Master | 🟢 Agilidade |
| Thiago Cardozo | Scrum Master | 🟢 Agilidade |
| Mateus Valerino | Front End | 💻 Desenvolvimento |
| Saulo Eduardo | Front End | 💻 Desenvolvimento |
| Davi Magno | Front End | 💻 Desenvolvimento |
| Wesley Yuri | Front End | 💻 Desenvolvimento |
| Vinicius Wagner | Front End | 💻 Desenvolvimento |
| Pablo Arthur | Testador de QA | 🟠 Qualidade |


## 🎯 **Papéis e Responsabilidades**

| Área / Função | Integrantes | Responsabilidades |
|---|---|---|
| 🧭 **Product Owner & Front End** | **Ewerton Guilherme** | • Implementação das telas principais do sistema<br>• Estruturação da navegação entre páginas<br>• Aplicação de estilos visuais conforme o protótipo<br>• Garantia de funcionamento básico da interface<br>• Preparação da versão demonstrável<br>• Estruturação da apresentação final<br>• Organização do conteúdo do projeto |
| 🔄 **Scrum Masters** | **Emily Marques, Vitória Gabrielly, Thiago Cardozo** | • Organização e refinamento das telas<br>• Padronização visual (cores, tipografia, componentes)<br>• Definição da navegação entre telas<br>• Produção do protótipo navegável<br>• Apoio ao front-end com especificações visuais<br>• Estruturação da apresentação final<br>• Organização do conteúdo do projeto |
| 💻 **Front End** | **Mateus Valerino, Saulo Eduardo, Davi Magno, Wesley Yuri, Vinicius Wagner** | • Implementação das telas principais<br>• Estruturação da navegação<br>• Aplicação de estilos conforme protótipo<br>• Garantia de funcionamento básico<br>• Preparação da versão demonstrável |
| 🧪 **QA** | **Pablo Arthur** | • Criação de planos de teste<br>• Verificação de responsividade<br>• Identificação e documentação de bugs<br>• Validação do que foi planejado<br>• Testes de segurança básica |

## 📋 Quadro de Gerenciamento (Trello)

🔗 https://trello.com/b/V4VTZUBU/duoconecta

O quadro está organizado por responsáveis e áreas do projeto, contendo:

- Planejamento semanal

- Mapeamento de riscos

- Checklist de qualidade

- Protótipo funcional

- Tarefas individuais por membro

## Planejamento Semanal

| Semana | Foco | Atividades |
|---|---|---|
| 📅 **Semana 1** | **Organização e Refinamento** | • Definição inicial das telas<br>• Refinamento do escopo<br>• Padronização visual inicial |
| 🚧 **Semana 2** | **Desenvolvimento Principal** | • Implementação das telas<br>• Estruturação da navegação<br>• Aplicação de estilos<br>• Testes iniciais |
| 🎯 **Semana 3** | **Finalização e Preparação** | • Ajustes finais<br>• Correção de bugs<br>• Preparação da apresentação<br>• Versão demonstrável do sistema |

## ⚠️ Mapeamento de Riscos

| 🚨 Risco | 👤 Responsável | 🛠️ Plano de Mitigação |
|---------|----------------|------------------------|
| Atraso no desenvolvimento | ![Scrum Masters](https://img.shields.io/badge/Scrum-Masters-blue) | Acompanhamento semanal e redistribuição de tarefas |
| Problemas técnicos | ![Front End](https://img.shields.io/badge/Front--End-green) | Testes contínuos e revisão de código |
| Falta de alinhamento visual | ![Scrum Masters](https://img.shields.io/badge/Scrum-Masters-blue) | Padronização de design e revisão no Figma |
| Falta de tempo para slides | ![Product Owner](https://img.shields.io/badge/Product-Owner-orange) | Início antecipado da apresentação |
| Dificuldade na integração | ![Front End](https://img.shields.io/badge/Front--End-green) | Integrações incrementais e testes frequentes |

## ✅ Checklist de Qualidade (Definition of Done)

Para que uma entrega seja considerada pronta, ela deve atender aos seguintes critérios:

| Nº | Critério |
|---|---|
| 1 | Protótipo navegável no Figma |
| 2 | Principais telas implementadas no front-end |
| 3 | Navegação básica funcional |
| 4 | Slides completos e revisados |
| 5 | Conteúdo coerente e organizado |
| 6 | Equipe preparada para apresentar |

## 🎨 Protótipo Funcional (Figma)

🔗 [Figma]((https://www.figma.com/files/team/1570905126895089086/project/497663066/Projeto-de-equipe?fuid=1554662447686071662)
Telas essenciais

## Tecnologias Utilizadas

### Trello
Utilizado para a organização das tarefas, planejamento das etapas do projeto e acompanhamento do desenvolvimento.

### Figma
Utilizado para a criação do protótipo, definição do layout e planejamento visual da interface.

### HTML
Utilizado para estruturar o conteúdo das páginas da aplicação.

### CSS
Utilizado para estilizar a interface, definir cores, espaçamentos, fontes e layout das telas.

### JavaScript
Utilizado para adicionar interatividade, comportamentos dinâmicos e funcionalidades à aplicação.



## Fluxograma das Telas

```mermaid
flowchart TD
    A[Dashboard / Tela Inicial]
    A --> B[Perfil]
    A --> C[Favoritos]
    A --> D[Brincadeiras]
    A --> E[Relatório Professor]
    A --> F[Notificações]
    A --> G[Aulas Baixadas]
    A --> H[Configurações]
    A --> I[Continuar Assistindo]
    I --> I1[Metodologias Inclusivas]
    I --> I2[Educação Especial]
    I --> I3[Ensino Adaptado]
    I --> I4[Inclusão na Prática]
    I1 --> J[Detalhes da Trilha]
    I2 --> J
    I3 --> J
    I4 --> J
    J --> K[Assistir Aula]
    J --> L[Ver Progresso]
    J --> M[Retomar Conteúdo]
    A --> N[Explorar Novas Trilhas]
    N --> O[Catálogo de Trilhas]
    O --> J

