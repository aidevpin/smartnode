# smartnode
Install MasterNode

Send 5.0 UTO to wallet address 1 Go to Tools -> Debug console.

Type the following RPC command, to create an address for the masternode fee:

getnewaddress

Example output

1KZfBWXhRkR9z2orJjyHtk4t7NYESgmZFu

Go back to your wallet overview.

Press on the toolbar button "Send".

Enter the address from the RPC command “getnewaddress” behind the text "Pay To:". (Example: TRPLV4dXmEFMSgXg2Xu6skN9pmw8TAo4N5)

Enter the following amount of coins behind the text "Amount:": 5

Send 10000.0 UTO to wallet address 2 Go back to the console of your wallet.

Type the following RPC command, to create an address for the masternode collateral:

getnewaddress

Example output

TFi68ygQkc8h27DyeBwPykVHjF6oh8PGkH

Go back to your wallet overview.

Press on the toolbar button "Send".

Enter the address from the RPC command “getnewaddress” behind the text "Pay To:". (Example: TFi68ygQkc8h27DyeBwPykVHjF6oh8PGkH)

Enter the following amount of coins behind the text "Amount:": 10000.0

Press on the button "Send".

Wait until the transaction is confirmed by 15 blocks.

Get Identify the transaction with the following RPC command masternode outputs

Example output

{ 3a990b698e0481a7b8631dd07ca2d650dc9fe904adc1cc082ffbca4e60e6ba6c-1 }

Generate a BLS key pair with the the following RPC command bls generate

Example output

{ "secret": "0acbf6f183d0c9b794b9bc0dba25f8a1a1eca21aa4f2e4a86ecd3120a59efb35", "public": "8358b9f16e3072b47e6c7ec92b8784057675fc5bad9b5cdc51b4f76f01395c91956a2fe57f0463f9c7837a7eb458b9fb" }

Get Two New Wallet Address getnewaddress

Example output

17cBnqjYjAuDLTm7KBk2CMJhs9xaLqD6ie

getnewaddress

Example output

1PLFgtzZaR5bEbnVBeDbVRbifxQwcshj8N

Note protx register "3a990b698e0481a7b8631dd07ca2d650dc9fe904adc1cc082ffbca4e60e6ba6c" 0 "1.1.1.1:19520" "17cBnqjYjAuDLTm7KBk2CMJhs9xaLqD6ie" "8358b9f16e3072b47e6c7ec92b8784057675fc5bad9b5cdc51b4f76f01395c91956a2fe57f0463f9c7837a7eb458b9fb" "1PLFgtzZaR5bEbnVBeDbVRbifxQwcshj8N" 0 "1KZfBWXhRkR9z2orJjyHtk4t7NYESgmZFu"
