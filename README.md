# vagas-app
## Estrutura do projeto

src/
├── assets/ # Arquivos estáticos (imagens, fonts, etc.)
├── components/ # Componentes Vue reutilizáveis
│ ├── common/ # Componentes genéricos (botões, modais, etc.)
│ ├── vagas/ # Componentes específicos de vagas
│ │ ├── VagasList.vue # Listagem de vagas
│ │ ├── VagaForm.vue # Formulário de vaga
│ │ └── VagaCard.vue # Card individual de vaga
│ └── curriculos/ # Componentes específicos de currículos
│ ├── CurriculoForm.vue
│ └── CurriculoList.vue
├── views/ # Páginas/views da aplicação
│ ├── VagasView.vue # Página de listagem/cadastro de vagas
│ ├── VagaDetailView.vue # Página de detalhe de vaga
│ ├── CurriculosView.vue # Página de currículos
│ ├── MatchesView.vue # Página de matches
│ └── DashboardView.vue # Página inicial/dashboard
├── store/ # Gerenciamento de estado (Vuex)
│ ├── modules/ # Módulos do Vuex
│ │ ├── vagas.js # Estado/mutações/ações para vagas
│ │ ├── curriculos.js # Estado/mutações/ações para currículos
│ │ └── matches.js # Estado/mutações/ações para matches
│ └── index.js # Arquivo principal do Vuex
├── router/ # Configuração de rotas
│ └── index.js # Definição de todas as rotas
├── services/ # Serviços/API calls
│ ├── api.js # Configuração do axios
│ ├── vagasService.js # Chamadas API para vagas
│ └── curriculosService.js # Chamadas API para currículos
├── App.vue # Componente raiz
└── main.js # Ponto de entrada da aplicação
