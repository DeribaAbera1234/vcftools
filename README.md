# VCFtools

A set of tools written in Perl and C++ for working with VCF files, such as those generated by the
1000 Genomes Project.

Project website: https://vcftools.github.io/

License
-------

The program package is released under the GNU Lesser General Public License version 3.0
(LGPLv3). See the `LICENSE` file for the complete LGPL license text.

Credits
-------

- Adam Auton (Binary Executable)
- Petr Danecek (Perl Module)
- Anthony Marcketta (Binary Executable)

Building VCFtools
-----------------

General help about the building process's configuration step can be acquired via:

```
./configure --help
```

### Build from Release Tarball

```
./configure
make
make install
```

### Build from GitHub

```
git clone https://github.com/vcftools/vcftools.git
cd vcftools
./autogen.sh
./configure
make
make install
```

Documentation
-------------

Documentation and usage examples of usage can be found here:

https://vcftools.github.io/examples.html

A manual page is also available. If prefix is set to the default `/usr` or if `MANPATH` points to
`$prefix/usr/share/man`, you can type:

```
man vcftools
```

Getting Help
------------

The best way to get help regarding VCFtools is to email the mailing list:

mailto:vcftools-help@lists.sourceforge.net

Citation
--------

If you make use of VCFtools in your research, we would appreciate a citation of the following paper:

**The Variant Call Format and VCFtools**, Petr Danecek, Adam Auton, Goncalo Abecasis, Cornelis
A. Albers, Eric Banks, Mark A. DePristo, Robert Handsaker, Gerton Lunter, Gabor Marth, Stephen
T. Sherry, Gilean McVean, Richard Durbin and 1000 Genomes Project Analysis Group,
**Bioinformatics**, 2011 http://dx.doi.org/10.1093/bioinformatics/btr330
