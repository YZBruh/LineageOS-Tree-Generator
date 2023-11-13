# Auto LineageOS Tree Generator
It allows you to create a LineageOS compatible device tree with GitHub actions and the ROM dump you have previously created. It uses AOSPDTGEN when creating the tree.

## Requirements
- ROM dump
- GitHub token (I will explain)
- Small device information (for repository creation and naming).

## Instruction for use
- Fork this repository.
- Get your 'Personal access token' in Account Settings > Developer settings > Personal access token. Check all the boxes and use classic tokens.
- Then go to repository Settings > Secrets and Variables > Action > New repository secret; create new secret. Write the following in the name section: In the 'LOS' description section; Paste your `Personal access token`. And save it.
- Action > All workflows > Extract Blobs > Run workflows > Fill in all requested information > And run.

## Notes
- All partitions should be present in the ROM dump. Otherwise it won't work.
- Report bugs.
- Perform operations carefully. Especially `token` transactions.
