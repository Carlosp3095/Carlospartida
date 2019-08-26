## Instalar C-shell (Version de Berkeley)
Con la linea de comando  

```
conda install -c conda-forge tcsh
```  
Nos mostrara lo que se desea instalar y actualizar  

```
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /Users/carlospartida/miniconda2

  added / updated specs:
    - tcsh


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    ca-certificates-2019.6.16  |       hecc5488_0         145 KB  conda-forge
    certifi-2019.6.16          |           py27_1         148 KB  conda-forge
    conda-4.7.11               |           py27_0         3.0 MB  conda-forge
    openssl-1.1.1c             |       h01d97ff_0         1.9 MB  conda-forge
    tcsh-6.20.00               |       hcfe32e1_0         367 KB  conda-forge
    ------------------------------------------------------------
                                           Total:         5.5 MB

The following NEW packages will be INSTALLED:

  tcsh               conda-forge/osx-64::tcsh-6.20.00-hcfe32e1_0

The following packages will be UPDATED:

  ca-certificates    pkgs/main::ca-certificates-2019.5.15-1 --> conda-forge::ca-certificates-2019.6.16-hecc5488_0

The following packages will be SUPERSEDED by a higher-priority channel:

  certifi                                         pkgs/main --> conda-forge
  conda                                           pkgs/main --> conda-forge
  openssl              pkgs/main::openssl-1.1.1c-h1de35cc_1 --> conda-forge::openssl-1.1.1c-h01d97ff_0
  
```  
Despues nos preguntara si queremos proceder con la instalación   

```
Proceed ([y]/n)?
```
 
Le damos Y por lo cual procedera a la instalación de los paquetes asi mismo com algunas actualizaciones de estos 

```
Downloading and Extracting Packages
conda-4.7.11         | 3.0 MB    | ##################################### | 100% 
openssl-1.1.1c       | 1.9 MB    | ##################################### | 100% 
tcsh-6.20.00         | 367 KB    | ##################################### | 100% 
certifi-2019.6.16    | 148 KB    | ##################################### | 100% 
ca-certificates-2019 | 145 KB    | ##################################### | 100% 
Preparing transaction: done
Verifying transaction: done
Executing transaction: done
```