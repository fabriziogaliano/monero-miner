# monero-miner

# Support CPU mining using Cryptonight algo, this image it's based on [xmrig][1]

Ovverride the run command with your own information:
```
docker run --name monero-miner \
fabriziogaliano/monero-miner \
--url=pool.supportxmr.com:5555 \
--user=46VepA9vrkhYN5tb2c27KnK4TZZr3vtJ9DErrxRGfrEBUFnwTJHryG6PcYtwaPq92CZ92FNDd5r5iTTy9V6cXxtn4hRPDcz \
--pass=w01:fabrikorn555@hotmail.com \
-k \
--max-cpu-usage=90 \
--donate-level=1
```

Feel free to increase Donate Level ;)

[1]:https://github.com/xmrig/xmrig/
