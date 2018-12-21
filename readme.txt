1. ID : 104062302
2. Name : 洪旻夆
3. Language : <C++>
4. Compiler : <GNU g++>
5. Compress : <tar zcvf CS6135_HW4_104062302.tar.gz HW4>
6. Files :
    HW4/src        : source codes
    HW4/bin/place  : binary executable
    HW4/readme.txt : this file
    HW4/report.pdf : report

7. Compile : (In HW4/src directory)
    Compilation
	    $ make
	Remove executable file
	    $ make clean

8. Execution :
    After compilation, there exists an executable file named <place>
	    $ ./place -aux <path/to/aux/file>
	e.g
	    $ ./place -aux benchmark/ibm01/ibm01-cu85.aux