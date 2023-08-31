# panther-iros-demo
Demo setup for Panther for iROS 2023 in Detroit

## Usage

First connect to the Panther's WiFi network, then connect to the NUC (`10.15.20.3` IP address), clone this repository and run:
```
docker compose up
```

Then on your computer open browser, connect to the address `10.15.20.3:8080`.
Now click the plus sign next to the `Data source` in the left top corner, select `Open connection` and set the `WebSocket URL` to `ws://10.15.20.3:9090`, finally click `Open`.