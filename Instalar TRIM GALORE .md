## Instalar TRIM GALORE
Con la linea de comando  

```
conda install -c bioconda trim-galore
```  
Nos mostrara lo que se desea instalar y actualizar  

```
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /Users/carlospartida/miniconda2

  added / updated specs:
    - trim-galore


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    fastqc-0.11.8              |                1         9.6 MB  bioconda
    font-ttf-dejavu-sans-mono-2.37|       h6964260_0         386 KB
    fontconfig-2.13.0          |       h5d5b041_1         202 KB
    freetype-2.9.1             |       hb4e5f40_0         555 KB
    icu-58.2                   |       h4b95b61_1        10.1 MB
    libpng-1.6.37              |       ha441bb4_0         262 KB
    openjdk-8.0.152            |       h393ad39_1        66.9 MB
    perl-5.26.2                |       h4e221da_0         9.5 MB
    trim-galore-0.6.4          |                0          40 KB  bioconda
    ------------------------------------------------------------
                                           Total:        97.5 MB

The following NEW packages will be INSTALLED:

  fastqc             bioconda/osx-64::fastqc-0.11.8-1
  font-ttf-dejavu-s~ pkgs/main/noarch::font-ttf-dejavu-sans-mono-2.37-h6964260_0
  fontconfig         pkgs/main/osx-64::fontconfig-2.13.0-h5d5b041_1
  freetype           pkgs/main/osx-64::freetype-2.9.1-hb4e5f40_0
  icu                pkgs/main/osx-64::icu-58.2-h4b95b61_1
  libpng             pkgs/main/osx-64::libpng-1.6.37-ha441bb4_0
  openjdk            pkgs/main/osx-64::openjdk-8.0.152-h393ad39_1
  perl               pkgs/main/osx-64::perl-5.26.2-h4e221da_0
  trim-galore        bioconda/noarch::trim-galore-0.6.4-0
  
  ```  
Despues nos preguntara si queremos proceder con la instalación   

```
Proceed ([y]/n)?
```
 
Le damos Y por lo cual procedera a la instalación de los paquetes asi mismo com algunas actualizaciones de estos 

```
Downloading and Extracting Packages
libpng-1.6.37        | 262 KB    | ##################################### | 100% 
fastqc-0.11.8        | 9.6 MB    | ##################################### | 100% 
perl-5.26.2          | 9.5 MB    | ##################################### | 100% 
fontconfig-2.13.0    | 202 KB    | ##################################### | 100% 
freetype-2.9.1       | 555 KB    | ##################################### | 100% 
font-ttf-dejavu-sans | 386 KB    | ##################################### | 100% 
openjdk-8.0.152      | 66.9 MB   | ##################################### | 100% 
icu-58.2             | 10.1 MB   | ##################################### | 100% 
trim-galore-0.6.4    | 40 KB     | ##################################### | 100% 
Preparing transaction: done
Verifying transaction: done
Executing transaction: done
```