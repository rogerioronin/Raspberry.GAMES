**Batocera Raspberry Pi 3B Plus**

**OBJETIVO**:
Adicionar e implementar atualizações (upgrade e downgrade) de emuladores especificamente presente na imagem "Batocera 30" para Raspberry Pi 3B (deve servir na versão 3B+).

**BATOCERA 30**:
Uso a versão do Batocera 30 para Raspberry Pi 3B porque segundo meus testes esta versão possui um ótimo desempenho (meus testes foram feitos em meados de 10/03/2022) e possui a vantagem de poder ser executado apartir de um Pendrive.

**IMPORTANTE**:
Não possuo conhecimento em programação, isso acarreta no problema de que algumas implementações que eu acho importante, não será possível sem ajuda.

**SEJA UM COLABORADOR**:
Você possui conhecimento e deseja ajudar no projeto, mande um e-mail para "rogerioronin@hotmail.com".

---------------------------------------------------------------------------------------------------------------------------------------------------------

**ATUALIZAÇÔES PRESENTES NA REVISÃO 0.1**

**Libretro (Retroarch)**:

Eu atualizei alguns núcleos usando como base o Lakka v4.1 (Retroarch 1.10.1), ou ao menos acho eu que atualizei, digo isso porque eu substitui os seguintes núcleos:

- **blueMSX** (bluemsx_libretro.so)
- **DOsbox Pure** (dosbox_pure_libretro.so)
- **FCEUmm** (fceumm_libretro.so)
- **Flycast** (flycast_libretro.so) 
OBSERVAÇÂO: Na atualização do emulador Flycast usei o núcleo presente no Batocera versão 31, pois o presente na ultima versão do Lakka não funcionou.
- **Gambatte** (gambatte_libretro.so)
- **Genesis Plus GX** (genesisplusgx_libretro.so)
- **mGBA** (mgba_libretro.so)
- **Mr.Boom** (mrboom_libretro.so)
- **Nestopia** (nestopia_libretro.so)
- **Neko Project II Kai** (np2kai_libretro.so)
- **PCE Fast** (pce_fast_libretro.so)
- **PCSX ReARMed** (pcsx_rearmed_libretro.so)
- **PicoDrive** (picodrive_libretro.so)
- **PrBoom** (prboom_libretro.so)
- **QUASI88** (quasi88_libretro.so)
- **Snes9x** (snes9x_libretro.so)
- **Stella** (stella_libretro.so)
- **TGB Dual** (tgbdual_libretro.so)

que estavam em "**usr/lib/libretro**", no entanto, apesar de eu ter atualizado todos os núcleos indicados, se você conferir a versão do Retroarch que indica, por algum motivo vai marcar versão 1.9.0, que é a versão original do Batocera 30, resumindo apesar de eu atualizar (ou ao menos acho que atualizei), não consigo fazer mostrar a versão real do Retroarch.


**DevilutionX**:
Atualizado DevilutionX (Diablo + Hellfire) to 1.3.0.


**Drastic**:
Adicionado o Drastic versão r2.5.0.4 com suporte a jogos compactados em .7zip e .zip.

OBSERVAÇÂO: Eu uso um controle de Playstation 3, então consequentemente o "Drastic" esta configurado para suportar cntrole de Playsatation 3, se você usa um controle diferente, configure conforme seu gosto (existe alguns tutoriais na internet explicando como configurar "controle no drastc").

**PPSSPP**:
Fiz o downgrade do PPSSPP para a versão 1.5.4, pois nos meus testes essa foi a versão que melhor funcionou no Batocera compativel com Raspberry Pi 3b.

---------------------------------------------------------------------------------------------------------------------------------------------------------

**Batocera RPI 3b versão 30 revisão 0.2**

**BAIXE AQUI** https://bityli.com/PSNQE
