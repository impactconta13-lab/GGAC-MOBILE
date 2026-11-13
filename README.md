# GGAC Mobile

APK Android ARM64 (`arm64-v8a`) do ARK 0.5.1, com runtime C++ e PSPRecomp/Allegrex ligados estaticamente.

A ISO **não** está no APK. No app, toque em **Selecionar ISO** e escolha a sua imagem PSP USA (`ULUS10409`). O app valida o `PARAM.SFO` e extrai `PSP_GAME` para o armazenamento privado.

A extração não recusa mais arquivos acima de 512 MB: cada arquivo da ISO é gravado em partes. A imagem em si continua só no aparelho.

Esta versão extrai os arquivos. O combate ainda não inicia: o módulo retail continua criptografado e não há código de jogo recompilado neste build.

Download: [ARK-GGXX-0.5.1-arm64-static.apk](https://github.com/Pqnocorvo/GGAC-MOBILE/releases/latest)
