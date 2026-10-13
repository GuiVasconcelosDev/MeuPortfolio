# Portfólio — Guilherme Vasconcelos

Portfólio pessoal de desenvolvedor backend (Java, Spring Boot e PostgreSQL), com visual editorial e animações guiadas por scroll.

## Tecnologias

- HTML, CSS e JavaScript puros, em um único arquivo
- [GSAP](https://gsap.com/) + ScrollTrigger (via CDN)
- Fontes: Instrument Serif, Inter Tight e JetBrains Mono (Google Fonts)

## Animações (ScrollTrigger)

- Entrada do título com máscara
- Barra de progresso da página
- Parallax da imagem do hero
- Texto do "Sobre" aparecendo palavra por palavra
- Faixa de tecnologias que se move com o scroll
- Cards de projetos com revelação em máscara e parallax interno
- Entrada em sequência das colunas da stack

Os efeitos são desativados para quem usa "reduzir movimento" no sistema.

## Estrutura

```
.
├── index.html
├── README.md
└── assets/
    ├── hero.jpg
    ├── barbearia.jpg
    ├── loja.jpg
    └── auth.jpg
```

Se uma imagem não existir, o site mostra um degradê escuro no lugar.

## Como rodar

1. Clone o repositório:
   ```bash
   git clone https://github.com/GuiVasconcelosDev/NOME-DO-REPO.git
   ```
2. Abra o `index.html` no navegador, ou use a extensão **Live Server** do VS Code.

Não precisa instalar nada, mas é preciso estar online para carregar o GSAP e as fontes.

## Imagens

| Arquivo | Uso | Tamanho recomendado |
|---|---|---|
| `hero.jpg` | Fundo do hero | 1920 × 1080 px |
| `barbearia.jpg` | Card Barbearia SaaS API | 1200 × 1440 px (5:6) |
| `loja.jpg` | Card Loja | 1200 × 1440 px (5:6) |
| `auth.jpg` | Card Project Fullstack Login | 1200 × 1440 px (5:6) |

Use JPG ou WebP, com até uns 300 KB cada.

## Personalização

- **Cores:** variáveis no início do `<style>`, em `:root` (tema claro e escuro).
- **Projetos:** blocos `<a class="card">` na seção de projetos.
- **Contato:** link `mailto:` e links de GitHub e LinkedIn na seção final.

## Publicação

No GitHub, vá em **Settings > Pages**, escolha a branch `main` e a pasta `/ (root)`. O site fica disponível em `https://guivasconcelosdev.github.io/NOME-DO-REPO/`.

## Contato

- E-mail: guilhermevasconcelos@gmail.com
- GitHub: [GuiVasconcelosDev](https://github.com/GuiVasconcelosDev)
- LinkedIn: [guilherme-vasconcelos-dev](https://linkedin.com/in/guilherme-vasconcelos-dev)