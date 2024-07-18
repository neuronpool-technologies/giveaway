`Giveaway()`

Provides a signup bonus in ICP to new stakers.

## Overview of the tech stack

- [Motoko](https://react.dev/](https://internetcomputer.org/docs/current/motoko/main/motoko?source=nav)) is used for the smart contract programming language.
- The IC SDK: [DFX](https://internetcomputer.org/docs/current/developer-docs/setup/install) is used to make this an ICP project.

### If you want to clone onto your local machine

Make sure you have `git` and `dfx` installed
```bash
# clone the repo
git clone #<get the repo ssh>

# change directory
cd giveaway

# set up the dfx local server
dfx start --background --clean

# deploy the canister locally
dfx deploy

# ....
# when you are done make sure to stop the local server:
dfx stop
```

## License

The `Giveaway()` code is distributed under the terms of the MIT License.

See LICENSE for details.