# Wordcount

1) copy clone path 

Open command line  :

2) git clone <clone path>

3) Eclipse > Import > Existing Projects into workspace

4) If there are no errors : goto 5 (Might need to import hadoop binaries)

5) File > Export > Jar file (select the project Wordcount) and save

6) Run the hadoop jar fFrom command line : (Pleae change the arguments 1 & 2 nased on input and output)

hadoop jar jars/Wordcount.jar WordCount /user/cloudera/wordcount/inp.txt /user/cloudera/wordcount/Output
