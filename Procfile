web: node node-server.js
worker: aria2c --enable-rpc --rpc-listen-all=true --rpc-listen-port 6800 --max-concurrent-downloads=4 --max-connection-per-server=10 --rpc-max-request-size=1024M --seed-time=0.01 --min-split-size=10M --follow-torrent=mem --split=10 --rpc-secret=rudu123 --daemon=true
