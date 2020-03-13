## Test environments
* local Window, R 3.5.1
* Ubuntu Xenial 16.04 which is default operation, R 3.6.2 which is default version (on travis-ci)


## R CMD check results
There were no ERRORs or WARNINGs. 



##2020-02-25:
There was 2 NOTE:

* checking CRAN incoming feasibility ... NOTE

  This is the new submittion of the 'RobMixReg' package.

* checking top-level files ... NOTE
Non-standard file/directory found at top level:
  ‘cran-comments.md’
  
  The 'cran-comments.md' file use as the log file. 


##2020-03-04:

This submission revised as below description based on the Jelena Saf's comments.

1. Rewrite the description of title in DESCRIPTION file.

2. Add author information by using the Author@R way.

3. Suppressed or annotated the useless information prited on the console.

4. In the main function ("rmr"), enable automatic testing for the example.

5. Rewrite the document (.Dd documentation) for all the functions.

##2020-03-05

Thanks the response from the Uwe Ligges.

This submisstion fixed the doi issue in the DESCRIPTION file.

##2020-03-13

Thanks the response from the Jelena Saf's comments.

1. Add explaination for the abbreviation of algorithms in the DESCRIPTION file.

2. Add example for each algorithm and enalble auto testing.
