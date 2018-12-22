# Global Placement

- Files
    - HW4/src        : source codes
    - HW4/bin/place  : binary executable
    - HW4/README.md : this file
    - HW4/report.pdf : report

- Compile (In HW4/src directory)
    - Compilation
      ```
        make
      ```
    - Remove executable file
      ```
        make clean
      ```

- Execution
    After compilation, there exists an executable file named <place>
	    $ ./place -aux <path/to/aux/file>
	e.g
	    $ ./place -aux benchmark/ibm01/ibm01-cu85.aux
	
- Description
    Global Placement implemented by Analytical Approach
    Only implemented objective value and gradients in GlobalPlacer.cpp and ExampleFunction.cpp
