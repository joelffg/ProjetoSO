# Rádio Frequência

### Aparelho utilizado

ACS1222L-D1 USB NFC Reader with LCD (goo.gl/mVZkY8)

### Instalação do driver

1. Logue como superuser. (sudo su)

2. Para compilar o driver são necessaŕios os seguintes pacotes:
	
-> pcsclite 1.8.3 ou superior
```
# apt-get install libpcsclite-dev
```

-> libusb 1.0.9 ou superior
```
# apt-get install libusb-1.0-0-dev
```

-> flex
```
# apt-get install flex
```

-> perl
```
# apt-get install perl
```

-> pkg-config
```
# apt-get install pkg-config
```

3. Na pasta com o arquivo compactador:
```
# tar -jxvf acsccid-x.y.z.tar.bz2
# cd acsccid-x.y.z
# ./configure
# make
# make install
```

### Antes de usar
1. Login como root.
```
$ sudo su
```

2. Entre na pasta "ctacs_linux_bin-1.0.1" e execute
```
# ./install.sh
```

### Autores:
* Joel Felipe - joelfelipe07@gmail.com
* Hugo Oliveira - hugotholiveira@hotmail.com

### Referências:
* http://www.pudn.com/Download/item/id/417462.html
* https://github.com/acshk/acsccid
* https://stackoverflow.com/questions/27800295/programming-acr122t-e2-in-linux
* https://manned.org/CT_init#head4
* https://github.com/larskanis/ctapi-cyberjack
* http://www.acs.com.hk/download-manual/2737/API-ACR1222L-1.03.pdf
* http://manpages.ubuntu.com/manpages/zesty/man3/towitoko-ctbcs.3.html

### Disponível em: 
https://github.com/joelffg/ProjetoSO/tree/master/Trabalho%20Final
