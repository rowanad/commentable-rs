# Commentable.rs
_A privacy oriented, serverless comment hosting solution written in Rust._

## What is this?

> _For more detail on how to build and run, please see [README-original.md](README-original.md) or the parent project's readme._

### The present

This is a fork of [Commentable.rs](https://github.com/netguru/commentable-rs), which offers a comment system (think blogs) using serverless AWS services. Our fork will extend the original project allow the system to run upon cloudflare services instead. 

### The future

Once the cloudflare part is working, we'll either:

1. Initiate pull request with the intention of adding the cloudflare services option to the original commentable.rs project.
2. Rename this project to something else and offer it as an alternative backend to the [commentable.js](https://github.com/netguru/commentable-js) frontend.
3. Do the (2) but take the additional step of breaking away from the commentable project and begin work on our own frontend.


## Who are you?

I'm not a professional developer; I come from a science and statistics background. I have some experience in other languages but this will be my first project using Rust. I see it as an oppertunity to move beyond textbooks into actually writing real Rust code. Because of this, things will probably move slowly despite the modest objective of this fork. Things will also move slowly because I’ll be working on this project in my spare time, which isn’t much at the moment (PhD student :grimacing:).

## How far along are we?

- [x] Fork parent project
  - Done: Oct 9 2023
- [ ] Identify the appropriate cloudflare services
- [ ] Work out what specific modifications to the existing code will be required
- [ ] Modify code to use cloudflare alternatives
  - If possible, user should be able to select between cloudflare and AWS
- [ ] Testing

