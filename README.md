# n8n-workflows
Backup dos workflows disponíveis do n8n utilizados pelo Mapa

## Como funciona
O Workflow de backup diariamente busca todos os workflows disponíveis via a api do n8n e analisa se é um novo workflow ou se teve alguma mudança, baseado no arquivo salvo no repositório, e, caso necessário, realiza o commit da alteração ou criação nesse repositório. 
Os arquivos dos workflows são salvos no formato json. 
