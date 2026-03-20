# DoaFácil: Simplificando a Logística de Doações 🤝

![Status do Projeto](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange)
![Licença](https://img.shields.io/badge/License-MIT-blue.svg)
![Versão](https://img.shields.io/badge/Version-MVP%200.1-brightgreen)

O **DoaFácil** é um Produto Viável Mínimo (MVP) desenvolvido para resolver um problema crítico na logística de doações no Brasil: a falta de comunicação eficiente entre doadores individuais e Organizações Não Governamentais (ONGs), que frequentemente resulta no desperdício de itens de grande porte ou perecíveis.

---

## 📖 Sobre o Projeto

Muitas pessoas possuem itens em bom estado (móveis, eletrodomésticos, alimentos próximos ao vencimento) e desejam doá-los, mas esbarram na dificuldade de encontrar quem precisa e de organizar o transporte. Por outro lado, ONGs perdem oportunidades valiosas de arrecadação por não terem um canal centralizado para visualizar e reservar essas doações.

O DoaFácil atua como uma ponte digital, oferecendo uma plataforma web/mobile onde doadores podem anunciar seus itens rapidamente e ONGs podem buscar, reservar e agendar a retirada de forma organizada.

### 🎯 Objetivos do MVP
- **Validar a Hipótese:** Verificar se uma plataforma centralizada reduz o tempo que um item leva para sair da casa do doador e chegar a quem precisa.
- **Medir Engajamento:** Avaliar a adoção e o uso da ferramenta pelas ONGs locais.
- **Reduzir Desperdício:** Minimizar o descarte de itens úteis por falhas logísticas.

---

## 🚀 Funcionalidades Principais

A plataforma foi desenhada com foco na experiência do usuário, garantindo simplicidade e eficiência para ambas as personas:

1. **Autenticação Simples:** Login rápido e seguro utilizando Google ou Firebase.
2. **Catálogo Inteligente:** Feed de doações disponíveis com geolocalização, permitindo filtros por categoria e proximidade.
3. **Sistema de Reserva:** Botão "Tenho Interesse" que bloqueia o item temporariamente para a ONG, evitando conflitos.
4. **Comunicação Direta:** Chat integrado para alinhamento de detalhes logísticos entre doador e ONG.
5. **Notificações em Tempo Real:** Alertas via Push/E-mail sobre novos itens e confirmações de interesse.
6. **Dashboard de Gestão:** Painel para as ONGs acompanharem o histórico de coletas e gerenciarem recebimentos.

---

## 🛠️ Metodologia e Desenvolvimento

O projeto foi estruturado utilizando a metodologia de **Aprendizagem Baseada em Problemas (ABP)**, partindo de um diagnóstico profundo das dores dos usuários para a concepção da solução.

### Gerenciamento do Backlog
O desenvolvimento segue práticas ágeis de engenharia de software:
- **Identificação:** Levantamento de requisitos baseado nas necessidades reais de doadores e ONGs.
- **Especificação:** Detalhamento técnico para o desenvolvimento do CRUD de doações e integrações.
- **Priorização:** Foco nas funcionalidades essenciais para o MVP (Produto Viável Mínimo).

### Cronograma (8 Semanas)
- **Semanas 1-2:** Modelagem de dados e prototipagem de alta fidelidade (Figma).
- **Semanas 3-6:** Desenvolvimento do Core (Autenticação, CRUD, Chat).
- **Semanas 7-8:** Integração de geolocalização, testes com usuários reais e ajustes finais.

---

## 💻 Arquitetura e Tecnologias

O DoaFácil foi projetado para ter **custo inicial praticamente zero**, utilizando serviços em nuvem escaláveis e gratuitos para a fase de validação:

- **Frontend:** [React / React Native / Vue.js - *A definir conforme implementação*]
- **Backend as a Service (BaaS):** Firebase (Autenticação, Banco de Dados em Tempo Real, Storage para imagens).
- **Hospedagem:** Vercel (para a aplicação web).
- **Geolocalização:** Google Maps API / Mapbox.

---

## 📊 Métricas de Sucesso (KPIs)

Para validar o impacto do projeto, acompanhamos as seguintes métricas:

| Métrica | Descrição | Objetivo |
|---|---|---|
| **Taxa de Conversão** | % de doações postadas que foram reservadas por uma ONG. | Validar a eficiência do *matching*. |
| **Tempo Médio de Retirada** | Tempo entre a postagem do item e a confirmação de entrega. | Validar a otimização logística. |
| **Feedback de Impacto** | Número estimado de pessoas beneficiadas (reportado pela ONG). | Quantificar o impacto social real. |

---

## 👥 Equipe Desenvolvedora

Este projeto foi idealizado e desenvolvido por:

- **Iago Santos** - [LinkedIn](#) | [GitHub](#)
- **Vithor Augusto** - [LinkedIn](#) | [GitHub](#)
- **Nelson Ribeiro** - [LinkedIn](#) | [GitHub](#)

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
*DoaFácil - Conectando quem quer ajudar com quem mais precisa.* 💙
