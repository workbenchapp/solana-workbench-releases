## 0.0.1-alpha

- Release the first version of Workbench. Functionality includes:
    - Start validator locally and stream/filter logs
    - Generate keypairs by pushing a button and airdrop SOL to them
        - These keypairs are accessible for use with the `solana` CLI in directory `$HOME/.solana-workbench/keys`.
        - e.g., `solana -k $HOME/.solana-workbench/keys/2Jb3kwLR9dFULFDETc5vFhMpgu4MSvcKb568c6bHt475.json balance`
    - Retrieve and render Anchor IDL by program ID 
