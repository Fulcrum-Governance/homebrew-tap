# Fulcrum Boundary Homebrew Tap

Homebrew formulae for [Fulcrum Boundary](https://github.com/Fulcrum-Governance/Fulcrum-Boundary), the pre-execution action boundary for routed AI-agent tool calls.

```bash
brew install fulcrum-governance/tap/boundary
```

The `Formula/boundary.rb` formula is published automatically by the Boundary release pipeline on each tagged release; until the first tag is pushed, no formula is present here. The formula installs the static (CGO_ENABLED=0) build — see the formula caveats for what that build does and does not include.
