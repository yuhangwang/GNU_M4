# GNU_M4
**GNU M4 traditional Unix macro processor**

This is an unofficial verbatim redistribution of the binary&source form of the GNU M4 under its open source license (GPL 3.0) terms (see the LICENSE file).

This redistribution is under the same license as the original.

Please visit the official website for more details: http://www.gnu.org/software/m4/m4.html

## Download
You can download the compiled binary files at the [release page](https://github.com/yuhangwang/GNU_M4/releases).

## Compilation notes
### Compilation environment
* CentOS 6.6
* x86_64 architecture
* Compiler: gcc version 4.4.7 20120313 (Red Hat 4.4.7-11)

### Compilation steps
#### Version: 1.4.17 (2013)
```bash
wget  wget http://ftp.gnu.org/gnu/m4/m4-1.4.17.tar.bz2
tar xvf m4-1.4.17.tar.bz2
mkdir build_m4-1.4.17
cd build_m4-1.4.17
../m4-1.4.17/configure --prefix=/home/steven/install/m4/1.4.17
make -j16
make check -j16 | tee QualityVerification.txt
make install
```

### Quality verification
See the "QualityVerification.txt" for the output of "make check".
