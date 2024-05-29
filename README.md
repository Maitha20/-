SELECT datetime (times tamp/1000000+
                (strftime('%s','1601-01-01')),'unixepoch','localtime')
