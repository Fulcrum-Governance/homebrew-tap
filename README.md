# Fulcrum Boundary Homebrew Tap

Homebrew packages for [Fulcrum Boundary](https://github.com/Fulcrum-Governance/Fulcrum-Boundary), the pre-execution action boundary for routed AI-agent tool calls.

```bash
brew install fulcrum-governance/tap/boundary
```

Boundary v0.12.0 and later are published as `Casks/boundary.rb` by the Boundary
release pipeline. The legacy `Formula/boundary.rb` package was retired before
the first cask release. The cask installs the static (`CGO_ENABLED=0`) build;
see its caveats for what that build does and does not include.
