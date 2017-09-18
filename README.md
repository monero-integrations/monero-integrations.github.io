## How To use Monero Integrations

* Install a Monero Integration, it can be for woocommerce, prestashop or whmcs

* Setup a monero wallet using the monero-wallet-cli tool. If you do not know how to do this you can learn about it at [getmonero.org](https://getmonero.org/resources/user-guides/monero-wallet-cli.html)

* Start the Wallet RPC and leave it running in the background. This can be accomplished by running `./monero-wallet-rpc --rpc-bind-port 18082 --rpc-login username:password --log-level 2 --wallet-file /path/walletfile` where "username:password" is the username and password that you want to use, seperated by a colon and  "/path/walletfile" is your actual wallet file. If you wish to use a remote node you can add the `--daemon-address` flag followed by the address of the node. `--daemon-address node.moneroworld.com:18089` for example.
