Set Up a Bitcoin Core Cold Wallet
=================================
## BASH script to set up an offline Tails session

You may need to open a [Bitcoin Core](https://bitcoin.org/en/bitcoin-core/) cold wallet in an offline Tails session - maybe you need to add an additional receiving address or maybe you wake up in a cold sweat wondering if you still have the correct passphrase for your cold wallet.

This script helps connect things up so that you can access the wallet in Bitcoin Core.

It runs a zenity GUI which prompts the user to select:
* The cold wallet file
* The `bitcoin-qt` binary

These files might be on your Tails persistent volume, or on any USB drive.
