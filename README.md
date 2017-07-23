# HADOOP SEMINAR FOR RVCE

```sh
$ hadoop com.sun.tools.javac.Main WordCount.java 
$ jar cf wc.jar WordCount*.class
$ hadoop jar wc.jar WordCount /user/tejashl/wordcount/input /user/tejashl/wordcount/output17
$ hadoop fs -cat /user/tejashl/wordcount/output34/part-r-00000
```

| Program | Purpose |
| ------ | ------ |
| prgm1 | Word Count |
| prgm2 | how many files the word has been mentioned |
| prgm3 | displaying the file names instead of the count |
| prgm4 | Word Count per files |
| prgm5 | Words positions in file] |
