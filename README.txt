= Hacking JSON support into Sqoop

This is the Sqoop (SQL-to-Hadoop) tool with an added hack to allow for saving
the imported data set in json format.

= Sqoop original repo

https://git-wip-us.apache.org/repos/asf/sqoop.git

= Sqoop info

http://sqoop.apache.org

= What I've done

Added a new flag `--to-json` that will change the output format to json. When
using `--to-json` all delimiters, field separators, etc. will be ignored.
