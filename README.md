# Angular Task Manager

Aplicação para organizar tarefas pendentes e concluídas, desenvolvida com Angular, Angular Material e SCSS. Utiliza JSON Server como API local.

## Executar

Com Node.js e npm instalados:

```bash
npm install
npm start
```

- Aplicação: [://localhost:4200](http://localhost:4200)
- API: [http://localhost:3000/tarefas](http://localhost:3000/tarefas)

A cada `npm start`, o banco local é restaurado a partir de `banco.base.json`, descartando os dados da execução anterior. Recarregar a página preserva os dados da execução atual.

## GitHub Codespaces

Execute `npm install` e `npm start`. Abra a porta 4200 pela aba Ports,
com visibilidade Private. As chamadas à API passam pelo proxy do Angular.

## Build

```bash
npm run build
```

Os arquivos gerados ficam em `dist/`.

## Créditos

Favicon criado por [Infinyteam](https://icon-icons.com/pt/authors/1146-infinyteam), obtido em [Icon-Icons](https://icon-icons.com/pt/icone/area-de-transferencia-notas-lista-tarefas/191193).
