# Viber RPG

RPG idle de ação para Android (Unity).

**Baixar:** https://vbw1510.github.io/ViberRPG/

## Como publicar uma versão nova
1. No Unity: suba `Version` e `Build` em `GameVersion.cs` (ex.: 0.1.1 / build 2).
2. `ViberRPG → 📱 Gerar APK (lançamento)` — cria a pasta `Builds/Android/site`.
3. Aqui no GitHub: **Releases → Draft a new release** → tag `v0.1.1` → anexe o `ViberRPG.apk` → **Publish release**.
4. Substitua o `version.json` (e o `index.html`) deste repositório pelos da pasta `site`.

O jogo confere o `version.json` ao abrir e avisa quando tem versão nova.
