# FRAP-example
Simple FRAP example

0. Make a directory for your programs

`mkdir bin`

2. Download smalt
`cd bin` 

`wget wget https://sourceforge.net/projects/smalt/files/smalt-0.7.6-static.tar.gz`

`tar -xvf smalt-0.7.6-static.tar.gz`

`cd smalt-0.7.6`

`./configure --prefix=/home/ana/bin`

`export PATH=$PATH:/home/ana/bin/smalt-0.7.6/src`

3. Download FRAP

`git clone https://github.com/yinacobian/FRAP-basic.git`

5. Download a database

`mkdir DB`
`wget https://ftp.ncbi.nlm.nih.gov/refseq/release/viral/viral.1.1.genomic.fna.gz`
`gunzip viral.1.1.genomic.fna.gz`

6. Download a dataset

`mkdir DS`
`cp `

7. Run FRAP

`cd /home/ana/bin/FRAP-basic`
`perl jmf4.pl`


