# Casa Blanca — Sistemas Internos

Aplicativos internos de uso diário da Casa Blanca Imobiliária (Iguatu-CE), cada um em um único arquivo HTML autocontido — sem necessidade de instalação, servidor ou build. Basta abrir o arquivo direto no navegador (Chrome ou Edge recomendados).

Os dados de cada sistema ficam salvos localmente no navegador (`localStorage`). Por isso, cada arquivo deve sempre ser aberto a partir do mesmo local no computador (ex: salvo em Documentos), e é recomendável exportar backups em JSON periodicamente usando a opção "Backup" de cada sistema.

## Sistemas

| Arquivo | Descrição |
|---|---|
| [`casa-blanca-agenda-dede.html`](./casa-blanca-agenda-dede.html) | Agenda mensal e controle financeiro dos serviços do Sr. Dedé (pedreiro): calendário de saídas, registro de serviços/orçamentos/verificações e relatório mensal. |
| [`casa-blanca-manutencao.html`](./casa-blanca-manutencao.html) | Gestão de manutenção dos imóveis. |
| [`casa-blanca-minhas-demandas.html`](./casa-blanca-minhas-demandas.html) | Painel de demandas pessoais/internas, com categorias, prioridades e acompanhamento de status. |
| [`casa-blanca-servicos-proprietario.html`](./casa-blanca-servicos-proprietario.html) | Controle de serviços realizados por proprietário, com lançamentos de despesas e geração de relatório. |

## Uso

1. Baixe o arquivo `.html` desejado.
2. Abra-o diretamente no navegador (duplo clique ou arrastar para uma aba).
3. Os dados digitados ficam salvos automaticamente no navegador.
