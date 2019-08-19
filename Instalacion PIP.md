## Instalacion PIP para Mac

Primero abrimos la terminal.
 
```
Last login: [Dia - hora] on ttys000  
[Nombre del equipo]:~ [Nombre del usuario]$  
```

Comenzaremos la instalacion de PIP mediante el metodo de instalacion sencilla con el comando:
 
```
$ sudo easy_install pip  

```
Por seguridad nos pedira nuestra contraseña para empezar la instalacion.  
<mark>La contraseña no sera visible por seguridad</mark>   

```
Password:[colocar contraseña]

```
Una vez colocada la contaseña empezara la instalacion.

```
Searching for pip
Best match: pip 18.1
Adding pip 18.1 to easy-install.pth file
Installing pip script to /Library/Frameworks/Python.framework/Versions/2.7/bin
Installing pip3.7 script to /Library/Frameworks/Python.framework/Versions/2.7/bin
Installing pip3 script to /Library/Frameworks/Python.framework/Versions/2.7/bin

Using /Library/Frameworks/Python.framework/Versions/2.7/lib/python2.7/site-packages
Processing dependencies for pip
Finished processing dependencies for pip
```
Despues se usar el comando se empezara la actualización a la ultima version

```
*$ sudo pip install --upgrade pip
```  

```
The directory '/Users/[Nombre del usuario]/Library/Caches/pip/http' or its parent directory is not owned by the current user and the cache has been disabled. Please check the permissions and owner of that directory. If executing pip with sudo, you may want sudo's -H flag.  
The directory '/Users/[Nombre del usuario]/Library/Caches/pip' or its parent directory is not owned by the current user and caching wheels has been disabled. check the permissions and owner of that directory. If executing pip with sudo, you may want sudo's -H flag.  
Collecting pip  
	Downloading https://files.pythonhosted.org/packages/8d/07/f7d7ced2f97ca3098c16565efbe6b15fafcba53e8d9bdb431e09140514b0/pip-19.2.2-py2.py3-none-any.whl (1.4MB)
   	 100% |████████████████████████████████| 1.4MB 14.8MB/s 
Installing collected packages: pip
  Found existing installation: pip 18.1
    Uninstalling pip-18.1:
      Successfully uninstalled pip-18.1
Successfully installed pip-19.2.2
```









