
- I love Linux, Bitcoin, NOSTR, Proxmox, building electronics, and computer security.
  
- Working on <a href="https://github.com/BoldBitcoinWallet/BBMTLib" target="_blank">Bold Bitcoin Wallet Library</a> AKA (the poor man's multi-sig warm wallet)
  
  - Developed for people who live someplace where obtaining a hardware wallet isn't possible, and don't want to risk their bitcoin on a single-sig hot wallet.
  - Uses M-of-N <a href="https://github.com/bnb-chain/tss-lib" target="_blank">multi-party computation threashold signature scheme</a>. (until FROST is production ready, I am currently working on upgrading to more effecient <a href="https://github.com/HalFinneyIsMyHomeBoy/DKLs23-BBMTLib" target="_blank">DKLs23 Library</a>)
  - All transactions appear on-chain as single-sig, which increases privacy and cheaper in fees than on-chain multi-sig.
  - Key generation and TX signing are transmitted via <a href="https://github.com/nostr-protocol/nips/blob/master/44.md" target="_blank">NOSTR (NIP-44) v2</a> encryption, then <a href="https://www.e2encrypted.com/nostr/nips/59/" target="_blank">Rumor/Seal/Wrap method</a> for added security.
   
- I collaborate on various Bitcoin projects that I find useful like <a href="https://github.com/utreexo/utreexod" target="_blank">Utreexod</a>, <a href="https://github.com/vinteumorg/Floresta" target="_blank">Floresta</a>, <a href="https://github.com/stutxo/op_ctv_payment_pool" target="_blank">OP_CTV Payment Pool</a> and others.
- Currently experimenting/researching the Ark protocol and different implementations/proof of concepts like Bark and Arkade.
- Migrated to primarily using Go and Rust after being a C# .NET and Python dev for most of my career.
