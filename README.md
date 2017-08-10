# Foofah Benchmarks

This repository contains all the benchmark tests used in Foofah project: 
* Each test file contains a json object, which includes the following data items: `InputTable`, `OutputTable`, `TestingTable`, `TestAnswer`.
* `InputTable` and `OutputTable` are the input-output example send to Foofah for synthesizing the data transformation program.
* `TestingTable` and `TestAnswer` are used to verify if the synthesized data transformation program is perfect.
* Each table is a 2-dimenstional array of strings. 

The source code of Foofah is [here](https://github.com/umich-dbgroup/foofah).