# Swim Monitor

Aplicação web para monitorização e gestão da carga de treino de natação.

## Funcionalidades atuais

- Dashboard com volume total, atletas, sessões, PSE média e volume por zona.
- Gestão de atletas: criar, editar, ativar/desativar e eliminar.
- Registo de sessões com:
  - data;
  - microciclo;
  - período AM/PM;
  - atletas presentes;
  - tarefas;
  - distância, repetições e distância total;
  - estilo;
  - zona de intensidade;
  - tipo de trabalho;
  - material;
  - descrição, intervalo e observações.
- Monitorização de PSE, FC ao acordar, qualidade do sono e TRIMP.
- Configuração de zonas e materiais.
- Exportação dos dados para CSV.
- Confirmação antes de eliminar dados.
- Dados guardados no `localStorage` do navegador.

## Como colocar no GitHub

1. Cria um repositório no GitHub, por exemplo `swim-monitor`.
2. Envia `index.html`, `styles.css`, `app.js` e `README.md`.
3. No repositório, abre **Settings → Pages**.
4. Em **Build and deployment**, escolhe:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Guarda e aguarda pela publicação.

O site ficará acessível através do endereço GitHub Pages do repositório.

## Importante sobre os dados

Esta primeira versão é adequada para protótipo e utilização num único navegador. Os dados não são automaticamente sincronizados entre treinadores ou dispositivos. Para uma versão de produção, deve ser acrescentada autenticação e uma base de dados online, por exemplo Supabase ou Firebase.

## Próximas fases recomendadas

1. Filtros por época, equipa, atleta, microciclo, data e AM/PM.
2. Dashboard individual do atleta.
3. Planeamento de microciclos.
4. Importação de Excel/CSV do Polar.
5. Cálculo validado de TRIMP.
6. Composição corporal e fórmula de Evans (2005), com registo da fórmula usada.
7. Testes personalizados e gráficos de evolução.
8. Treino de ginásio e ciclo menstrual.
9. Base de dados online com contas para treinadores.
10. Exportação Excel e cópia de segurança.
