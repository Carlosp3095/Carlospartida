## Instalacion Biopython para Mac

Primero abrimos la terminal.
 
```
Last login: [Dia - hora] on ttys000  
[Nombre del equipo]:~ [Nombre del usuario]$  
```

Comenzaremos la instalacion impaciente de Biopython mediante el comando:
 
```
$  pip install biopython  

```
Una vez colocado el comando empezara la instalacion 

```
Collecting biopython
  Downloading https://files.pythonhosted.org/packages/5a/da/78133668c51eefd66fc00954d742564f91dee8c909bb82cd9bbf356542aa/biopython-1.74-cp27-cp27m-macosx_10_6_intel.macosx_10_9_intel.macosx_10_9_x86_64.macosx_10_10_intel.macosx_10_10_x86_64.whl (2.3MB)
     |████████████████████████████████| 2.3MB 651kB/s 
Collecting numpy (from biopython)
  Downloading https://files.pythonhosted.org/packages/8f/0b/1a2c21bb69138337dc079841aa4a45e5b2fc7a4260c0907f5254fb08f02e/numpy-1.16.4-cp27-cp27m-macosx_10_6_intel.macosx_10_9_intel.macosx_10_9_x86_64.macosx_10_10_intel.macosx_10_10_x86_64.whl (13.9MB)
     |████████████████████████████████| 13.9MB 3.9MB/s 
Installing collected packages: numpy, biopython
Successfully installed biopython-1.74 numpy-1.16.4
```
Una vez instalado podemos actualizar la version de ser necesario con el comando

```
 pip install --upgrade biopython
```  
En caso de que se halla instalado la version mas nueva se mostrara el mensaje siguiente 

```
Requirement already up-to-date: biopython in /Library/Frameworks/Python.framework/Versions/2.7/lib/python2.7/site-packages (1.74)
Requirement already satisfied, skipping upgrade: numpy in /Library/Frameworks/Python.framework/Versions/2.7/lib/python2.7/site-packages (from biopython) (1.16.4)
[Nombre del equipo]:~ [Nombre del usuario]$ 
```
O sino solo se actulizara sin problema alguno 
