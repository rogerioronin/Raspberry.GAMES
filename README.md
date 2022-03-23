**Batocera Raspberry Pi 3B Plus**

**OBJETIVO**:
Adicionar e implementar atualizações (upgrade e downgrade) de emuladores especificamente presente na imagem "Batocera 29" para Raspberry Pi 3B (deve servir na versão 3B+).

**BATOCERA 29**:
Uso a versão do Batocera 29 para Raspberry Pi 3B porque segundo meus testes foi a versão com melhor desempenho (meus testes foram feitos em meados de 10/03/2022).

**IMPORTANTE**:
Não possuo conhecimento em programação, isso acarreta no problema de que algumas implementações que eu acho importante, não será possível sem ajuda.

**SEJA UM COLABORADOR**:
Você possui conhecimento e deseja ajudar no projeto, mande um e-mail para "rogerioronin@hotmail.com".

-----------------------------------------------------------------------------------------------------------------------------------------------------------

**ATUALIZAÇÔES PRESENTES NA REVISÃO 0.1**

**LIBRETRO / RETROARCH**:
Eu atualizei estes núcleos usando como base o Lakka v4.0 (Retroarch 1.10.1), ou ao menos acho eu que atualizei, digo isso porque eu substitui os núcleos que estavam em "usr/lib/libretro", porem apesar de eu ter atualizado todos os núcleos se você abrir um jogo e conferir a versão do Retroarch, por algum motivo vai marcar a versão 1.9.0, que é a versão original do Batocera 29, resumindo apesar de eu atualizar (ou ao menos acho que atualizei), não consigo fazer mostrar a versão real do Retroarch.
OBSERVAÇÃO: Eu tenho quase certeza que atualizei o Retroarch pois fiz o seguinte teste, peguei o nucleo "duckstation_libretro.so" e renomeei para "pcsx_rearmed_libretro.so" e substitui o mesmo presente no Batocera 29 e o núcleo iniciado no Batocera 29 depois da substituião foi o "duckstation_libretro.so". Depois deste deste supus que apesar dos núcleos marcarem a versão 1.9.0 eles estão atualizados para a versão "1.10.1".
