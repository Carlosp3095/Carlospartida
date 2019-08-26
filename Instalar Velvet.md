## Instalar Velvet
Con la linea de comando  

```
conda install -c bioconda velvet 
```  
Nos mostrara lo que se desea instalar y actualizar  

```
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /Users/carlospartida/miniconda2

  added / updated specs:
    - velvet


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    libgcc-4.8.5               |      hdbeacc1_10         250 KB
    libgfortran-3.0.1          |       h93005f0_2         426 KB
    velvet-1.2.10              |                1         224 KB  bioconda
    ------------------------------------------------------------
                                           Total:         901 KB

The following NEW packages will be INSTALLED:

  libgcc             pkgs/main/osx-64::libgcc-4.8.5-hdbeacc1_10
  libgfortran        pkgs/main/osx-64::libgfortran-3.0.1-h93005f0_2
  velvet             bioconda/osx-64::velvet-1.2.10-1
  
```  
Despues nos preguntara si queremos proceder con la instalación   

```
Proceed ([y]/n)?
```
 
Le damos Y por lo cual procedera a la instalación de los paquetes asi mismo com algunas actualizaciones de estos 

```
Downloading and Extracting Packages
velvet-1.2.10        | 224 KB    | ##################################### | 100% 
libgfortran-3.0.1    | 426 KB    | ##################################### | 100% 
libgcc-4.8.5         | 250 KB    | ##################################### | 100% 
Preparing transaction: done
Verifying transaction: done
Executing transaction: done
```