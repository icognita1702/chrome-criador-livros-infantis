# chrome-criador-livros-infantis

Extensão Chrome baseada em React para criar livros infantis interativos com IA.

## 📖 Sobre o Projeto

Este repositório contém a estrutura base para uma extensão do Google Chrome que permite criar livros infantis interativos utilizando inteligência artificial. A extensão é construída com React e oferece uma interface intuitiva para criação de histórias personalizadas para crianças.

## 🎯 Propósito

O objetivo desta extensão é:
- Facilitar a criação de livros infantis personalizados
- Utilizar IA para gerar histórias criativas e educativas
- Proporcionar uma interface amigável e acessível
- Permitir personalização de personagens, cenários e temas
- Exportar livros em formato digital

## 📁 Estrutura do Projeto

```
chrome-criador-livros-infantis/
├── manifest.json           # Manifesto da extensão Chrome
├── package.json           # Dependências do projeto
├── README.md             # Este arquivo
├── public/
│   └── icons/           # Ícones da extensão
│       ├── icon16.png
│       ├── icon48.png
│       └── icon128.png
├── src/
│   ├── components/      # Componentes React
│   ├── pages/          # Páginas da aplicação
│   ├── services/       # Serviços e APIs
│   ├── utils/          # Funções utilitárias
│   ├── styles/         # Arquivos CSS/SCSS
│   ├── App.jsx         # Componente principal
│   └── index.jsx       # Ponto de entrada
└── assets/
    ├── images/         # Imagens e recursos
    └── fonts/          # Fontes personalizadas
```

## 🚀 Como Usar Este Repositório

### Pré-requisitos

- Node.js (versão 16 ou superior)
- npm ou yarn
- Google Chrome

### Instalação

1. Clone este repositório:
```bash
git clone https://github.com/icognita1702/chrome-criador-livros-infantis.git
cd chrome-criador-livros-infantis
```

2. Instale as dependências:
```bash
npm install
```

3. Execute o projeto em modo de desenvolvimento:
```bash
npm start
```

4. Para construir a extensão:
```bash
npm run build
```

### Carregar a Extensão no Chrome

1. Abra o Chrome e navegue até `chrome://extensions/`
2. Ative o "Modo do desenvolvedor" no canto superior direito
3. Clique em "Carregar sem compactação"
4. Selecione a pasta `build` do projeto

## 🛠️ Tecnologias Utilizadas

- **React**: Framework JavaScript para construção da interface
- **Chrome Extensions API**: APIs nativas do Chrome
- **JavaScript/ES6+**: Linguagem de programação
- **CSS3**: Estilização
- **Webpack**: Bundler de módulos

## 📝 Próximos Passos

Este repositório atualmente contém apenas a estrutura base. Os próximos passos incluem:

1. ✅ Criar estrutura de diretórios
2. ⬜ Configurar manifest.json
3. ⬜ Implementar componentes React básicos
4. ⬜ Integrar API de IA para geração de histórias
5. ⬜ Desenvolver interface de criação de livros
6. ⬜ Implementar sistema de exportação
7. ⬜ Adicionar testes
8. ⬜ Documentar código

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## 📄 Licença

Este projeto está em desenvolvimento inicial.

## 👥 Autor

- GitHub: [@icognita1702](https://github.com/icognita1702)

---

**Nota**: Este repositório está em fase inicial e contém apenas a estrutura de diretórios. O código da aplicação será adicionado gradualmente.
