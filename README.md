# Helikon Polkadot Governance Archive

An [mdbook](https://github.com/rust-lang/mdBook) micro-site that documents the Polkadot OpenGov voting activity of [kukabi](https://github.com/kukabi),
the founder of [Helikon](https://helikon.io), as delegated by the [W3F](https://web3.foundation) as part of the [Decentralized Voices](https://medium.com/web3foundation/decentralized-voices-round-1-candidates-announced-23d9a800b260) (DV) program.

## Run

Assuming you have Rust [installed](https://www.rust-lang.org/tools/install):

```
cargo install mdbook
cargo install mdbook-external-links
cargo install mdbook-last-changed
git clone https://github.com/helikon-labs/helikon-gov-archive.git
cd helikon-gov-archive
mdbook serve --open
```