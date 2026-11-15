# 🌱 Rota Verde

**Conectando moradores a coletores de recicláveis e promovendo a educação ambiental para um futuro mais sustentável.**

[**Acessar o site (em breve)**](#) · [**Instagram do Projeto**](https://www.instagram.com/proj.rotaverde)

---

**📌 Sumário**
* [📌 1. O Projeto](#-1-o-projeto)
* [💡 2. A Solução](#-2-a-solução)
* [🖥️ 3. Estrutura da Landing Page](#️-3-estrutura-da-landing-page)
* [✨ 4. Destaques](#-4-destaques)
* [🛠️ 5. Stack Tecnológica](#️-5-stack-tecnológica)
* [📁 6. Arquitetura do Projeto](#-6-arquitetura-do-projeto)
* [🗺️ 7. Processo do Projeto](#️-7-processo-do-projeto)
* [🚀 8. Como Executar Localmente](#-8-como-executar-localmente)
* [👥 9. Equipe](#-9-equipe)

---

## 📌 1. O Projeto

O **Rota Verde** é um projeto de extensão do curso de Engenharia da Computação do Centro Universitário de Viçosa (Univiçosa). Ele nasceu da necessidade de resolver um problema real na comunidade do bairro Laranjal (Viçosa - MG): a falta de informação centralizada e acessível sobre como descartar resíduos corretamente e para onde levá-los.

Uma pesquisa realizada com os moradores revelou que a maioria não sabe diferenciar resíduos recicláveis dos não recicláveis e desconhece a localização de pontos de coleta. O projeto está alinhado aos Objetivos de Desenvolvimento Sustentável (ODS) da ONU, especialmente o **ODS 11** (Cidades e Comunidades Sustentáveis) e o **ODS 12** (Consumo e Produção Responsáveis).

## 💡 2. A Solução

Uma **plataforma web acessível e intuitiva** que atua como uma ponte entre a população e os agentes de reciclagem. 

O grande diferencial do site é ser desenhado especificamente para atender pessoas com **pouco letramento digital**. Isso é feito por meio de uma navegação clara, linguagem simples, textos diretos, botões grandes e forte apoio visual (ícones). A plataforma oferece orientações sobre o descarte correto de materiais (papel, plástico, metal, vidro e lixo eletrônico) e permite que o usuário encontre o ponto de coleta mais próximo, com o nome e o telefone do coletor responsável.

## 🖥️ 3. Estrutura da Landing Page

| Seção | O que entrega |
| :--- | :--- |
| **Header / Navegação** | Logotipo e menu de acesso rápido às seções (Início, Como funciona, Ponto de coleta, Sobre nós, Contato). |
| **Hero** | Proposta de valor de impacto: título "Descarte certo, futuro sustentável", texto de apoio e botão de ação (CTA) para encontrar um ponto de coleta. |
| **O que reciclar** | Cards informativos e visuais sobre Papel, Plástico, Metal e Vidro, com exemplos práticos. |
| **Alerta de Lixo Eletrônico** | Destaque visual sobre o perigo do descarte incorreto de pilhas, baterias e eletrônicos. |
| **Ponto de Coleta** | Campo de busca por bairro, filtro por tipo de material e exibição do mapa com a localização e o contato do coletor. |
| **Sobre Nós** | Apresentação da equipe e do propósito do projeto de extensão. |
| **Contato** | Formulário para sugestões, dúvidas e cadastro de novos coletores. |
| **Footer** | Links úteis, informações de realização (Univiçosa) e redes sociais. |

## ✨ 4. Destaques

*   ♿ **Acessibilidade Digital:** Interface pensada para inclusão digital, com linguagem simples, hierarquia visual clara e botões grandes.
*   📱 **Responsividade:** Layout adaptado para desktop, tablet e mobile, garantindo que o acesso seja fácil em qualquer dispositivo.
*   📍 **Foco no Impacto Local:** Solução desenhada especificamente para a realidade do bairro Laranjal, com potencial de expansão para outras regiões.
*   🏗️ **HTML Semântico:** Estrutura de código pensada para ser compreensível por leitores de tela, reforçando o compromisso com a inclusão.
*   🧹 **Código Limpo:** O frontend utiliza apenas HTML, CSS e JavaScript puros (Vanilla), sem frameworks, facilitando a manutenção e o entendimento do código.

## 🛠️ 5. Stack Tecnológica

| Camada | Tecnologia | Propósito no projeto |
| :--- | :--- | :--- |
| **Front-end** | HTML5 · CSS3 · JavaScript | Estrutura semântica, estilização modular (identidade visual própria) e interatividade (filtros e busca). |
| **Back-end** | PHP | Processamento de formulários e funções dinâmicas no servidor. |
| **Design** | Figma | Criação do layout, prototipagem e definição da identidade visual (paleta de cores e tipografia Montserrat). |
| **Versionamento** | Git & GitHub | Controle de versão e colaboração em equipe. |

## 📁 6. Arquitetura do Projeto

```text
rota-verde/
├── assets/
│   ├── img/         # Imagens do site (fundo, logo)
│   └── icons/       # Ícones dos materiais recicláveis (SVG)
├── css/
│   └── style.css    # Estilos da página (identidade visual e responsividade)
├── js/
│   └── script.js    # Lógica de filtros, busca e interações
├── php/             # Arquivos de backend (processamento de formulários)
├── docs/            # Imagens para documentação e README
│   └── layout-site.png
├── index.html       # Arquivo HTML principal
└── README.md        # Documentação do projeto
```

## 🗺️ 7. Processo do Projeto

| Etapa | Status | Descrição |
| :--- | :---: | :--- |
| **1. Pesquisa com a Comunidade** | ✅ Concluído | Aplicação de formulário no bairro Laranjal para mapear o conhecimento sobre reciclagem e a aceitação da ferramenta digital. |
| **2. Design e Prototipagem** | ✅ Concluído | Criação da identidade visual no Figma, definindo paleta de cores, tipografia e layout focado em acessibilidade. |
| **3. Desenvolvimento Frontend** | 🚧 Em andamento | Estruturação das páginas com HTML semântico, estilização responsiva em CSS e implementação das interações via JavaScript. |
| **4. Desenvolvimento Backend** | ⏳ A fazer | Criação da lógica em PHP para processar os formulários de contato e cadastro de novos coletores. |
| **5. Testes de Usabilidade** | ⏳ A fazer | Validação da plataforma com usuários reais para garantir que a navegação seja simples e cumpra o objetivo de inclusão digital. |

## 🚀 8. Como Executar Localmente

O projeto é composto por HTML, CSS e JavaScript puros para o frontend, e PHP para o backend.

### 1. Clonar o repositório
```bash
git clone https://github.com/projeto-Rota-Verde/rota-verde.git
cd rota-verde
```

### 2. Visualizar a interface (Frontend)
Basta abrir o arquivo `index.html` em qualquer navegador. Para uma experiência de desenvolvimento mais completa, recomenda-se utilizar a extensão **Live Server** no VS Code.

### 3. Testar as funcionalidades (Backend PHP)
É necessário ter o PHP instalado na máquina. Na raiz do projeto, execute:
```bash
php -S localhost:8000
```
Depois, acesse `http://localhost:8000` no navegador.

## 👥 9. Equipe

| Participante | Papel no projeto |
| :--- | :--- |
| **Jade Moreira de Assis Rodrigues** | Desenvolvedora / UI/UX |
| **Anna Karolina Chaves Cabral** | Desenvolvedora |
| **Alice Izabel de Almeida** | Pesquisa e Conteúdo |
| **Kelly Aparecida Lelis** | Pesquisa e Conteúdo |
| **Lucas Celso Carvalho** | Pesquisa e Conteúdo |
| **Maria Clara Ferreira Vidigal** | Design e Divulgação |
| **Profa. Svetlana Fialho Soria Galvarro** | Orientação |

---

Feito pela comunidade, para a comunidade. 💚