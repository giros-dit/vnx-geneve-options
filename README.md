# vnx-geneve-options
A demo of creating geneve tunnels with options controlled by tc 

## How to test it

1. Start the vnx scenario
2. Start a wireshark capture on isp-e1
3. Ping from h1 to h2. On wireshark, verify that this traffic is sent with geneve option 11111111
4. Ping from r1 to r2 and from t1 to t2. On wireshark, verify that this traffic is sent with geneve option 22222222


