Sample-Map-Reduce
=================
Each file in this folder `data` contains entries that look like
journals/cl/SantoNR90:::Michele Di Santo::Libero Nigro::Wilma Russo:::Programmer-Defined Control Abstractions in Modula-2.
that represent bibliographic information about publications, formatted as follows:

````
paper-id:::author1::author2::…. ::authorN:::title
````

The task is to compute how many times every term occurs across titles, for each author.
For example, the author Alberto Pettorossi the following terms occur in titles with the indicated
cumulative frequencies (across all his papers): program:3, transformation:2, transforming:2, using:2, programs:2, and logic:2.

I use [mincemeatpy](www.google.com) to implement.

##Running
1. Run Map-Reduct server by using `python sample.py`

2. Run the clients `python mincemeat.py -p changeme 127.0.0.1`



###NOTE
This sample is 3rd homework in Web Intelligence and Big data course in [Coursera](https://www.coursera.org/).
