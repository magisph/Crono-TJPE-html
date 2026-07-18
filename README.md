# Crono-TJPE-html

Gerenciador do cronograma de estudos para o concurso do **TJPE**, como aplicativo web instalável (PWA).

## 🔗 Acesso online

**https://magisph.github.io/Crono-TJPE-html/**

> Publicado automaticamente via GitHub Pages a cada push na branch `main`.

## 📲 Instalar no celular/tablet Android (como app nativo)

1. Abra o link acima no **Chrome** (Android).
2. Toque no botão **⬇️ Instalar** na barra superior — ou no menu ⋮ do Chrome → **Instalar aplicativo / Adicionar à tela inicial**.
3. O app abre em tela cheia, com ícone próprio, e **funciona offline** (service worker + cache).

No desktop (Chrome/Edge) o mesmo botão de instalação aparece na barra de endereço.

## ✨ Funcionalidades

- Todos os **73 dias** e **146 sessões** (240 h) agrupados pelas **3 fases**, detalhando disciplina, temas/subtemas e carga horária.
- Marque cada sessão como concluída — a **barra de progresso** e o **gráfico de progressão** (acúmulo de sessões ao longo dos dias, até 26/09/2026) atualizam em tempo real.
- **Botão “📍 Hoje”** rola até o dia atual; **tema claro/escuro** (segue o sistema ou manual).
- Progresso salvo no dispositivo (`localStorage`); botão **Limpar progresso** com opção de desfazer.
- Design responsivo e acessível, otimizado para Android (Material Design 3, alvos de toque ≥ 48dp, `prefers-reduced-motion`).

## 🗂 Estrutura

| Arquivo | Função |
|---|---|
| `index.html` | App completo (dados do plano, estilos e scripts embutidos). |
| `manifest.webmanifest` | Manifesto PWA (nome, ícones, tema, standalone). |
| `sw.js` | Service worker — cache offline. |
| `icons/`, `apple-touch-icon.png`, `favicon.svg` | Ícones do app. |
| `.github/workflows/pages.yml` | Deploy automático no GitHub Pages. |

Uso offline por arquivo: também é possível apenas abrir o `index.html` no navegador (duplo-clique) — funciona sem servidor, mas a instalação como app exige o acesso via HTTPS (o link do Pages).
