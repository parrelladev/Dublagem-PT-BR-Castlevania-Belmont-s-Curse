# Castlevania Belmont's Curse — voz PT-BR (0.2.4-preview)

Este mod acrescenta áudio PT-BR para 789 identificadores de fala de `Dialog_en_GB` e substitui a trilha de voz da cinematic de abertura CT01. Os bancos de áudio do jogo permanecem originais.

## Requisitos

- Jogo instalado no build compatível indicado abaixo.
- BepInEx 6 para IL2CPP instalado separadamente e configurado para este jogo. Este arquivo não inclui o carregador, o runtime .NET nem bibliotecas do BepInEx.

## Instalação

1. Feche o jogo.
2. Extraia o conteúdo deste arquivo ZIP na pasta que contém `Castlevania Belmont's Curse.exe`, mesclando a pasta `BepInEx` existente.
3. Abra o jogo e selecione **Português (Brasil)** como idioma de voz.
4. Para voltar ao inglês, selecione **English**.

O plugin cria sua configuração padrão automaticamente. Não é necessário copiar um arquivo de configuração.

## Compatibilidade e cobertura

O plugin só é ativado quando o SHA-256 de `GameAssembly.dll` é `56212abb69646214fecc2385460e94a72c6a0e8ddf03ccecd9ac5228e22cf3d5`. Em outro build, as substituições ficam desativadas.

Há 789 falas de `Dialog_en_GB` com WAVs PT-BR. IDs sem substituição continuam usando o áudio original. Voicelines, amostras Master e outras cinematics permanecem originais. A cinematic CT01 usa a master WAV PT-BR sincronizada, estéreo, 48 kHz/24-bit, com 185,033 s.

Os bancos originais não são distribuídos nem modificados. A mixagem da CT01 usa a mix japonesa como base, sem stem isolado de música e efeitos; consulte a página do mod para as limitações dessa mix.
