# rust-wk-1

## Rust Week 1 - Assignment 2

GitHub CoPilot can be arbitrarily specific (up to some bound that I'm too lazy to get to). I asked the hello world example to not only build the function, but also make sure two println!s were used and that world was followed by "a lot" of exclamation marks. Of Course CoPilot doesn't know what a lot is and waits for you to terminate the line or continue adding exclamation marks to fulfill a lot.

## Rust Week 1 - Assignment 3

### Tasks and learnings
- Added `devcontainer.json`
- Specified rust image version in `devcontainer.json` (Can update later to increment version)
- Some special things about `devcontainer.json` is you can not only specify a locally developed Dockerfile, but also aspects that you want as default to start from. I chose CoPilot non-nightly, to create more uniformity. 

### Usage
- Clone repository if you want this locally
- Open repository/directory in VS Code
- Click the `><` icon in the bottom left and build and run as a dev container
- You can edit the `devcontainer.json` to change images, use a locally built Dockerfile, add more settings and defaults to VS Code, etc.