# Cortex

Editor de vídeo para Windows 10/11 (64 bits), feito do zero: timeline multipista, efeitos na GPU, cor, títulos, legendas automáticas, áudio e exportação em vários formatos.

## Baixar e instalar

1. Abra a pasta **instalador**, clique em **Cortex-Setup-0.4.0.exe** e depois no botão **Download** (ícone de seta, no canto direito).
2. Dê dois cliques no arquivo. Não precisa de permissão de administrador.
3. Se o Windows mostrar "Editor desconhecido" (SmartScreen), clique em **Mais informações → Executar assim mesmo**. O instalador não tem assinatura digital.

Quem já tem a 0.4.0 ou mais nova não precisa baixar de novo: o Cortex se atualiza sozinho.

SHA-256 do instalador: veja `latest.json`.

## Novidades da 0.4.0

- Atualização automática: o app procura versão nova, baixa em segundo plano e instala com um clique (ou sozinho quando você fecha).
- Legendas automáticas estilo CapCut, com a palavra falada em destaque (14 estilos). Roda no seu PC; o modelo de voz é baixado uma vez.
- Baixar vídeos do YouTube, TikTok, Instagram e outros (Ferramentas ou botão ⬇ Link na Mídia).
- 50+ de cada: efeitos, filtros, transições, sobreposições, títulos, stickers e animações.
- 56 fontes no estilo das redes sociais.
- Correção: vídeo em reverso não fica mais com tela preta durante a reprodução.

## Componentes

- Electron / Chromium (MIT e licenças do Chromium).
- FFmpeg, build GPL de [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds) (GNU GPL v3), usado para ler e exportar mídia.
- Fontes livres (SIL Open Font License / Apache), com licenças incluídas no app.
- Reconhecimento de voz: Whisper (MIT) via transformers.js / ONNX Runtime (Apache 2.0 / MIT), modelo baixado do Hugging Face no primeiro uso.
- yt-dlp (Unlicense), baixado do GitHub oficial no primeiro uso do baixador.
