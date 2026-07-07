# 🏋️ NutriFit Suplementos

> Protótipo de loja virtual de um fabricante fictício de suplementos alimentares, desenvolvido com HTML e CSS puros como projeto de estudo/portfólio.

## 📖 Sobre o projeto

**NutriFit Suplementos** é o front-end de um e-commerce, com página inicial, catálogo de produtos, páginas de detalhe de cada item, e telas de login e cadastro. O foco do projeto é a construção de uma interface moderna, responsiva e orientada a conversão, no estilo de lojas de suplementos e nutrição esportiva.

> ⚠️ Este é um projeto **somente de front-end** (sem back-end, banco de dados ou integração de pagamento). Funcionalidades como carrinho, busca e envio de formulários (login, cadastro, newsletter) representam a interface, mas ainda não possuem lógica funcional.

## ✨ Funcionalidades

- 🏠 **Página inicial** com banner de destaque, categorias (Whey, Creatina, Vitaminas, Acessórios) e seção de mais vendidos
- 🛍️ **Catálogo de produtos** com listagem em cards (imagem, nome, descrição e preço)
- 📄 **Páginas de detalhe** individuais para cada produto
- 🔐 **Telas de login e cadastro** de usuário
- 📬 Formulário de newsletter ("Time de Elite")
- 📱 **Menu responsivo** para dispositivos móveis
- 🦶 Rodapé com links institucionais, suporte e redes sociais

## 🛠️ Tecnologias utilizadas

- **HTML5** — estruturação semântica das páginas
- **CSS3** — estilização e layout responsivo (um arquivo de estilo por página)
- **[Font Awesome](https://fontawesome.com/)** — ícones (carrinho, usuário, redes sociais etc.)

## 📁 Estrutura de pastas

```
nutrifit-suplementos/
├── assets/                        # Imagens de produtos, logo e demais recursos visuais
├── estilo/                        # Arquivos CSS do projeto (um por página)
├── index.html                     # Página inicial
├── tela-produtos.html             # Catálogo de produtos
├── detalhe_produto_01.html        # Detalhe do produto — Gold Whey
├── detalhe_produto_02.html        # Detalhe do produto — Creatina Monohidratada
├── detalhe_produto_03.html        # Detalhe do produto — Pré-Treino
├── detalhe_produto_04.html        # Detalhe do produto — Vitaminas
├── detalhe_produto_05.html        # Detalhe do produto
├── detalhe_produto_06.html        # Detalhe do produto — Coqueteleira
├── detalhe_produto_07.html        # Detalhe do produto — Whey Protein Iron Pulse
├── detalhe_produto_destaque.html  # Página de produto em destaque
├── tela_login.html                # Tela de login
├── tela_cadastro.html             # Tela de cadastro
├── LICENSE
└── README.md
```

## 🚀 Como executar o projeto

Como é um projeto estático (HTML/CSS/JS puros), não há dependências ou build para instalar.

```bash
# Clone o repositório
git clone https://github.com/lucaslandimdev/nutrifit-suplementos.git

# Acesse a pasta do projeto
cd nutrifit-suplementos

# Abra o index.html no navegador
```

💡 Dica: para uma melhor experiência de desenvolvimento (com recarregamento automático), use a extensão **Live Server** do VS Code.

## 🗺️ Páginas do projeto

| Página | Arquivo |
|---|---|
| Home | `index.html` |
| Catálogo de produtos | `tela-produtos.html` |
| Detalhe do produto | `detalhe_produto_01.html` … `detalhe_produto_07.html` |
| Produto em destaque | `detalhe_produto_destaque.html` |
| Login | `tela_login.html` |
| Cadastro | `tela_cadastro.html` |

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request* com melhorias, correções ou novas funcionalidades.

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/minha-feature`)
3. Faça commit das suas alterações (`git commit -m 'Adiciona minha feature'`)
4. Faça push para a branch (`git push origin feature/minha-feature`)
5. Abra um Pull Request

## 👨‍💻 Autor

Desenvolvido por **Lucas Landim**

[![GitHub](https://img.shields.io/badge/GitHub-lucaslandimdev-181717?style=flat&logo=github)](https://github.com/lucaslandimdev)

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
