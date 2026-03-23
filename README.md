---
website: "Selo de Usabilidade e Acessibilidade"          # Entre as aspas escreve o nome do website
date: "01/04/2025"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://selo.usabilidade.gov.pt"   # Entre as aspas escreve o domínio do website
owner: "ARTE, I.P."         # Entre as aspas escrever o nome do owner do website
seal: "Ouro"                          # Entre as aspas escreve Bronze, Prata ou Ouro
---

# {{ page.website }}

- Data de criação: {{ page.date }}
- URL: {{ page.uri }}
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}

## Relatório de Auditoria

Consulte aqui a última atualização: [Relatório do {{ page.website }}](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="12092025_report.html">(12/09/2025). Relatório do {{ page.website }}</a></li>
    <li><a href="30042025_report.html">(30/04/2025). Relatório do {{ page.website }}</a></li>   
  </ul>
</details>
