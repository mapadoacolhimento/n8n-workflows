# n8n-workflows
Backup dos worflows disponíveis do n8n utilizados pelo Mapa

## Como funciona
O Worflow de backup diariamente busca todos os worflows disponíveis via a api do n8n e analisa se é um novo worflow ou se teve alguma mudança, baseado no arquivo salvo no repositório, e, caso necessário, realiza o commit da alteração ou criação nesse repositório. 
Os aruivos dos workflows são salvos no formato json. 
