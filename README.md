<h1 align="center">💰 Agenda-Financeira — Painel F.Moraes</h1>

<p align="center">
  Sistema de gestão de serviços para prestadores autônomos: clientes, agenda, faturamento e orçamentos em PDF.<br>
  Criado para uso real na minha empresa de elétrica e climatização.
</p>

<p align="center">
  <a href="https://moraesx3.github.io/Agenda-Finaceira/"><img src="https://img.shields.io/badge/Testar%20online-d68a45?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Testar online"></a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

<p align="center">
  <img src="telas.png" alt="Telas do sistema: painel, serviços, clientes e orçamentos" width="100%">
</p>

> Os dados mostrados são **fictícios**, apenas para demonstração.

## 🔧 O problema

Como eletricista e instalador de ar-condicionado, eu controlava serviços, clientes e orçamentos em papel e no bloco de notas do celular. Era difícil saber quanto faturei no mês, quais serviços estavam agendados e mandar um orçamento com aparência profissional.

## ✅ A solução

Um painel que roda no navegador do celular, sem instalação e sem servidor:

- **Painel:** faturamento do mês, histórico por mês, serviços concluídos e agendados, orçamentos pendentes
- **Serviços:** agenda com status (agendado, concluído, cancelado) e valor de cada serviço
- **Clientes:** cadastro com telefone e e-mail
- **Orçamentos:** criação, aprovação e **geração de PDF** com o logo da empresa, pronto para enviar no WhatsApp
- **Arquivos:** PDFs gerados ficam salvos no próprio app
- **Empresa:** dados que aparecem nos documentos (nome, CNPJ, contato)
- **Backup:** exporta e restaura todos os dados em um arquivo `.json`

## 🧱 Como funciona

| Parte | Como foi feita |
|---|---|
| Interface | HTML, CSS e JavaScript puro, pensada primeiro para celular |
| Armazenamento | `localStorage` do navegador: os dados ficam só no aparelho de quem usa |
| PDF | Biblioteca [jsPDF](https://github.com/parallax/jsPDF) |
| Hospedagem | GitHub Pages |

## ▶️ Como usar

1. Acesse **[moraesx3.github.io/minhas-financas](https://moraesx3.github.io/Agenda-Finaceira/)** ou baixe o `index.html` e abra no navegador.
2. O app abre com dados de exemplo. Para começar do zero com os seus dados, use **Empresa → Backup → Restaurar**, ou edite e exclua os exemplos.
3. Faça **backup** com frequência: os dados ficam salvos apenas no navegador.

## 🚧 Próximos passos

- [ ] Módulo de **PMOC**: cadastro de aparelhos de ar-condicionado e cronograma de manutenção
- [ ] Lembrete de clientes com manutenção vencendo
- [ ] Sincronização entre aparelhos

---

<p align="center">Feito por <a href="https://github.com/Moraesx3">Felipe Moraes</a> · Estudante de TADS · Eletricista e técnico em climatização · Corbélia/PR</p>
