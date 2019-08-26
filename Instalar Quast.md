## Instalar Quast
Con la linea de comando  

```
conda install -c bioconda quast
```  
Nos mostrara lo que se desea instalar y actualizar  

```
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /Users/carlospartida/miniconda2

  added / updated specs:
    - quast


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    backports-1.0              |             py_2         139 KB
    backports.functools_lru_cache-1.5|             py_2           9 KB
    backports_abc-0.5          |   py27h6972548_0          12 KB
    blas-1.0                   |              mkl           6 KB
    blast-2.6.0                |      boost1.64_2       113.0 MB  bioconda
    circos-0.69.8              |                0        26.3 MB  bioconda
    cycler-0.10.0              |   py27hfc73c78_0          13 KB
    expat-2.2.6                |       h0a44026_0         111 KB
    functools32-3.2.3.2        |           py27_1          23 KB
    giflib-5.1.4               |       h1de35cc_1          59 KB
    glimmerhmm-3.0.4           |  pl526h0a44026_3        40.5 MB  bioconda
    intel-openmp-2019.4        |              233         887 KB
    joblib-0.13.2              |           py27_0         341 KB
    jpeg-9b                    |       he5867d9_2         201 KB
    kiwisolver-1.1.0           |   py27h0a44026_0          54 KB
    libgd-2.2.5                |       h527e5b3_3         194 KB
    libtiff-4.0.10             |       hcb84e12_2         394 KB
    libwebp-1.0.1              |       hd73b212_0         431 KB
    matplotlib-2.2.3           |   py27h54f8f79_0         4.7 MB
    mkl-2019.4                 |              233       101.9 MB
    mkl-service-2.0.2          |   py27h1de35cc_0          46 KB
    mkl_fft-1.0.14             |   py27h5e564d8_0         156 KB
    mkl_random-1.0.2           |   py27h27c97d8_0         318 KB
    numpy-1.16.4               |   py27hacdab7b_0          48 KB
    numpy-base-1.16.4          |   py27h6575580_0         3.3 MB
    perl-autoloader-5.74       |          pl526_2           4 KB  bioconda
    perl-carp-1.38             |          pl526_3          15 KB  bioconda
    perl-clone-0.42            |  pl526h01d97ff_0          12 KB  bioconda
    perl-config-general-2.63   |          pl526_0          41 KB  bioconda
    perl-digest-perl-md5-1.9   |          pl526_1          11 KB  bioconda
    perl-dynaloader-1.25       |          pl526_1           4 KB  bioconda
    perl-exporter-5.72         |          pl526_1          13 KB  bioconda
    perl-exporter-tiny-1.002001|          pl526_0          23 KB  bioconda
    perl-extutils-makemaker-7.36|          pl526_1         153 KB  bioconda
    perl-font-ttf-1.06         |          pl526_0         200 KB  bioconda
    perl-gd-2.71               |  pl526h5c9b4e4_0         106 KB  bioconda
    perl-io-string-1.08        |          pl526_3          10 KB  bioconda
    perl-list-moreutils-0.428  |          pl526_1          28 KB  bioconda
    perl-list-moreutils-xs-0.428|          pl526_0          40 KB  bioconda
    perl-math-bezier-0.01      |          pl526_1           8 KB  bioconda
    perl-math-round-0.07       |          pl526_1           9 KB  bioconda
    perl-math-vecstat-0.08     |          pl526_1           9 KB  bioconda
    perl-module-implementation-0.09|          pl526_2           9 KB  bioconda
    perl-module-runtime-0.016  |          pl526_1          15 KB  bioconda
    perl-number-format-1.75    |          pl526_3          20 KB  bioconda
    perl-params-validate-1.29  |  pl526h1de35cc_1          25 KB  bioconda
    perl-pathtools-3.75        |  pl526h1de35cc_1          39 KB  bioconda
    perl-readonly-2.05         |          pl526_0          17 KB  bioconda
    perl-regexp-common-2017060201|          pl526_0          93 KB  bioconda
    perl-scalar-list-utils-1.52|  pl526h01d97ff_0          35 KB  bioconda
    perl-set-intspan-1.19      |          pl526_1          22 KB  bioconda
    perl-statistics-basic-1.6611|                0          27 KB  bioconda
    perl-svg-2.84              |          pl526_0          37 KB  bioconda
    perl-text-format-0.59      |          pl526_2          15 KB  bioconda
    perl-threaded-5.26.0       |                0           4 KB  bioconda
    perl-time-hires-1.9760     |  pl526h1de35cc_1          22 KB  bioconda
    perl-try-tiny-0.30         |          pl526_1          16 KB  bioconda
    perl-xml-parser-2.44       |  pl526h776b7f1_7         162 KB  bioconda
    perl-xsloader-0.24         |          pl526_0           8 KB  bioconda
    pyparsing-2.4.2            |             py_0          61 KB
    python-dateutil-2.8.0      |           py27_0         265 KB
    pytz-2019.2                |             py_0         245 KB
    quast-5.0.2                |py27pl526ha441bb4_1        17.8 MB  bioconda
    simplejson-3.8.1           |           py27_0          81 KB  bioconda
    singledispatch-3.4.0.3     |   py27he22c18d_0          15 KB
    subprocess32-3.5.4         |   py27h1de35cc_0          50 KB
    tornado-5.1.1              |   py27h1de35cc_0         613 KB
    ------------------------------------------------------------
                                           Total:       313.4 MB

The following NEW packages will be INSTALLED:

  backports          pkgs/main/noarch::backports-1.0-py_2
  backports.functoo~ pkgs/main/noarch::backports.functools_lru_cache-1.5-py_2
  backports_abc      pkgs/main/osx-64::backports_abc-0.5-py27h6972548_0
  blas               pkgs/main/osx-64::blas-1.0-mkl
  blast              bioconda/osx-64::blast-2.6.0-boost1.64_2
  circos             bioconda/noarch::circos-0.69.8-0
  cycler             pkgs/main/osx-64::cycler-0.10.0-py27hfc73c78_0
  expat              pkgs/main/osx-64::expat-2.2.6-h0a44026_0
  functools32        pkgs/main/osx-64::functools32-3.2.3.2-py27_1
  giflib             pkgs/main/osx-64::giflib-5.1.4-h1de35cc_1
  glimmerhmm         bioconda/osx-64::glimmerhmm-3.0.4-pl526h0a44026_3
  intel-openmp       pkgs/main/osx-64::intel-openmp-2019.4-233
  joblib             pkgs/main/osx-64::joblib-0.13.2-py27_0
  jpeg               pkgs/main/osx-64::jpeg-9b-he5867d9_2
  kiwisolver         pkgs/main/osx-64::kiwisolver-1.1.0-py27h0a44026_0
  libgd              pkgs/main/osx-64::libgd-2.2.5-h527e5b3_3
  libtiff            pkgs/main/osx-64::libtiff-4.0.10-hcb84e12_2
  libwebp            pkgs/main/osx-64::libwebp-1.0.1-hd73b212_0
  matplotlib         pkgs/main/osx-64::matplotlib-2.2.3-py27h54f8f79_0
  mkl                pkgs/main/osx-64::mkl-2019.4-233
  mkl-service        pkgs/main/osx-64::mkl-service-2.0.2-py27h1de35cc_0
  mkl_fft            pkgs/main/osx-64::mkl_fft-1.0.14-py27h5e564d8_0
  mkl_random         pkgs/main/osx-64::mkl_random-1.0.2-py27h27c97d8_0
  numpy              pkgs/main/osx-64::numpy-1.16.4-py27hacdab7b_0
  numpy-base         pkgs/main/osx-64::numpy-base-1.16.4-py27h6575580_0
  perl-autoloader    bioconda/osx-64::perl-autoloader-5.74-pl526_2
  perl-carp          bioconda/osx-64::perl-carp-1.38-pl526_3
  perl-clone         bioconda/osx-64::perl-clone-0.42-pl526h01d97ff_0
  perl-config-gener~ bioconda/osx-64::perl-config-general-2.63-pl526_0
  perl-digest-perl-~ bioconda/osx-64::perl-digest-perl-md5-1.9-pl526_1
  perl-dynaloader    bioconda/osx-64::perl-dynaloader-1.25-pl526_1
  perl-exporter      bioconda/osx-64::perl-exporter-5.72-pl526_1
  perl-exporter-tiny bioconda/osx-64::perl-exporter-tiny-1.002001-pl526_0
  perl-extutils-mak~ bioconda/osx-64::perl-extutils-makemaker-7.36-pl526_1
  perl-font-ttf      bioconda/osx-64::perl-font-ttf-1.06-pl526_0
  perl-gd            bioconda/osx-64::perl-gd-2.71-pl526h5c9b4e4_0
  perl-io-string     bioconda/osx-64::perl-io-string-1.08-pl526_3
  perl-list-moreuti~ bioconda/osx-64::perl-list-moreutils-0.428-pl526_1
  perl-list-moreuti~ bioconda/osx-64::perl-list-moreutils-xs-0.428-pl526_0
  perl-math-bezier   bioconda/osx-64::perl-math-bezier-0.01-pl526_1
  perl-math-round    bioconda/osx-64::perl-math-round-0.07-pl526_1
  perl-math-vecstat  bioconda/osx-64::perl-math-vecstat-0.08-pl526_1
  perl-module-imple~ bioconda/osx-64::perl-module-implementation-0.09-pl526_2
  perl-module-runti~ bioconda/osx-64::perl-module-runtime-0.016-pl526_1
  perl-number-format bioconda/osx-64::perl-number-format-1.75-pl526_3
  perl-params-valid~ bioconda/osx-64::perl-params-validate-1.29-pl526h1de35cc_1
  perl-pathtools     bioconda/osx-64::perl-pathtools-3.75-pl526h1de35cc_1
  perl-readonly      bioconda/osx-64::perl-readonly-2.05-pl526_0
  perl-regexp-common bioconda/osx-64::perl-regexp-common-2017060201-pl526_0
  perl-scalar-list-~ bioconda/osx-64::perl-scalar-list-utils-1.52-pl526h01d97ff_0
  perl-set-intspan   bioconda/osx-64::perl-set-intspan-1.19-pl526_1
  perl-statistics-b~ bioconda/osx-64::perl-statistics-basic-1.6611-0
  perl-svg           bioconda/osx-64::perl-svg-2.84-pl526_0
  perl-text-format   bioconda/osx-64::perl-text-format-0.59-pl526_2
  perl-threaded      bioconda/osx-64::perl-threaded-5.26.0-0
  perl-time-hires    bioconda/osx-64::perl-time-hires-1.9760-pl526h1de35cc_1
  perl-try-tiny      bioconda/osx-64::perl-try-tiny-0.30-pl526_1
  perl-xml-parser    bioconda/osx-64::perl-xml-parser-2.44-pl526h776b7f1_7
  perl-xsloader      bioconda/osx-64::perl-xsloader-0.24-pl526_0
  pyparsing          pkgs/main/noarch::pyparsing-2.4.2-py_0
  python-dateutil    pkgs/main/osx-64::python-dateutil-2.8.0-py27_0
  pytz               pkgs/main/noarch::pytz-2019.2-py_0
  quast              bioconda/osx-64::quast-5.0.2-py27pl526ha441bb4_1
  simplejson         bioconda/osx-64::simplejson-3.8.1-py27_0
  singledispatch     pkgs/main/osx-64::singledispatch-3.4.0.3-py27he22c18d_0
  subprocess32       pkgs/main/osx-64::subprocess32-3.5.4-py27h1de35cc_0
  tornado            pkgs/main/osx-64::tornado-5.1.1-py27h1de35cc_0
  
```  
Despues nos preguntara si queremos proceder con la instalación   

```
Proceed ([y]/n)?
```
 
Le damos Y por lo cual procedera a la instalación de los paquetes asi mismo com algunas actualizaciones de estos 

```
Downloading and Extracting Packages
perl-try-tiny-0.30   | 16 KB     | ##################################### | 100% 
numpy-1.16.4         | 48 KB     | ##################################### | 100% 
perl-regexp-common-2 | 93 KB     | ##################################### | 100% 
perl-exporter-5.72   | 13 KB     | ##################################### | 100% 
perl-time-hires-1.97 | 22 KB     | ##################################### | 100% 
pytz-2019.2          | 245 KB    | ##################################### | 100% 
python-dateutil-2.8. | 265 KB    | ##################################### | 100% 
matplotlib-2.2.3     | 4.7 MB    | ##################################### | 100% 
intel-openmp-2019.4  | 887 KB    | ##################################### | 100% 
quast-5.0.2          | 17.8 MB   | ##################################### | 100% 
perl-number-format-1 | 20 KB     | ##################################### | 100% 
perl-xsloader-0.24   | 8 KB      | ##################################### | 100% 
circos-0.69.8        | 26.3 MB   | ##################################### | 100% 
perl-scalar-list-uti | 35 KB     | ##################################### | 100% 
perl-list-moreutils- | 28 KB     | ##################################### | 100% 
perl-autoloader-5.74 | 4 KB      | ##################################### | 100% 
perl-list-moreutils- | 40 KB     | ##################################### | 100% 
perl-math-round-0.07 | 9 KB      | ##################################### | 100% 
backports.functools_ | 9 KB      | ##################################### | 100% 
perl-exporter-tiny-1 | 23 KB     | ##################################### | 100% 
perl-dynaloader-1.25 | 4 KB      | ##################################### | 100% 
perl-readonly-2.05   | 17 KB     | ##################################### | 100% 
glimmerhmm-3.0.4     | 40.5 MB   | ##################################### | 100% 
perl-text-format-0.5 | 15 KB     | ##################################### | 100% 
functools32-3.2.3.2  | 23 KB     | ##################################### | 100% 
libtiff-4.0.10       | 394 KB    | ##################################### | 100% 
perl-clone-0.42      | 12 KB     | ##################################### | 100% 
perl-config-general- | 41 KB     | ##################################### | 100% 
perl-module-runtime- | 15 KB     | ##################################### | 100% 
mkl-2019.4           | 101.9 MB  | ##################################### | 100% 
libwebp-1.0.1        | 431 KB    | ##################################### | 100% 
perl-xml-parser-2.44 | 162 KB    | ##################################### | 100% 
backports-1.0        | 139 KB    | ##################################### | 100% 
perl-font-ttf-1.06   | 200 KB    | ##################################### | 100% 
numpy-base-1.16.4    | 3.3 MB    | ##################################### | 100% 
perl-digest-perl-md5 | 11 KB     | ##################################### | 100% 
perl-math-vecstat-0. | 9 KB      | ##################################### | 100% 
mkl_fft-1.0.14       | 156 KB    | ##################################### | 100% 
perl-set-intspan-1.1 | 22 KB     | ##################################### | 100% 
perl-io-string-1.08  | 10 KB     | ##################################### | 100% 
perl-svg-2.84        | 37 KB     | ##################################### | 100% 
mkl-service-2.0.2    | 46 KB     | ##################################### | 100% 
expat-2.2.6          | 111 KB    | ##################################### | 100% 
cycler-0.10.0        | 13 KB     | ##################################### | 100% 
mkl_random-1.0.2     | 318 KB    | ##################################### | 100% 
kiwisolver-1.1.0     | 54 KB     | ##################################### | 100% 
blast-2.6.0          | 113.0 MB  | ##################################### | 100% 
perl-statistics-basi | 27 KB     | ##################################### | 100% 
perl-gd-2.71         | 106 KB    | ##################################### | 100% 
perl-threaded-5.26.0 | 4 KB      | ##################################### | 100% 
perl-carp-1.38       | 15 KB     | ##################################### | 100% 
backports_abc-0.5    | 12 KB     | ##################################### | 100% 
perl-pathtools-3.75  | 39 KB     | ##################################### | 100% 
perl-module-implemen | 9 KB      | ##################################### | 100% 
perl-params-validate | 25 KB     | ##################################### | 100% 
subprocess32-3.5.4   | 50 KB     | ##################################### | 100% 
simplejson-3.8.1     | 81 KB     | ##################################### | 100% 
giflib-5.1.4         | 59 KB     | ##################################### | 100% 
tornado-5.1.1        | 613 KB    | ##################################### | 100% 
perl-extutils-makema | 153 KB    | ##################################### | 100% 
libgd-2.2.5          | 194 KB    | ##################################### | 100% 
blas-1.0             | 6 KB      | ##################################### | 100% 
pyparsing-2.4.2      | 61 KB     | ##################################### | 100% 
singledispatch-3.4.0 | 15 KB     | ##################################### | 100% 
jpeg-9b              | 201 KB    | ##################################### | 100% 
perl-math-bezier-0.0 | 8 KB      | ##################################### | 100% 
joblib-0.13.2        | 341 KB    | ##################################### | 100% 
Preparing transaction: done
Verifying transaction: done
Executing transaction: \ The default QUAST package does not include:
* GRIDSS (needed for structural variants detection)
* SILVA 16S rRNA database (needed for reference genome detection in metagenomic datasets)
* BUSCO tools and databases (needed for searching BUSCO genes) -- works in Linux only!

To be able to use those, please run
    quast-download-gridss
    quast-download-silva
    quast-download-busco

done
```