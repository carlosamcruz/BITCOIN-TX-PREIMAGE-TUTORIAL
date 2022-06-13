# BSV-TX-PREIMAGE-TUTORIAL

Herein I show how to create and use the preimage of a transaction in the BSV Blockchain. 

There is no easy docs availabe that clearly teaches the steps to create a transction preimage for the BSV Blockchain.

Therefore I will put here my experience of creating this structure and will try to keep it uptodated, following changes that may happens in the future.

PreImage of P2PKH transaction of ForkID 41 type

[BSV TX V3 (1).pdf](https://github.com/carlosamcruz/BSV-TX-PREIMAGE-TUTORIAL/files/8664989/BSV.TX.V3.1.pdf)

Explorando os Detalhes das Transações no Protocolo Bitcoin - Aula 01 - https://youtu.be/vIfcjOXMMAk

[Cracking-TXBSV-Aula 01.pdf](https://github.com/carlosamcruz/BSV-TX-PREIMAGE-TUTORIAL/files/8824889/Cracking-TXBSV-Aula.01.pdf)

EDTX Protocolo Bitcoin - Aula 02 - Pre Imagem https://youtu.be/oZ9bhsQMV1U

References

[1] C. S. Wright (Satoshi Nakamoto). Bitcoin: A Peer-to-Peer Electronic Cash System. 2008. - https://www.bitcoinsv.io/bitcoin.pdf

[2] Two Hope Ventures.Transaction Spec for Bitcoin. Layout: Specification, Date: 2017-08-26, Activation: 1515888000, Version: 1.0. https://twohop.ventures/wp-content/uploads/2019/12/BSVSpec-Transactions-V1.0.pdf

[3] A. Barnini, and A. Aglietti. ScriptSig: A Bitcoin Architecture Deep Dive. November 22nd 2020. https://hackernoon.com/scriptsig-a-bitcoin-architecture-deep-dive-fs1i3zvy

[4] A. Barnini, and A. Aglietti. BITCOIN From theory to practice. ISBN-13 ‏ : ‎ 979-8601742344. Independently published (19 junho 2020). https://bitcoininaction.com/

[5] A. M. Antonopoulos. Mastering Bitcoin. First Edition by Andreas M. Antonopoulos LLC is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License. https://github.com/bitcoinbook/bitcoinbook

[6] The Bitcoin Wiki. https://wiki.bitcoinsv.io/index.php/Main_Page

[7] SIGHASH flags. https://wiki.bitcoinsv.io/index.php/SIGHASH_flags

[8] OP CHECKSIG. https://wiki.bitcoinsv.io/index.php/OP_CHECKSIG

[9] Replay Protected Sighash. BUIP-HF Digest for replay protected signature verification across hard forks. 2017-07-16. https://reference.cash/protocol/forks/replay-protected-sighash

[10] Transaction Signing. https://www.reference.cash/protocol/blockchain/transaction/transaction-signing

[11] BUIP-HF Digest for replay protected signature verification across hard forks. Version 1.2, 2017-07-16. https://github.com/bitcoin-sv/bitcoin-sv/blob/master/doc/abc/replay-protected-sighash.md#OP_CHECKSIG

[12] Transaction Signing. https://flowee.org/docs/spec/blockchain/transaction/transaction-signing/

[13] Advanced OP_PUSH_TX. https://xiaohuiliu.medium.com/advanced-op-push-tx-78ce84f69a66

[14] How does Bitcoin work?. https://learnmeabitcoin.com/

[15] ScriptSig Explaination. https://gist.github.com/itoonx/05342939b80d7d1bb61c9135c24b013a

[16] A. Barnini, and A. Aglietti. Bitcoin in Action. https://bitcoininaction.com/

[17] Announcement: Double Spend Proof (“dsproof-beta”). https://reference.cash/protocol/network/messages/dsproof-beta

[18] Transaction Signing. https://reference.cash/protocol/blockchain/transaction/transaction-signing#bitcoin-cash-signatures.

[19] sighashtype.h. Copyright (c) 2017-2018 Bitcoin developers.https://github.com/bitcoin-sv/bitcoin-sv/blob/master/src/script/sighashtype.h

[20] Opcodes used in Bitcoin Script. https://wiki.bitcoinsv.io/index.php/Opcodes_used_in_Bitcoin_Script

[21] Bitcoin Transactions. https://wiki.bitcoinsv.io/index.php/Bitcoin_Transactions

[22] SuperAsset. https://bitcoinfiles.org/t/80c06d32012577b41ffea21a0b0aadefdb1331c8bb62ddc1a2d2682a9a90b7d2

[23] sCrypt Release 0.0.1. https://scryptdoc.readthedocs.io/_/downloads/en/latest/pdf/


[25] Bitcoin address. https://wiki.bitcoinsv.io/index.php/Bitcoin_address

[26] Technical background of Bitcoin addresses. https://wiki.bitcoinsv.io/index.php/Technical_background_of_Bitcoin_addresses

[27] What type of Bitcoin address should I use. https://shiftcrypto.ch/blog/what-are-bitcoin-address-types/

[28] What Is a Bitcoin Address? A 3-Minute Rundown. https://blog.hubspot.com/marketing/bitcoin-address


[29] Elliptic Curve Cryptography. November 3, 2013

[30] T. Pornin. Deterministic Usage of the Digital Signature Algorithm (DSA) and Elliptic Curve Digital Signature Algorithm (ECDSA). August 2013.

[31] Barker, E. B., Barker, W. C., Burr, W. E., Polk, W. T., and Smid, M. E. (2007). Sp 800-57. Recommendation for key management, Part 1: General (Revised). Technical report, Gaithersburg, MD, United States.

[32] FIPS (1977). Data encryption standard (DES). Federal Information Processing Standards. Publication 46-3. FIPS 46.

[33] FIPS (1981). DES modes of operation. Federal Information Processing Standards. Publication 81. FIPS 81.

[34] NSA (2009). The Case for Elliptic Curve Cryptography. U.S. National Security Agency. Archived from the original on 2009-01-17.

[35] NSA (2016). Commercial National Security Algorithm Suite and Quantum Computing FAQ. U.S. National Security Agency.

[36] Sendrier, N. (2017). Code-based cryptography: State of the art and perspectives. IEEE Security and Privacy, 15(4):44–50. DOI: 10.1109/MSP.2017.3151345.
