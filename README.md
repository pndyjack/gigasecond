# Gigasecond

Calculate the moment when someone has lived for 10^9 seconds.

A gigasecond is 10^9 (1,000,000,000) seconds.

If you're unsure what operations you can perform on `DateTime<Utc>` take a look at the [chrono crate](https://docs.rs/chrono/0.4.0/chrono/) which is listed as a dependency in the `Cargo.toml` file for this exercise.

## Writing the Code

Execute the tests with:

```bash
$ cargo test
```

All but the first test have been ignored. After you get the first test to
pass, open the tests source file which is located in the `tests` directory
and remove the `#[ignore]` flag from the next test and get the tests to pass
again. Each separate test is a function with `#[test]` flag above it.
Continue, until you pass every test.

If you wish to run all tests without editing the tests source file, use:

```bash
$ cargo test -- --ignored
```

To run a specific test, for example `some_test`, you can use:

```bash
$ cargo test some_test
```

If the specific test is ignored use:

```bash
$ cargo test some_test -- --ignored
```

## Source

Chapter 9 in Chris Pine's online Learn to Program tutorial. [http://pine.fm/LearnToProgram/?Chapter=09](http://pine.fm/LearnToProgram/?Chapter=09)
