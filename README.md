# Belle Time: Portal Ella's (Web & UX/UI Architecture)

> **Status do Projeto:** Fase 1 Concluída (Arquitetura de Interação e Prototipagem de Alta Fidelidade) 

O **Belle Time** é um sistema web responsivo projetado para digitalizar e otimizar a gestão de agendamentos do Studio Ella's, um salão de beleza real localizado em Sorocaba/SP. 

Este repositório documenta a evolução da plataforma para uma arquitetura em nuvem (Web/Mobile First). Para visualizar a **versão legada (V1)** desenvolvida como aplicação Desktop (CRUD Python/Linux), [clique aqui e acesse o repositório anterior](https://github.com/isabellascarassatii/BelleTime_Agenda).

---

## 🎯 O Problema de Negócio
O salão operava sob um modelo de gestão estritamente analógico (WhatsApp e papel), o que gerava alta fricção na comunicação, lentidão no tempo de resposta e constantes conflitos de agenda (*double-booking*). A consequência direta era a sobrecarga cognitiva da gestora e a perda de receita.

## 💡 A Solução e Arquitetura de Interface
Com o objetivo de sanar essas dores, o projeto foi pivotado de uma aplicação desktop para uma **Single Page Application (SPA) Mobile First**. O foco desta etapa foi a engenharia de usabilidade e o Design Centrado no Usuário.

Entregas validadas nesta etapa:
* **Portfólio Digital:** Vitrine autônoma para redução de suporte consultivo inicial.
* **Calendário Síncrono (Client-Side):** Lógica visual de bloqueio de horários ocupados para prevenção de reservas duplicadas.
* **Painel Administrativo:** *Dashboard* estruturado para a gestora definir sua disponibilidade de atendimento de forma centralizada.

---

## 🛠️ Tecnologias e Metodologias Aplicadas

* **Prototipagem & UI Design:** Figma (Uso avançado de Componentes, Variantes e Variáveis Lógicas).
* **Engenharia de Requisitos:** Lean Canvas, Criação de Personas, Mapeamento de Jornada.
* **Garantia de Qualidade (QA/UX):** Avaliação Heurística (Nielsen) e métricas SUS (*System Usability Scale*).
* **Conformidade:** Estruturação de formulários alinhada aos princípios da LGPD.

---

## 🔗 Navegação Interativa
A interface de alta fidelidade está disponível para simulação interativa:
👉 **[Acessar Protótipo Interativo no Figma](https://studioellas.figma.site/)**

---

## 🚀 Roadmap Técnico (Próximos Passos)
A atual arquitetura visual e lógica foi validada e encontra-se madura para a transição para o desenvolvimento Full-Stack:

- [ ] **Front-End:** Desenvolvimento da interface utilizando HTML5, CSS3, JavaScript Vanilla e Bootstrap 5.
- [ ] **Back-End:** Implementação da API RESTful em **Python (Flask)**.
- [ ] **Persistência de Dados:** Modelagem e integração com banco de dados relacional **MySQL**.

---
*Desenvolvido com foco em resolução de problemas reais de negócios.*
