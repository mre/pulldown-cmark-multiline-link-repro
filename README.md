# pulldown-cmark Link issue repro

pulldown-cmark doesn't seem to handle multiline links correctly.

To reproduce the error, run

```sh
cat test.md | cargo run
```

This shows that multiline links don't get detected right now.
