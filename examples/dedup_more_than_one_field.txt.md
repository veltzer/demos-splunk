Lets say we web logs from 10 different servers (field=host)
And we do

dedup 2 host,httpcode

The for each of the 10 hosts we will one line for each http code:

host1,200,...
host1,200,...
host1,404
host1,506
host2,200
host2,404
host2,507
host2,508
