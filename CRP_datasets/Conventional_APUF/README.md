# Conventional APUF data of 31500 CRPs in two files
- _partchal3.txt_ contains 31500 Challenges
- _partresp3.txt_ contains 31500 corresponding Responses
  ## The files format is {0,1} and **NOT** {+1,-1}. This encoding is done inside the script
  ## For example, see _lregressionBINin.py_ , which contains the Python script for basic Logistic Regression Attack on PUF
