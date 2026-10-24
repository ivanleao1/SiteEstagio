Markdown
# 🎓 Portal do Aluno – IFG Câmpus Goiânia

> Aplicação web interativa para suporte, orientação acadêmica e redirecionamento de serviços aos alunos do Ensino Médio, Técnico Integrado e EJA do IFG Câmpus Goiânia.

Projeto desenvolvido para fins de **validação de estágio supervisionado** do curso.

---

## 📌 Sobre o Projeto

O **Portal do Aluno** foi projetado para centralizar as principais informações acadêmicas e operacionais do cotidiano escolar do IFG Câmpus Goiânia em uma única interface leve, moderna e acessível. 

A plataforma resolve o problema de dispersão de dados, facilitando a navegação de estudantes do ensino médio e técnico integrado para consultas frequentes sobre normas, certidões e links diretos do **SUAP**.

---

## 🛠️ Tecnologias e Paradigmas

A aplicação foi desenvolvida seguindo a arquitetura de **Single Page Application (SPA)** leve e sem dependências pesadas de frameworks externos:

* **HTML5 Semântico:** Estruturação focada em acessibilidade e suporte a leitores de tela.
* **CSS3 Moderno:** Layout responsivo (Mobile-First) com variáveis de estilo e alternância dinâmica de tema.
* **JavaScript (ES6+ Vanilla):** Lógica client-side pura combinando:
  * **Programação Orientada a Objetos (POO):** Encapsulamento do controle do portal, gerenciamento de acessibilidade e controller de buscas.
  * **Programação Funcional:** Métodos imutáveis de array para filtragem e busca proativa de dúvidas.

---

## ♿ Requisitos de IHC e Acessibilidade

Para atender aos padrões de Interação Humano-Computador (IHC) e diretrizes de acessibilidade (WCAG 2.1 e e-MAG):

* 🔍 **Controle de Zoom de Texto:** Botões para aumentar, diminuir e restaurar o tamanho das fontes (`A+`, `A-`, `Reset`).
* 🌓 **Modo Alto Contraste:** Suporte a usuários com baixa visão ou fotofobia.
* 📱 **Layout Responsivo:** Otimizado para smartphones, tablets e desktops.
* 🏷️ **Busca Instantânea por Tags:** Filtro proativo de informações por palavras-chave relevantes (*SUAP*, *Frequência*, *Estágio*, *Certificado*).

---

## 📑 Módulos e Funcionalidades

1. **Atalhos e Redirecionamentos SUAP:** Acesso rápido ao Boletim, Frequência, Renovação de Matrícula e Requerimentos.
2. **Guia de Regimento Acadêmico:** Esclarecimentos sobre frequência mínima (75%), critérios de aprovação (Média 6.0) e regramanto de segunda chamada.
3. **Fluxos de Certificação e Estágio:** Orientações detalhadas em formato *accordion* para obtenção de certificados (EJA/Integrado) e início de estágio.

---

## 🚀 Como Executar o Projeto Localmente

Como o projeto é construído em tecnologia web pura, **não é necessário instalar o Node.js ou `npm`**.

1. Clone este repositório:
   ```bash
   git clone [https://ivanleao1.github.io/SiteEstagio/]
