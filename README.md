# Testes de API – Urban.Grocers

![QA](https://img.shields.io/badge/Testes-API-blue)
![Ferramenta](https://img.shields.io/badge/Postman-Test%20Execution-orange)
![Documentação](https://img.shields.io/badge/apiDoc-Referência-informational)
![Bug Tracking](https://img.shields.io/badge/Jira-Relatórios%20de%20Bug-orange)

---

## 📌 Sobre o Projeto

Este projeto foi desenvolvido durante o estudo de testes de API no contexto do aplicativo Urban.Grocers. O foco foi testar novos endpoints adicionados à API, relacionados a kits de produtos e cálculo de entrega via Order and Go. Os testes foram realizados com auxílio da documentação técnica (apiDoc), utilizando o Postman como ferramenta de execução.

---

## 🎯 Objetivo do Projeto

Testar e validar dois novos recursos da API do Urban.Grocers:
1. **Adicionar produtos a um kit** (`POST /api/v1/kits/{id}/products`);
2. **Verificar disponibilidade e custo do serviço de entrega Order and Go** (`POST /order-and-go/v1/delivery`).

---

## 🔧 Tecnologias e Ferramentas

- **Postman** — execução de requisições
- **apiDoc** — referência da API
- **Google Sheets** — checklist dos testes
- **Jira** — rastreamento de bugs

---

## ▶️ Como Executar

1. Abra o **Postman**.  
2. Importe a coleção de requisições ou configure os endpoints manualmente conforme o **apiDoc**.  
3. Configure os parâmetros e payloads de acordo com os valores definidos no checklist.  
4. Execute as requisições, valide as respostas e compare com os critérios de aceite.  
5. Registre eventuais bugs no **Jira**, seguindo as boas práticas de relato (etapas, resultado esperado, resultado real, prioridade).

---

## 🧾 Resultado

- Checklist de testes cobrindo cenários positivos e negativos;
- Testes executados no **Postman** conforme critérios;
- Bugs relatados no **Jira**;
- Evidências consolidadas no Google Sheets;

---

## 📚 Aprendizados

- Como interpretar requisitos de API e traduzir em casos de teste;
- Criar e organizar checklists de teste;
- Utilizar o Postman para enviar requisições e validar respostas;
- Reportar bugs de forma clara no Jira;

---

## 💡 Melhorias Futuras

- Automatizar os testes de API com ferramentas como Newman ou RestAssured;

---

## 📂 Arquivos do Projeto

- ✅ [Checklist de testes – Google Sheets](https://docs.google.com/spreadsheets/d/1to5l7gcZbPaLRpjes2cyLjXu4T6rHYGv/edit?usp=sharing&ouid=117698170295509867083&rtpof=true&sd=true)  
- 🐞 [Relatórios de bugs – Jira](https://celiadepaivabruno.atlassian.net/jira/software/c/projects/S4/issues?jql=project%20%3D%20%22S4%22%20ORDER%20BY%20created%20DESC)

---

## 🇺🇸 Project Summary

**Urban.Grocers API Testing** — QA project focused on manual testing of new API endpoints for **Urban.Grocers**.  
Scope: test checklist design, execution with **Postman**, bug tracking in **Jira**, and final test report.

