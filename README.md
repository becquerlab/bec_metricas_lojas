# Painel de Métricas das Lojas — Bécquer Fragrances Lab

Painel semanal e mensal das cinco lojas: Pinheiros, Moema, Harmonia, Matarazzo e Morumbi.

**Endereço:** https://becquerlab.github.io/bec_metricas_lojas/

O acesso é protegido por senha. Os dados ficam comprimidos e criptografados em AES-256
dentro do próprio `index.html` — sem a senha, o arquivo não revela nada.

## Como é atualizado

Toda segunda-feira, de forma automática:

1. As cinco planilhas de registro de movimentação são lidas no Google Drive
2. Conversão, PA e ticket médio são recalculados a partir de atendimentos, vendas,
   itens e valor — as colunas de fórmula das planilhas não são usadas
3. Os números passam por uma análise que procura quedas fora do padrão, dias não
   lançados e erros de digitação
4. O `index.html` é reescrito e publicado aqui

Não edite `index.html` à mão: a próxima atualização sobrescreve o arquivo.
