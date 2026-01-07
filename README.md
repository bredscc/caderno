# Caderno de Estudos

Uma ferramenta web minimalista para anotar dúvidas durante o estudo sem perder o foco. Organize suas questões e copie tudo de uma vez para buscar explicações depois.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.x-61dafb.svg)
![Vite](https://img.shields.io/badge/Vite-5.x-646cff.svg)

## O Problema

Você está estudando e surge uma dúvida. Você para para pesquisar no Google, acaba em 10 abas diferentes, perde o foco e esquece onde estava. Isso te soa familiar?

## A Solução

Este caderno digital permite que você **anote rapidamente suas dúvidas sem interromper o fluxo de estudo**. No final da sessão, você pode copiar todas as anotações formatadas e buscar as respostas de uma vez - seja em uma IA, com um professor, ou pesquisando depois.

## Funcionalidades

- Interface minimalista inspirada em cadernos físicos
- Anotação rápida de dúvidas durante o estudo
- Campo para registrar o assunto que está estudando
- Numeração automática das anotações
- Timestamp de cada registro
- Botão para copiar tudo formatado
- Visual com linhas de caderno e espiral decorativa
- Design responsivo para desktop e mobile

## Tecnologias

- **React 18** - Biblioteca JavaScript
- **Vite** - Build tool
- **Tailwind CSS v4** - Estilização
- **Lucide React** - Ícones
- **Google Fonts** - Tipografia (Inter + Caveat)

## Instalação

```bash
# Clone o repositório
git clone https://github.com/bredscc/caderno-duvidas.git
cd caderno-duvidas

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
```

Acesse `http://localhost:5173`

## Como Usar

1. **Defina o assunto** (opcional) no campo superior
2. **Anote suas dúvidas** conforme elas surgem durante o estudo
3. **Continue estudando** - suas anotações ficam salvas na tela
4. **Copie tudo** ao final usando o botão "Copiar Tudo"
5. **Cole no Claude.ai, ChatGPT, ou onde preferir** para obter explicações

## Build para Produção

```bash
npm run build
```

Os arquivos otimizados estarão na pasta `dist/`

## Deploy

Este projeto está configurado para deploy no GitHub Pages. O arquivo está hospedado em:
`https://brecketline.me/caderno/`

Para fazer deploy:

```bash
# Configure o base no vite.config.js para seu caminho
base: '/caderno/'

# Build e copie para seu repositório de páginas
npm run build
cp -r dist/* /caminho/para/seu/github.io/caderno/
```

## Estrutura do Projeto

```
caderno-duvidas/
├── src/
│   ├── App.jsx          # Componente principal
│   ├── main.jsx         # Entry point
│   └── index.css        # Estilos do Tailwind
├── public/
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
└── README.md
```

## Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## Roadmap

Possíveis melhorias futuras:

- [ ] Salvar anotações no localStorage
- [ ] Categorização de dúvidas por tags
- [ ] Exportar para PDF ou Markdown
- [ ] Temas de cores personalizáveis
- [ ] Modo escuro
- [ ] Atalhos de teclado adicionais

## Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## Autor

**Brenda**

- GitHub: [@bredscc](https://github.com/bredscc)
- Website: [brecketline.me](https://brecketline.me)

## Agradecimentos

- Comunidade React e Tailwind CSS

---

Desenvolvido com foco em produtividade e aprendizado eficiente
