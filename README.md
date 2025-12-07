# base1111.
Speed Comparison: Base RPC Providers Benchmarked  You can benchmark latency.  Python:
import time
urls = ["https://mainnet.base.org", "https://base.publicnode.com"]
for url in urls:
    t=time.time(); Web3(Web3.HTTPProvider(url)).eth.block_number
    print(url, time.time()-t)
