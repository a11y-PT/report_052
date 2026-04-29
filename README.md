---
website: "Câmara de Felgueiras"          # Entre as aspas escreve o nome do website
date: "17/04/2026"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://cm-felgueiras.pt/"   # Entre as aspas escreve o domínio do website
a11y_statement: "https://cm-felgueiras.pt/municipio/imprensa/acessibilidade/" # Entre as aspas escreve o URL da Declaração de Acessibilidade do website
owner: "Câmara de Felgueiras"         # Entre as aspas escrever o nome do owner do website
seal: "Prata"                          # Entre as aspas escreve Bronze, Prata ou Ouro
---

# {{ page.website }}

- Data de criação: {{ page.date }}
- URL: {{ page.uri }}
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}

## Relatório de Auditoria

<p>O presente relatório resultou da auditoria da informação publicada na <a href="{{ page.a11y_statement }}">Declaração de Acessibilidade e Usabilidade</a>.</p>

Consulte aqui a última atualização: [Relatório {{ page.website }}](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="29042026_report.html">(29/04/2026). Relatório {{ page.website }}</a></li>
  </ul>
</details>

<hr>

<p><small>2025 - 2026, GitTemplateReports (v.1.0.4)</small></p>
