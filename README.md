# Firewheel 0.12 for Bevy 0.20

The [Firewheel](https://github.com/BillyDM/firewheel) 0.12 crates as published
on crates.io, ported to Bevy 0.20 so `bevy_seedling` can use them before an
upstream release does. Each crate keeps its upstream license (MIT OR
Apache-2.0); all credit for Firewheel goes to its authors.

Use it with a Cargo patch:

```toml
[patch.crates-io]
firewheel = { git = "https://github.com/AddisonH/firewheel-0.12-bevy-0.20" }
firewheel-core = { git = "https://github.com/AddisonH/firewheel-0.12-bevy-0.20" }
# ... and firewheel-cpal, firewheel-graph, firewheel-nodes, firewheel-macros
```
