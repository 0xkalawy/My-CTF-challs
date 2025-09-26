# Description
We commonly transmit a lot of data over the network, so we decided to create our serialization method. Our message buffer is constructed as follows:

2-byte data length
Actual data
another 2-byte length
Actual data
2-byte length
Actual data
let's minify it as follows: 2B:data:2B:data:2B:data
