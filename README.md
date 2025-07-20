# DiBiTech Engenharia - Site para GitHub Pages

Este é o site da DiBiTech Engenharia, especializada em automação industrial e soluções tecnológicas.

## Como hospedar no GitHub Pages

1. **Crie um repositório no GitHub**
   - Faça login no GitHub
   - Clique em "New repository"
   - Nomeie o repositório (ex: `dibitech-site`)
   - Marque como público
   - Clique em "Create repository"

2. **Faça upload dos arquivos**
   - Faça upload de todos os arquivos desta pasta para o repositório
   - Ou use Git para fazer push dos arquivos:
     ```bash
     git init
     git add .
     git commit -m "Initial commit"
     git branch -M main
     git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
     git push -u origin main
     ```

3. **Configure o GitHub Pages**
   - Vá para Settings do repositório
   - Role até a seção "Pages"
   - Em "Source", selecione "Deploy from a branch"
   - Selecione "main" branch e "/ (root)"
   - Clique em "Save"

4. **Acesse seu site**
   - O site estará disponível em: `https://SEU_USUARIO.github.io/SEU_REPOSITORIO`
   - Pode levar alguns minutos para ficar online

## Estrutura dos Arquivos

```
dist/
├── index.html              # Página principal
├── vite.svg                # Ícone do Vite
├── README.md               # Este arquivo
└── assets/
    ├── index-r1gF4gNV.css  # Estilos CSS
    ├── index-VVYyHQzs.js   # JavaScript da aplicação
    ├── hero_image-BoYNYCpY.jpg # Imagem principal
    ├── logo-jpPbFh_Y.png   # Logo da empresa
    └── service_*.png       # Ícones dos serviços
```

## Sobre o Site

O site apresenta os serviços da DiBiTech Engenharia:
- Automação de Processos
- Desenvolvimento de Sistemas
- Infraestrutura de TI
- Ciência de Dados e ML
- Educação e Treinamento

### Contato
- Email: ruitobias@dibitech.com.br
- Telefone: (15) 98100-9064
- Localização: Apiaí - SP, Brasil

