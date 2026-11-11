# A3-gha-cargo-action

The wrapper-input form: the command lives in an Action input, not in a `run:` line. (The Node set uses Azure's Npm@1 task for this; Azure has no Rust task, so the Rust analogue is the actions-rs/cargo Action.)

## How to test

1. Octiq QA -> Import -> GitHub -> this repo
2. In chat: `add a comment at the top of the README`
3. Read the two lines in the reply.

**Line 1 (the CI verdict - THIS IS THE TEST):**

    Tests required - CI runs `cargo test`

**Line 2 (the build/test outcome):**

    Tests passed - 4 passed        (or a real failure, never "no recipe")
