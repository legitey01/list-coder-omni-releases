# List Coder Omni

<p align="center">
  <img src="https://raw.githubusercontent.com/legitey01/List-Coder-Omni/dev/packages/desktop/resources/icons/icon.png" width="120" alt="List Coder Omni Logo"/>
</p>

<h3 align="center">O IDE que entende você.</h3>

<p align="center">
  <a href="https://list-coder.com">Website</a> • 
  <a href="https://github.com/legitey01/List-Coder-Omni">GitHub</a> • 
  <a href="https://discord.gg/listcoder">Discord</a>
</p>

---

## O que é o List Coder Omni?

O **List Coder Omni** é um IDE desktop inteligente, feito para desenvolvedores que querem produtividade sem complicação. Com IA integrada, terminal embutido, multi-abas e suporte nativo a múltiplos provedores de IA — tudo em um app rápido e bonito.

### Features

- **IA Integrada** — Chat, autocomplete e agentes com os melhores modelos (GPT, Claude, Gemini, Grok, entre outros)
- **Multi-Provedor** — Conecte seu provider favorito: OpenAI, Anthropic, Google, xAI, OpenRouter, Groq, e mais
- **Terminal Embutido** — Execute comandos sem sair do editor
- **Multi-Abas** — Trabalhe em vários arquivos ao mesmo tempo
- **Extensões** — Use MCP servers para expandir as capacidades
- **Auto-Update** — Sempre atualizado com as últimas melhorias
- **Multi-Plataforma** — Windows, macOS e Linux

---

## Download

| Plataforma | Arquivo | Tamanho |
|------------|---------|---------|
| Windows (x64) | [Installer (.exe)](https://github.com/legitey01/list-coder-omni-releases/releases/latest/download/list-coder-omni-desktop-win-x64.exe) | ~120 MB |
| Windows (x64) | [MSIX (.appx)](https://github.com/legitey01/list-coder-omni-releases/releases/latest/download/list-coder-omni-desktop-win-x64.appx) | ~170 MB |

---

## Screenshots

<p align="center">
  <img src="https://raw.githubusercontent.com/legitey01/List-Coder-Omni/dev/screenshots/screenshot-1.png" width="800" alt="List Coder Omni Screenshot"/>
</p>

---

## Como funciona o Auto-Update

O List Coder Omni verifica automaticamente novas versões a cada inicialização. O arquivo `latest-omni.yml` contém as informações da versão mais recente e é atualizado a cada release.

### Para desenvolvedores

Se você quer contribuir ou criar suas próprias builds:

```bash
# Clonar o repositório
git clone https://github.com/legitey01/List-Coder-Omni.git
cd List-Coder-Omni

# Instalar dependências
bun install

# Build do app
cd packages/desktop
bun run build
npx electron-builder --win --x64 --publish never --config electron-builder.config.ts
```

---

## Links

- **Website:** [list-coder.com](https://list-coder.com)
- **Documentação:** [list-coder.com/docs](https://list-coder.com/docs)
- **Discord:** [discord.gg/listcoder](https://discord.gg/listcoder)
- **Twitter:** [@listcoder](https://twitter.com/listcoder)

---

## Licença

© 2026 List Coder Omni. Todos os direitos reservados.
