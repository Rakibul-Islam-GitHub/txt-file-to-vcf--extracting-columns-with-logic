### txt to data (column) extract with logic

sample txt data:

```
CS 1202425011031 Jhone Doe 1***569437 63 53 10 0 84%
CS 1202425011032 JANE P LINA 1***829745 63 31 32 0 49%
ECE CS 1202425033740 ADAM 1***370202 63 15 48 24%

```

logic is to remove 13 digit column and any column(s) before it. then take 10 digit as phone number and add +880 with it. after that, take previous column(s) as name.
