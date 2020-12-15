##How to mine Scala with a Raspberry PI##

I tried this with a Raspberry Pi 3B+ with the SO Raspbian. If you try with other RPI model or other SO, send me a message and I can update the table.


| MODEL | SO | Hashrate(H/s) |
| ----- | ---- | ---- |
| 3B+ | Raspbian | 100 |


1. Firts of all, update your RPI.

`sudo apt update`

`sudo apt full-upgrade`


2. Reboot if necessary.

`sudo shutdown -r now`


3. Now, install the ds64-shell. You can run 64 bit programs with it.

`sudo apt-get install -y raspbian-nspawn-64`


4. Start it with:

`ds64-shell`

(You can close it with `exit` )


5. Download the last version of the Linux XLARig.

`wget https://github.com/scala-network/XLArig/releases/download/v5.1.0/XLArig-v5.1.0-linux-x86_64.zip`


6. Unzip it.

`unzip XLArig-v5.1.0-linux-x86_64.zip`

(Maybe, you don't have installed unzip, install it with `sudo apt-get install unzip`)


7. Enter in the folder.

`cd XLArig-v5.1.0-linux-x86_64`

8. Give run permissions to the miner.

`chmod +x xlarig`

9. Start minning with...

`./xlarig --donate-level 0 -o scala.pooldemineria.com:3333 -u YOUR_SCALA_WALLET_ADDRESS -p YOUR_WORKER_NAME -a panthera -k`


**Donations:** Svkzohotw2D5xk8r8JJ7ePX1K2NgPrJBJ61eVE17jVogKD5dksagwnE1akdLkR6P3NEU9TdqqN3bEXB4ryubGukS2gB2sr5v7

**Best pool for minning:** [PoolDeMineria.com](http://scala.pooldemineria.com)
