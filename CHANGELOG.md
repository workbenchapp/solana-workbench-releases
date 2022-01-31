#### 0.2.0-alpha

- Massively revamped accounts/keys section. [Demo here](https://www.youtube.com/watch?v=GdzdUdran7Y). New features:
    - **Pre-airdropped Wallets** are created automatically for local dev usage.
    - **Account Management.** Accounts across all networks can now be yanked into user lists by pubkey and labeled for easy tracking.
    - **Explorer Integration.** A inspect sub-view for accounts includes a link to the Solana Explorer with the correct network pre-populated.
- Program Change "live view" on Accounts page.
    - **Surface accounts of interest.** This provides a way for users to easily yank accounts of interest.
    - **Filter by Owning Program.** By default changes on System Program are shown, but custom programs are supported with the "Filter" dropdown.
    - **Changes sorted by relevance.** Program changes are sorted by default based on the maximum amount of SOL change seen during live streaming (descending). The goal of this is to surface interesting accounts and sample based on information (i.e., how much money changed hands).
    - ⚠️ CAVEAT: This feature still has performance issues on mainnet-beta. Don't let it run longer than a few minutes. (We wanted to release it anyway to collect user feedback)
- Some navigation changes, accounts page is now front and center.

#### 0.1.2-alpha

- Add OSX icon
- Fix exec'ing issues on OSX
- Signed OSX binaries!
- Improved state management logic for test validator
- Change `<code>` to display black-on-grey instead of pink-on-white because seriously, why is the default pink-on-white?
- Local app logs to enable troubleshooting issues

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
