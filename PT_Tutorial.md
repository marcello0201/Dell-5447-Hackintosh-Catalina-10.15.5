## Tutorial para instalar as kexts

- EFI/CLOVER/kexts/Other : Onde fica a maioria das Kexts para funcionar o sistema.

- /Library/Extensions/ : Essas kexts dão suporte ao bluetooth da DW1560.
-  DisplayProductID-5f1: A pasta da suporte ao display do notebook, deve ser colocada inteira no diretorio. 
- /usr/bin : Da suporte ao CodecCommander.kext , corrigindo o audio ALC255. 
- Jack fix_v2 - Repara o chiado do som quando é usado fones de ouvido P2, e deve ser inicializado com o sistema.

## Onde colocar os kext:
- /Library/Extensions/

    * BrcmBluetoothInjector.kext

    * BrcmFirmwareRepo.kext

    * BrcmPatchRAM3.kext

- /System/Library/Displays/Contents/Resources/Overrides 

    * DisplayProductID-5f1

- /usr/bin

    * hda-verb

- Preferências de sistema/ Usuários e grupos/itens de inicio 

    * Jack fix_v2
    
## Problemas com hibernação ?

Neste modelo de notebook, para garantir que a hibernação funcione corretamente no Mac OS, é preciso atualizar um firmware da cpu para grantir que a hibernação funcione corretamnte, seguindo este tutorial você conseguirá realizar a atualização, mas lembrando E POR SUA CONTA E RISCO.

https://github.com/marcello0201/Dell-5547-Hackintosh/tree/master/Management-Engine-Firmware

Bugs comuns veja em: https://github.com/marcello0201/Dell-5447-Hackintosh-Catalina-10.15.5/blob/master/Issues.md

## Configuração da bios

![Screenshot](https://github.com/marcello0201/Dell-5447-Hackintosh-Catalina-10.15.5/blob/master/Bios%20setings/1.png)
![Screenshot](https://github.com/marcello0201/Dell-5447-Hackintosh-Catalina-10.15.5/blob/master/Bios%20setings/2.png)
![Screenshot](https://github.com/marcello0201/Dell-5447-Hackintosh-Catalina-10.15.5/blob/master/Bios%20setings/3.png)
![Screenshot](https://github.com/marcello0201/Dell-5447-Hackintosh-Catalina-10.15.5/blob/master/Bios%20setings/4.jpg)
