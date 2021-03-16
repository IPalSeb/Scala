## How to mine Scala with a Orange PI


| MODEL | SO | Hashrate(H/s) |
| ----- | ---- | ---- |
| Example | Example  | Example  |



1. Firts of all, update your RPI.

`sudo apt update`

`sudo apt full-upgrade`


2. Reboot if necessary.

`sudo shutdown -r now`


3. Install the needed dependencies.

`sudo add-apt-repository ppa:ubuntu-toolchain-r/test -y`

`sudo apt update sudo apt install aptitude -y`

`sudo aptitude install -y build-essential g++-8 gcc-8 git cmake libuv1-dev libmicrohttpd-dev libssl-dev export CC=gcc-8 export CXX=g++-8`


4. Download the latest XLArig and compile it.

`git clone https://github.com/scala-network/XLArig.git`

`cd xlarig`

`mkdir build`

`cd build`

`cmake ..`

`make`


5. Give the miner execution rights.
`chmod u+x xlarig`


6. Start minning with...

`./xlarig --donate-level 0 -o scala.pooldemineria.com:3333 -u YOUR_SCALA_WALLET_ADDRESS -p YOUR_WORKER_NAME -a panthera -k`


**Donations:** Svkzohotw2D5xk8r8JJ7ePX1K2NgPrJBJ61eVE17jVogKD5dksagwnE1akdLkR6P3NEU9TdqqN3bEXB4ryubGukS2gB2sr5v7


**Best pool for minning:** [PoolDeMineria.com](http://scala.pooldemineria.com)
