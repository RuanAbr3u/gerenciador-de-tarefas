# 📋 Gerenciador de Tarefas

Um aplicativo web moderno para gerenciar suas tarefas diárias, construído com **React**, **Vite** e **Tailwind CSS**.

![React](https://img.shields.io/badge/React-18.3.1-blue?logo=react)
![Vite](https://img.shields.io/badge/Vite-5.4.1-646cff?logo=vite)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4.10-06B6D4?logo=tailwindcss)
![Node.js](https://img.shields.io/badge/Node.js-18+-339933?logo=node.js)

## ✨ Funcionalidades

- ✅ **Adicionar tarefas** com título e descrição
- ✅ **Marcar tarefas** como completas/incompletas
- ✅ **Deletar tarefas** não desejadas
- ✅ **Visualizar detalhes** das tarefas em página dedicada
- ✅ **Persistência de dados** com localStorage
- ✅ **Interface responsiva** com Tailwind CSS
- ✅ **Navegação fluida** com React Router

## 🚀 Como Começar

### Pré-requisitos

- Node.js 18+ instalado
- npm ou yarn

### Instalação

1. Clone o repositório:

```bash
git clone https://github.com/RuanAbr3u/gerenciador-de-tarefas.git
cd gerenciador-de-tarefas
```

2. Instale as dependências:

```bash
npm install
```

3. Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

4. Abra o navegador em [http://localhost:5173](http://localhost:5173)

## 📦 Scripts Disponíveis

```bash
# Servidor de desenvolvimento
npm run dev

# Build para produção
npm run build

# Verificar código com ESLint
npm run lint

# Visualizar build de produção
npm run preview
```

## 🏗️ Estrutura do Projeto

```
src/
├── components/
│   ├── AddTask.jsx        # Formulário para adicionar tarefas
│   ├── Button.jsx         # Componente reutilizável de botão
│   ├── Input.jsx          # Componente reutilizável de input
│   ├── Tasks.jsx          # Lista de tarefas
│   └── Title.jsx          # Título da aplicação
├── pages/
│   └── TaskPage.jsx       # Página de detalhes da tarefa
├── App.jsx                # Componente principal
├── main.jsx               # Entrada da aplicação
└── index.css              # Estilos globais
```

## 🛠️ Tecnologias Utilizadas

- **React 18.3** - Biblioteca para construir interfaces
- **Vite 5.4** - Build tool rápido e moderno
- **Tailwind CSS 3.4** - Framework CSS utilitário
- **React Router 6.26** - Roteamento na aplicação
- **Lucide React 0.435** - Ícones SVG
- **UUID 10.0** - Geração de IDs únicos
- **ESLint** - Verificação estática de código

## 💾 Armazenamento de Dados

As tarefas são salvas automaticamente no **localStorage** do navegador. Ao recarregar a página, todas as tarefas criadas serão recuperadas.

## 🎨 Personalizando Estilos

Os estilos são gerenciados com Tailwind CSS. Para personalizar a tema, edite `tailwind.config.js`:

```js
export default {
  content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
  theme: {
    extend: {
      // Adicione suas customizações aqui
    },
  },
  plugins: [],
};
```

## 📝 Exemplo de Uso

1. Digite um título e descrição para a tarefa
2. Clique em "Adicionar Tarefa"
3. Clique na tarefa para marcar como completa
4. Clique no ícone ver mais (➜) para visualizar detalhes
5. Clique no ícone lixeira (🗑️) para deletar a tarefa

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 👨‍💻 Autor

**Ruan Abreu**

- GitHub: [@RuanAbr3u](https://github.com/RuanAbr3u)
- LinkedIn: [Ruan Abreu](https://www.linkedin.com/in/ruan-abreu/)

---

⭐ Se este projeto foi útil para você, deixe uma estrela! ⭐
