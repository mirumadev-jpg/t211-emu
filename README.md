# T211 Emulator

Frontend Android independente de Master Miruma, criado para reaproveitar o Samsung Galaxy Tab 3 7.0 SM-T211 e explorar jogos retrô em hardware modesto.

**Site do projeto:** <https://mirumadev-jpg.github.io/t211-emu/>

**Autor do frontend e da integração:** Master Miruma

**Plataforma-alvo:** Android 4.4.2/API 19, ARMv7 Cortex-A9 dual-core, Vivante GC1000/OpenGL ES 2.0.

## O projeto

O T211 usa uma aplicação Android própria em Java/JNI e cores libretro. A intenção é oferecer uma experiência mais leve e direcionada ao tablet do que uma interface completa de RetroArch. A página apresenta somente sistemas e cores confirmados no projeto. Compatibilidade e desempenho variam por jogo; o foco atual está na otimização dos cores principais.

## Créditos

Obrigado às equipes e contribuintes que desenvolveram e mantêm o ecossistema libretro e os projetos upstream Genesis Plus GX, PicoDrive, Beetle PCE Fast, gpSP, FB Alpha 2012 e MAME 2003. O frontend, a interface, a integração, a embalagem do app e a identidade visual do T211 são de Master Miruma. Os cores mantêm seus créditos, marcas, avisos e licenças originais.

## Licenciamento e conteúdo distribuído

A licença PolyForm Noncommercial 1.0.0 destina-se somente ao código original do frontend Android do T211 quando esse código for publicado; ela não altera as licenças dos cores e dependências de terceiros. Os termos da licença estão em <https://polyformproject.org/licenses/noncommercial/1.0.0>.

Este primeiro repositório é a apresentação estática do projeto. Ele não distribui APK, bibliotecas `.so` de cores, ROMs, BIOS, chaves de assinatura ou binários de terceiros. A licença do código-fonte desta página não concede direitos sobre a marca, o logo ou os cores upstream.

## GitHub Pages

A página é estática e não requer dependências ou etapa de compilação. O GitHub Pages deve publicar a branch `main`, pasta `/`.
