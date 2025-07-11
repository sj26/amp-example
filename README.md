# Amp Example

[![Build status](https://badge.buildkite.com/7d027dc1ac92002987045c6388d02ae5cc3e54ae1099592ccf.svg?branch=main)](https://buildkite.com/sj26/amp-example)

Run [Amp](https://ampcode.com) in a Buildkite pipeline.

Uses [amp-buildkite-plugin](https://github.com/sj26/amp-buildkite-plugin), a light wrapper for prompting amp.

```yaml
steps:
  - plugins:
      sj26/amp:
        prompt: |
          Tell me a story.
```

<a href="https://buildkite.com/sj26/amp-example/builds/latest?branch=main"><img width="1496" alt="Screenshot of Amp running in Buildkite, telling a story" src=".buildkite/screenshot.png" /></a>
