# 📱 Portfólio de Desenvolvedor JavaScript

Um portfólio responsivo e dinâmico para apresentar suas habilidades, experiência profissional e projetos desenvolvidos em JavaScript.

## 🎯 Sobre o Projeto

Este é um portfólio pessoal desenvolvido como parte do curso **JavaScript Developer** da plataforma **Digital Innovation One (DIO)**. O projeto demonstra conhecimentos em:

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização responsiva e layout moderno
- **JavaScript** - Manipulação de DOM e fetch de dados
- **JSON** - Estrutura de dados dinâmica

## ✨ Funcionalidades

- ✅ **Seção de Perfil** - Foto, nome, profissão, localização e contatos
- ✅ **Hard Skills** - Ferramentas e tecnologias (com ícones)
- ✅ **Soft Skills** - Competências pessoais
- ✅ **Idiomas** - Språk que domina
- ✅ **Portfólio** - Projetos desenvolvidos com links
- ✅ **Experiência Profissional** - Histórico de trabalhos
- ✅ **Acordeão Interativo** - Menu retrátil para melhor UX
- ✅ **Responsivo** - Funciona em desktop, tablet e mobile

## 📂 Estrutura do Projeto

```
js-developer-portfolio/
├── index.html              # Página principal
├── data/
│   ├── profile.json        # Dados do portfólio
│   └── imgs/              # Imagens dos projetos
├── assets/
│   ├── css/               # Estilos
│   │   ├── global.css
│   │   ├── header.css
│   │   ├── acordeon.css
│   │   ├── languages.css
│   │   ├── portfolio.css
│   │   ├── experience.css
│   │   └── skills.css
│   ├── js/                # Lógica JavaScript
│   │   ├── main.js
│   │   ├── api.js
│   │   └── acordeon.js
│   ├── img/               # Imagens e ícones
│   │   └── icons/
│   │       └── tools/
│   └── fonts/            # Fontes customizadas
└── README.md             # Este arquivo
```

## 🚀 Como Usar

### 1. Clonar o Repositório

```bash
git clone https://github.com/BrunoLVentura1447/js-developer-portfolio.git
cd js-developer-portfolio
```

### 2. Executar Localmente

#### Com Node.js (http-server):

```bash
# Instalar globalmente (se não tiver)
npm install -g http-server

# Iniciar servidor na porta 8080
http-server ./
```

#### Ou com Python:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Depois acesse: `http://localhost:8080` (ou a porta indicada)

## 📋 Personalizando com seus Dados

Todos os dados são carregados do arquivo `data/profile.json`. Para personalizar seu portfólio, edite este arquivo:

```json
{
  "name": "Seu Nome",
  "photo": "URL-da-sua-foto",
  "job": "Sua Profissão",
  "location": "Sua Localização",
  "phone": "Seu Telefone",
  "email": "seu-email@example.com",
  "skills": {
    "hardSkills": [
      {
        "nome": "JavaScript",
        "logo": "URL-do-icone"
      }
    ],
    "softSkills": ["Comunicação", "Trabalho em equipe"]
  },
  "languages": ["Português", "Inglês"],
  "portfolio": [
    {
      "name": "Título do Projeto",
      "url": "Link do projeto",
      "github": "true"
    }
  ],
  "professionalExperience": [
    {
      "name": "Cargo - Empresa",
      "period": "MM/YYYY - MM/YYYY",
      "description": "Descriptions das atividades"
    }
  ]
}
```

## 🛠️ Tecnologias Utilizadas

- ![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
- ![Normalize.css](https://img.shields.io/badge/Normalize.css-49B596?style=flat)
- ![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=flat&logo=google&logoColor=white)

## 📱 Responsividade

O portfólio é totalmente responsivo e se adapta para:
- 📱 Dispositivos móveis (320px+)
- 📱 Tablets (768px+)
- 🖥️ Desktops (1024px+)

## 🎓 O que Aprendi

- Manipulação do DOM com JavaScript
- Requisições HTTP com Fetch API
- Estruturação de dados com JSON
- CSS Layout (Flexbox, Grid)
- Acessibilidade web
- Desenvolvimento responsivo

## 🔗 Links Úteis

- [Digital Innovation One (DIO)](https://www.dio.me)
- [Curso JavaScript Developer](https://www.dio.me/courses/javascript-developer)
- [Repositório no GitHub](https://github.com/BrunoLVentura1447/js-developer-portfolio)

## 👤 Autor

**Bruno Luiz Ventura**
- 📧 Email: brunoluizventura15@gmail.com
- 🐙 GitHub: [@BrunoLVentura1447](https://github.com/BrunoLVentura1447)
- 💼 LinkedIn: [LinkedIn Profile](seu-linkedin-aqui)

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/minha-feature`)
3. Commit suas mudanças (`git commit -m 'Adicionando minha feature'`)
4. Push para a branch (`git push origin feature/minha-feature`)
5. Abra um Pull Request

## ⭐ Se achou útil, deixe uma estrela!

---

**Desenvolvido com ❤️ durante o bootcamp da DIO**
