curl -L https://github.com/ionet-official/io-net-official-setup-script/raw/main/ionet-setup.sh -o ionet-setup.sh

chmod +x ionet-setup.sh && ./ionet-setup.sh

sudo apt install curl

curl -L https://github.com/ionet-official/io_launch_binaries/raw/main/io_net_launch_binary_linux -o io_net_launch_binary_linux

chmod +x io_net_launch_binary_linux

./io_net_launch_binary_linux --device_id=30b6d991-3709-4844-94b5-0ecc9a20e8d4 --user_id=609a0c87-ec1a-412f-8415-18b6f7a76175 --operating_system="Linux" --usegpus=true --device_name="New-device"