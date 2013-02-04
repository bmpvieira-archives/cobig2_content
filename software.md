Software
========

4Pipe4
------

*4Pipe4 is an NGS analysis pipeline with emphasis on SNP detection, especially when no strain information is available.*

4Pipe4 is written in python3 and is licensed under the [GPLv3](http://www.gnu.org/licenses/gpl-3.0.html).

This pipeline automates and simplifies the use of several programs trough a unified configuration file.

The list of used programs (these need to be installed by the user):

* [sff_extract](http://bioinf.comav.upv.es/sff_extract/)
* [seqclean](http://compbio.dfci.harvard.edu/tgi/software/)
* [mira](http://mira-assembler.sourceforge.net/)
* [EMBOSS GetORF](http://emboss.sourceforge.net/apps/cvs/emboss/apps/getorf.html)
* [NCBI BLAST](ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/)
* [Blast2go4pipe](http://bioinfo.cipf.es/aconesa/software.html)
* [EMBOSS etandem](http://helixweb.nih.gov/emboss/html/etandem.html)
* [7zip](http://www.7-zip.org/)

Also recomended is a local version of [NCBI's Univec](http://www.ncbi.nlm.nih.gov/VecScreen/UniVec.html) and sequence database, such as "[nr](ftp://ftp.ncbi.nlm.nih.gov/blast/db/)".

Downloads

[4Pipe4 V1.1.1](http://cobig2.fc.ul.pt/downloads/4Pipe4-1.1.1.tar.gz)
If you wish to get the very latest code, however, you can get the development version from [github](https://github.com/StuntsPT/4Pipe4).

Bugs & other issues

Please direct any, questions to the [author](mailto:f.pinamartins@gmail.com) and bugs, feature requests, etc... to github's [issue tracker](https://github.com/StuntsPT/4Pipe4/issues).

 
Concatenator
------------

*Concatenator V 1.1.0:*

Concatenator is a small utility with two functions:

1) The conversion of files between FASTA and NEXUS formats, with costumizable output;

2) The concatenation of up to five NEXUS files, being the output ready to use with popular phylogenetic programs, such as PAUP* or MrBayes;

The interface was designed to be extremely simple and intuitive, but nevertheless, helpfiles are available on each program window.

[Windows binary version](http://cobig2.fc.ul.pt/images/Concatenator/Concatenator.zip). Ready to use on a Windows machine.

[Source code for windows](http://cobig2.fc.ul.pt/images/Concatenator/Concatenator%20%20source%20windows.zip). If you prefer to run the script rather then the binary file. Requires Perl and Perl/Tk module to run.

[Source code for MAC & LINUX systems](http://cobig2.fc.ul.pt/images/Concatenator/Concatenator%20%20source%20unix.tar.gz). In case this is your OS of choice. Requires Perl and Perl/Tk module to run.

[MAC OS X Install manual](http://cobig2.fc.ul.pt/images/Concatenator/Mac%20Install%20Manual.pdf).

*Concatenator is released under a GPL license.*

### How to cite: ###

Pina-Martins F, Paulo OS (2008). Concatenator: Sequence Data Matrices Handling Made Easy. Molecular Ecology Resources 8, 1254-1255

### Known bugs: ###

Concatenator will crash without an error message if you try to concatenate files where at least one of them has a repeated taxa name. As a workaround, you can rename the repeated taxa names with a different name. We are currently working on this bug.

In some versions of Windows Vista, Concatenator is unable to save files to any folder other than the desktop. Even if you start Concatenator with administration rights, this will still occur.

In some cases Concatenator will not be able to read or write files to some directories with unusual characters, such as "ç, ã, õ, é, etc...". As a workaround, just save or load files from a directory tree without these characters.