HiveQueryScripts
================

This project analyzes movieLens data <http://files.grouplens.org/datasets/movielens/ml-100k-README.txt> using hive running on hadoop platform.

Objective: Find the number of clients accessing movies across the days of the week.

Results are found in output.txt

### To run script

- starts hadoop
** $hstart **

- execute the script using hive
** $hive -f hivequeryScript.hive >> output.txt **

