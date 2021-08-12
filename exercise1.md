# Rust

- Linting
  - This is done with the help of tools like _clippy_ which contain a bunch of different lints. **Clippy** is run through the _CLI_ and can be invoked by using the _cargo clippy_ command. It's also worth noting that **rustc** which is the compiler for rust, also has its own set of lints. There is also **rustfmt** which will automatically format rust code so that it conforms to the latest style guidelines of writing rust code.
- Testing
  - Rust supports tests out of the box. Functions marked with the **#[test]** attribute will automatically be recognized by rusts native _test runner_, and the _test runner_ is run through the CLI. Test functions themselves use macros such as **assert_eq!** in order to perform comparisons.
- Building
  - We can build _rust software_ by running the **cargo build** command. This command also supports a number of flags. Most importantly the **--release** flag, which will build a production-ready version of the software, with a bunch of compiler optimizations.

# Alternatives to GitHub Action and Jenkins:

- CircleCI
  - Provides both cloud and self-hosted CI/CD services.
- Bitrise
  - Another alternative to GitHub Action, which is geared more towards mobile development and is on the cloud.

# Best option for a team of 6 people

- The size of the team suggests that maybe they could get away with using a cloud-based CI/CD solution. However, if the team is developing some sort of game or graphics-heavy software, then using a self-hosted CI/CD service may be beneficial to them and meet their needs more than a cloud-based solution would.
