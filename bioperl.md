# bioperl

primero ocupamos instalar CPAN el cual nos ayudara a manejar e instalar los modulos Perl, este se instala con el comando 
 
```
cpan App::cpanminus
```  
el cual realizara lo siguientes  

```
Fetching with LWP:
http://cpan.mirrors.ionfish.org/authors/01mailrc.txt.gz
Reading '/Users/carlospartida/.cpan/sources/authors/01mailrc.txt.gz'
............................................................................DONE
Fetching with LWP:
http://cpan.mirrors.ionfish.org/modules/02packages.details.txt.gz
Reading '/Users/carlospartida/.cpan/sources/modules/02packages.details.txt.gz'
  Database was generated on Sun, 25 Aug 2019 20:41:03 GMT
.............
  New CPAN.pm version (v2.27) available.
  [Currently running version is v2.00]
  You might want to try
    install CPAN
    reload cpan
  to both upgrade CPAN.pm and run the new version without leaving
  the current session.


...............................................................DONE
Fetching with LWP:
http://cpan.mirrors.ionfish.org/modules/03modlist.data.gz
Reading '/Users/carlospartida/.cpan/sources/modules/03modlist.data.gz'
DONE
Writing /Users/carlospartida/.cpan/Metadata
Running install for module 'App::cpanminus'
Running make for M/MI/MIYAGAWA/App-cpanminus-1.7044.tar.gz
Fetching with LWP:
http://cpan.mirrors.ionfish.org/authors/id/M/MI/MIYAGAWA/App-cpanminus-1.7044.tar.gz
Fetching with LWP:
http://cpan.mirrors.ionfish.org/authors/id/M/MI/MIYAGAWA/CHECKSUMS
Checksum for /Users/carlospartida/.cpan/sources/authors/id/M/MI/MIYAGAWA/App-cpanminus-1.7044.tar.gz ok

  CPAN.pm: Building M/MI/MIYAGAWA/App-cpanminus-1.7044.tar.gz

Checking if your kit is complete...
Looks good
Writing Makefile for App::cpanminus
Writing MYMETA.yml and MYMETA.json
cp lib/App/cpanminus.pm blib/lib/App/cpanminus.pm
cp lib/App/cpanminus/fatscript.pm blib/lib/App/cpanminus/fatscript.pm
cp bin/cpanm blib/script/cpanm
/usr/bin/perl -MExtUtils::MY -e 'MY->fixin(shift)' -- blib/script/cpanm
Manifying blib/man1/cpanm.1
Manifying blib/man3/App::cpanminus.3pm
Manifying blib/man3/App::cpanminus::fatscript.3pm
  MIYAGAWA/App-cpanminus-1.7044.tar.gz
  /usr/bin/make -- OK
'YAML' not installed, will not store persistent state
Running make test
PERL_DL_NONLAZY=1 /usr/bin/perl "-MExtUtils::Command::MM" "-e" "test_harness(0, 'blib/lib', 'blib/arch')" t/*.t
t/happy_cpantesters.t .. 1/1 # App::cpanminus/1.7044
t/happy_cpantesters.t .. ok   
All tests successful.
Files=1, Tests=1,  0 wallclock secs ( 0.01 usr  0.01 sys +  0.01 cusr  0.00 csys =  0.03 CPU)
Result: PASS
  MIYAGAWA/App-cpanminus-1.7044.tar.gz
  /usr/bin/make test -- OK
Running make install
```
Una vez llegado a esta parte nos pedira la contraseña del usuario para poder instalar lo. 

```
Password:
Installing /Library/Perl/5.18/App/cpanminus.pm
Installing /Library/Perl/5.18/App/cpanminus/fatscript.pm
Installing /usr/local/share/man/man1/cpanm.1
Installing /usr/local/share/man/man3/App::cpanminus.3pm
Installing /usr/local/share/man/man3/App::cpanminus::fatscript.3pm
Installing /usr/local/bin/cpanm
Appending installation info to /Library/Perl/Updates/5.18.2/darwin-thread-multi-2level/perllocal.pod
  MIYAGAWA/App-cpanminus-1.7044.tar.gz
  sudo /usr/bin/make install  -- OK
```
Una vez instalado CPAN podemos instalar el modulo a nuestra elección mediante el comando 

```
cpanm Module::Name
```
 
En este caso se instalara Bio::seq por lo que se usara el comando. 

```
cpanm Bio::Seq
``` 
Este empezara hara hacer prubas de sus distribuidores hasta completar la instalacion del modulo los cuales se veran asi:

``` 
--> Working on Bio::Seq
Fetching http://www.cpan.org/authors/id/C/CD/CDRAUG/BioPerl-1.7.5.tar.gz ... OK
Configuring BioPerl-1.7.5 ... OK
==> Found dependencies: YAML, Test::Weaken, IPC::Run, XML::DOM, Test::RequiresInternet, Graph::Directed, Test::Most, Set::Scalar, XML::SAX::Writer, GD, XML::Twig, XML::DOM::XPath, Test::Memory::Cycle, Data::Stag, XML::Parser::PerlSAX
--> Working on YAML
Fetching http://www.cpan.org/authors/id/T/TI/TINITA/YAML-1.29.tar.gz ... OK
Configuring YAML-1.29 ... OK
==> Found dependencies: Test::YAML
--> Working on Test::YAML
Fetching http://www.cpan.org/authors/id/T/TI/TINITA/Test-YAML-1.07.tar.gz ... OK
Configuring Test-YAML-1.07 ... OK
==> Found dependencies: Test::Base
--> Working on Test::Base
Fetching http://www.cpan.org/authors/id/I/IN/INGY/Test-Base-0.89.tar.gz ... OK
Configuring Test-Base-0.89 ... OK
==> Found dependencies: Spiffy
--> Working on Spiffy
Fetching http://www.cpan.org/authors/id/I/IN/INGY/Spiffy-0.46.tar.gz ... OK
Configuring Spiffy-0.46 ... OK
Building and testing Spiffy-0.46 ... OK
Successfully installed Spiffy-0.46
Building and testing Test-Base-0.89 ... OK
Successfully installed Test-Base-0.89
Building and testing Test-YAML-1.07 ... OK
Successfully installed Test-YAML-1.07
Building and testing YAML-1.29 ... OK
Successfully installed YAML-1.29
--> Working on Test::Weaken
Fetching http://www.cpan.org/authors/id/K/KR/KRYDE/Test-Weaken-3.022000.tar.gz ... OK
Configuring Test-Weaken-3.022000 ... OK
Building and testing Test-Weaken-3.022000 ... OK
Successfully installed Test-Weaken-3.022000
--> Working on IPC::Run
Fetching http://www.cpan.org/authors/id/T/TO/TODDR/IPC-Run-20180523.0.tar.gz ... OK
Configuring IPC-Run-20180523.0 ... OK
Building and testing IPC-Run-20180523.0 ... OK
Successfully installed IPC-Run-20180523.0
--> Working on XML::DOM
Fetching http://www.cpan.org/authors/id/T/TJ/TJMATHER/XML-DOM-1.46.tar.gz ... OK
Configuring XML-DOM-1.46 ... OK
==> Found dependencies: XML::RegExp, XML::Parser::PerlSAX
--> Working on XML::RegExp
Fetching http://www.cpan.org/authors/id/T/TJ/TJMATHER/XML-RegExp-0.04.tar.gz ... OK
Configuring XML-RegExp-0.04 ... OK
Building and testing XML-RegExp-0.04 ... OK
Successfully installed XML-RegExp-0.04
--> Working on XML::Parser::PerlSAX
Fetching http://www.cpan.org/authors/id/K/KM/KMACLEOD/libxml-perl-0.08.tar.gz ... OK
Configuring libxml-perl-0.08 ... OK
Building and testing libxml-perl-0.08 ... OK
Successfully installed libxml-perl-0.08
Building and testing XML-DOM-1.46 ... OK
Successfully installed XML-DOM-1.46
--> Working on Test::RequiresInternet
Fetching http://www.cpan.org/authors/id/M/MA/MALLEN/Test-RequiresInternet-0.05.tar.gz ... OK
Configuring Test-RequiresInternet-0.05 ... OK
Building and testing Test-RequiresInternet-0.05 ... OK
Successfully installed Test-RequiresInternet-0.05
--> Working on Graph::Directed
Fetching http://www.cpan.org/authors/id/J/JH/JHI/Graph-0.9704.tar.gz ... OK
Configuring Graph-0.9704 ... OK
Building and testing Graph-0.9704 ... OK
Successfully installed Graph-0.9704
--> Working on Test::Most
Fetching http://www.cpan.org/authors/id/O/OV/OVID/Test-Most-0.35.tar.gz ... OK
Configuring Test-Most-0.35 ... OK
==> Found dependencies: Test::Deep, Test::Exception, Test::More, Test::Differences, Exception::Class, Test::Harness, Test::Warn
--> Working on Test::Deep
Fetching http://www.cpan.org/authors/id/R/RJ/RJBS/Test-Deep-1.128.tar.gz ... OK
Configuring Test-Deep-1.128 ... OK
Building and testing Test-Deep-1.128 ... OK
Successfully installed Test-Deep-1.128 (upgraded from 0.112)
--> Working on Test::Exception
Fetching http://www.cpan.org/authors/id/E/EX/EXODIST/Test-Exception-0.43.tar.gz ... OK
Configuring Test-Exception-0.43 ... OK
Building and testing Test-Exception-0.43 ... OK
Successfully installed Test-Exception-0.43 (upgraded from 0.32)
--> Working on Test::More
Fetching http://www.cpan.org/authors/id/E/EX/EXODIST/Test-Simple-1.302167.tar.gz ... OK
Configuring Test-Simple-1.302167 ... OK
Building and testing Test-Simple-1.302167 ... OK
Successfully installed Test-Simple-1.302167 (upgraded from 0.98)
--> Working on Test::Differences
Fetching http://www.cpan.org/authors/id/D/DC/DCANTRELL/Test-Differences-0.67.tar.gz ... OK
Configuring Test-Differences-0.67 ... OK
==> Found dependencies: Text::Diff, Capture::Tiny
--> Working on Text::Diff
Fetching http://www.cpan.org/authors/id/N/NE/NEILB/Text-Diff-1.45.tar.gz ... OK
Configuring Text-Diff-1.45 ... OK
Building and testing Text-Diff-1.45 ... OK
Successfully installed Text-Diff-1.45 (upgraded from 1.41)
--> Working on Capture::Tiny
Fetching http://www.cpan.org/authors/id/D/DA/DAGOLDEN/Capture-Tiny-0.48.tar.gz ... OK
Configuring Capture-Tiny-0.48 ... OK
Building and testing Capture-Tiny-0.48 ... OK
Successfully installed Capture-Tiny-0.48 (upgraded from 0.23)
Building and testing Test-Differences-0.67 ... OK
Successfully installed Test-Differences-0.67 (upgraded from 0.61)
--> Working on Exception::Class
Fetching http://www.cpan.org/authors/id/D/DR/DROLSKY/Exception-Class-1.44.tar.gz ... OK
Configuring Exception-Class-1.44 ... OK
==> Found dependencies: Devel::StackTrace
--> Working on Devel::StackTrace
Fetching http://www.cpan.org/authors/id/D/DR/DROLSKY/Devel-StackTrace-2.04.tar.gz ... OK
Configuring Devel-StackTrace-2.04 ... OK
Building and testing Devel-StackTrace-2.04 ... OK
Successfully installed Devel-StackTrace-2.04 (upgraded from 1.31)
Building and testing Exception-Class-1.44 ... OK
Successfully installed Exception-Class-1.44
--> Working on Test::Harness
Fetching http://www.cpan.org/authors/id/L/LE/LEONT/Test-Harness-3.42.tar.gz ... OK
Configuring Test-Harness-3.42 ... OK
Building and testing Test-Harness-3.42 ... OK
Successfully installed Test-Harness-3.42 (upgraded from 3.26)
--> Working on Test::Warn
Fetching http://www.cpan.org/authors/id/B/BI/BIGJ/Test-Warn-0.36.tar.gz ... OK
Configuring Test-Warn-0.36 ... OK
Building and testing Test-Warn-0.36 ... OK
Successfully installed Test-Warn-0.36 (upgraded from 0.24)
Building and testing Test-Most-0.35 ... OK
Successfully installed Test-Most-0.35
--> Working on Set::Scalar
Fetching http://www.cpan.org/authors/id/D/DA/DAVIDO/Set-Scalar-1.29.tar.gz ... OK
Configuring Set-Scalar-1.29 ... OK
Building and testing Set-Scalar-1.29 ... OK
Successfully installed Set-Scalar-1.29
--> Working on XML::SAX::Writer
Fetching http://www.cpan.org/authors/id/P/PE/PERIGRIN/XML-SAX-Writer-0.57.tar.gz ... OK
Configuring XML-SAX-Writer-0.57 ... OK
==> Found dependencies: XML::Filter::BufferText
--> Working on XML::Filter::BufferText
Fetching http://www.cpan.org/authors/id/R/RB/RBERJON/XML-Filter-BufferText-1.01.tar.gz ... OK
Configuring XML-Filter-BufferText-1.01 ... OK
Building and testing XML-Filter-BufferText-1.01 ... OK
Successfully installed XML-Filter-BufferText-1.01
Building and testing XML-SAX-Writer-0.57 ... OK
Successfully installed XML-SAX-Writer-0.57
--> Working on GD
Fetching http://www.cpan.org/authors/id/R/RU/RURBAN/GD-2.71.tar.gz ... OK
==> Found dependencies: ExtUtils::PkgConfig
--> Working on ExtUtils::PkgConfig
Fetching http://www.cpan.org/authors/id/X/XA/XAOC/ExtUtils-PkgConfig-1.16.tar.gz ... OK
Configuring ExtUtils-PkgConfig-1.16 ... N/A
! Configure failed for ExtUtils-PkgConfig-1.16. See /Users/carlospartida/.cpanm/work/1566772296.90296/build.log for details.
! Installing the dependencies failed: Module 'ExtUtils::PkgConfig' is not installed
! Bailing out the installation for GD-2.71.
--> Working on XML::Twig
Fetching http://www.cpan.org/authors/id/M/MI/MIROD/XML-Twig-3.52.tar.gz ... OK
Configuring XML-Twig-3.52 ... OK
Building and testing XML-Twig-3.52 ... OK
Successfully installed XML-Twig-3.52
--> Working on XML::DOM::XPath
Fetching http://www.cpan.org/authors/id/M/MI/MIROD/XML-DOM-XPath-0.14.tar.gz ... OK
Configuring XML-DOM-XPath-0.14 ... OK
==> Found dependencies: XML::XPathEngine
--> Working on XML::XPathEngine
Fetching http://www.cpan.org/authors/id/M/MI/MIROD/XML-XPathEngine-0.14.tar.gz ... OK
Configuring XML-XPathEngine-0.14 ... OK
Building and testing XML-XPathEngine-0.14 ... OK
Successfully installed XML-XPathEngine-0.14
Building and testing XML-DOM-XPath-0.14 ... OK
Successfully installed XML-DOM-XPath-0.14
--> Working on Test::Memory::Cycle
Fetching http://www.cpan.org/authors/id/P/PE/PETDANCE/Test-Memory-Cycle-1.06.tar.gz ... OK
Configuring Test-Memory-Cycle-1.06 ... OK
==> Found dependencies: Devel::Cycle
--> Working on Devel::Cycle
Fetching http://www.cpan.org/authors/id/L/LD/LDS/Devel-Cycle-1.12.tar.gz ... OK
Configuring Devel-Cycle-1.12 ... OK
Building and testing Devel-Cycle-1.12 ... OK
Successfully installed Devel-Cycle-1.12
Building and testing Test-Memory-Cycle-1.06 ... OK
Successfully installed Test-Memory-Cycle-1.06
--> Working on Data::Stag
Fetching http://www.cpan.org/authors/id/C/CM/CMUNGALL/Data-Stag-0.14.tar.gz ... OK
Configuring Data-Stag-0.14 ... OK
Building and testing Data-Stag-0.14 ... OK
Successfully installed Data-Stag-0.14
! Installing the dependencies failed: Module 'GD' is not installed
! Bailing out the installation for BioPerl-1.7.5.
31 distributions installed
``` 
o igual si sale algun error puede checarse el README de [BioPerl](https://github.com/bioperl/bioperl-live/blob/master/README.md) o en [Directory](https://github.com/bioperl/bioperl-live/blob/master/HACKING.md) puedes checar ayuda para la busqueda de distintos modulos