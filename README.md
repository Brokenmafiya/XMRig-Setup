# XMRig-Setup
# -Install dependencies

sudo apt update && sudo apt install -y git build-essential cmake libuv1-dev libssl-dev libhwloc-dev

# Clone and build XMRig:

git clone https://github.com/xmrig/xmrig.git
cd xmrig
mkdir build && cd build
cmake ..
make

# Create a config.json with your wallet




git clone this;repo
cd XMRig-Setup/xmrig/build
./xmrig

