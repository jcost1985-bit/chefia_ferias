# Painel de Controle — CJP

Painel web estático para acompanhamento das demandas da CJP.

## Recursos
- 14 demandas iniciais cadastradas
- Prazo e contagem regressiva
- Prioridade automática:
  - Urgente: vencida ou até 2 dias
  - Alta: 3 a 7 dias
  - Média: 8 a 21 dias
  - Baixa: mais de 21 dias
  - Aguardando: dependência externa
- Status: Pendente, Em andamento, Aguardando, A avaliar, Concluída e Cancelada
- Busca e filtros
- Cadastro/edição/exclusão de demandas
- Histórico de evolução por campo
- Persistência no navegador (localStorage)
- Exportação/importação de backup JSON
- Layout responsivo

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie o arquivo `index.html`.
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)`.
6. Salve e aguarde o GitHub Pages publicar.

O painel funciona sem servidor ou banco de dados. Cada navegador guarda suas alterações localmente.
