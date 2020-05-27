## Dell Inspiron 5447

![Screenshot](https://github.com/marcello0201/Dell-5447-Hackintosh-Catalina-10.15.5/blob/master/Bios%20setings/MacOS.png)

- Bios versão :  A12
- Processador: Intel Core i7 4510U @2.00 GHz
- Placa de Video : Intel HD  Graphics 4400
- Memoria: 16GB DDR3L 1600 Mhz
- Disco: SSD 1TB SanDisk
- Clover Versão: Clover_r5107 
- Sistema:  MacOS Catalina 10.15.5 (19F96)

## Suportado:

- Video / HDMI / Brilho da Tela
- Webcan
- Audio / Microfone / Fones de ouvido
- Teclado / Touchpad 
- Bateria
- USB 3.0 / 2.0
- LAN

## Não suportado:

- Wifi e bluetooth: Atheros AR9565
    - Troque essa placa pela  DELL DW 1560
- Placa de Video: Radeon r7 M265 (Desativado via SSDT) 
- Leitor de cartão SD: RTS5179 (Desativado  via SSDT para economizar energia) 
- Elan USB TouchScreen

Como instalar as kexts veja em : 

English notes ? see : 

-------------------
## Notas dessa versão:
- Aumento da Vram  de 1536MB para 2048MB.
- Jack fix_v2 - automaticamente fecha o terminal na inicialização.
- Ativação do repouso após fechar a tampa e acorda automaticamente ao abrir.
- Ativação das portasUSB via SSDT.
