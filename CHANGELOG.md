#### 0.1.1-alpha

- Performance enhancements and bugfixes, esp. around "Run Deps" page
    - Polling for status and validator lifecycle + logs were a bit of a shit show in last release, that's been smoothed out a lot. The polling for logs was crushing my Macbook Air so I eased it up a bit. Let us know how you like the new 
- M1 Mac support! (ARM, so should work fine on Linux once we get builds for that up)
    - I haven't tested directly so please give it a whirl if you have one

#### 0.1.0-alpha

- Release the first version of Workbench. Functionality includes:
    - Start validator locally and stream/filter logs
    - Generate keypairs by pushing a button and airdrop SOL to them
        - These keypairs are accessible for use with the `solana` CLI in directory `$HOME/.solana-workbench/keys`.
        - e.g., `solana -k $HOME/.solana-workbench/keys/2Jb3kwLR9dFULFDETc5vFhMpgu4MSvcKb568c6bHt475.json balance`
    - Retrieve and render Anchor IDL by program ID 
