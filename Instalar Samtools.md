## Instalar Samtools
Con la linea de comando  

```
conda install -c bioconda samtools
```  
Nos mostrara lo que se desea instalar y actualizar  

```
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /Users/carlospartida/miniconda2

  added / updated specs:
    - samtools


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    certifi-2019.6.16          |           py27_1         155 KB
    curl-7.65.2                |       ha441bb4_0         135 KB
    krb5-1.16.1                |       hddcf347_7         1.0 MB
    libcurl-7.65.2             |       h051b688_0         539 KB
    libdeflate-1.0             |       h1de35cc_1          45 KB  bioconda
    libssh2-1.8.2              |       ha12b0ac_0         207 KB
    samtools-1.9               |      h7c4ea83_11         575 KB  bioconda
    ------------------------------------------------------------
                                           Total:         2.6 MB

The following NEW packages will be INSTALLED:

  curl               pkgs/main/osx-64::curl-7.65.2-ha441bb4_0
  krb5               pkgs/main/osx-64::krb5-1.16.1-hddcf347_7
  libcurl            pkgs/main/osx-64::libcurl-7.65.2-h051b688_0
  libdeflate         bioconda/osx-64::libdeflate-1.0-h1de35cc_1
  libssh2            pkgs/main/osx-64::libssh2-1.8.2-ha12b0ac_0
  samtools           bioconda/osx-64::samtools-1.9-h7c4ea83_11

The following packages will be UPDATED:

  openssl            conda-forge::openssl-1.1.1c-h01d97ff_0 --> pkgs/main::openssl-1.1.1c-h1de35cc_1

The following packages will be SUPERSEDED by a higher-priority channel:

  certifi                                       conda-forge --> pkgs/main
  
```  
Despues nos preguntara si queremos proceder con la instalación   

```
Proceed ([y]/n)?
```
 
Le damos Y por lo cual procedera a la instalación de los paquetes asi mismo com algunas actualizaciones de estos 

```
Downloading and Extracting Packages
samtools-1.9         | 575 KB    | ##################################### | 100% 
krb5-1.16.1          | 1.0 MB    | ##################################### | 100% 
libdeflate-1.0       | 45 KB     | ##################################### | 100% 
certifi-2019.6.16    | 155 KB    | ##################################### | 100% 
curl-7.65.2          | 135 KB    | ##################################### | 100% 
libcurl-7.65.2       | 539 KB    | ##################################### | 100% 
libssh2-1.8.2        | 207 KB    | ##################################### | 100% 
Preparing transaction: done
Verifying transaction: done
Executing transaction: done
```