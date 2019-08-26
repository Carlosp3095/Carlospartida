## Instalar CUTADAPT
Con la linea de comando  

```
conda install -c bioconda cutadapt
```  
Nos mostrara lo que se desea instal y actualizar  

```
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /Users/carlospartida/miniconda2

  added / updated specs:
    - cutadapt


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    bz2file-0.98               |           py27_1          13 KB
    ca-certificates-2019.5.15  |                1         133 KB
    certifi-2019.6.16          |           py27_1         155 KB
    conda-4.7.11               |           py27_0         3.0 MB
    cutadapt-1.18              |   py27h1de35cc_1         176 KB  bioconda
    pigz-2.4                   |       ha441bb4_0          57 KB
    xopen-0.7.3                |             py_0          11 KB  bioconda
    ------------------------------------------------------------
                                           Total:         3.5 MB

The following NEW packages will be INSTALLED:

  bz2file            pkgs/main/osx-64::bz2file-0.98-py27_1
  cutadapt           bioconda/osx-64::cutadapt-1.18-py27h1de35cc_1
  pigz               pkgs/main/osx-64::pigz-2.4-ha441bb4_0
  xopen              bioconda/noarch::xopen-0.7.3-py_0

The following packages will be UPDATED:

  ca-certificates                               2019.5.15-0 --> 2019.5.15-1
  certifi                                  2019.6.16-py27_0 --> 2019.6.16-py27_1
  conda                                       4.7.10-py27_0 --> 4.7.11-py27_0



```  
Despues nos preguntara si queremos proceder con la instalación   

```
Proceed ([y]/n)?
```
 
Le damos Y por lo cual procedera a la instalación de los paquetes asi mismo com algunas actualizaciones de estos 

```
Downloading and Extracting Packages
conda-4.7.11         | 3.0 MB    | ##################################### | 100% 
certifi-2019.6.16    | 155 KB    | ##################################### | 100% 
xopen-0.7.3          | 11 KB     | ##################################### | 100% 
bz2file-0.98         | 13 KB     | ##################################### | 100% 
pigz-2.4             | 57 KB     | ##################################### | 100% 
ca-certificates-2019 | 133 KB    | ##################################### | 100% 
cutadapt-1.18        | 176 KB    | ##################################### | 100% 
Preparing transaction: done
Verifying transaction: done
Executing transaction: done
```