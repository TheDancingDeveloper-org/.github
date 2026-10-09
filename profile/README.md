# TheDancingDeveloper

Independent software, built in public: self-hosted services, peer-to-peer
systems, media automation and developer tools. Practical problems, clean and
maintainable code, and open formats over unnecessary complexity.

🌐 [thedancingdeveloper.com](https://thedancingdeveloper.com/) ·
💼 [LinkedIn](https://www.linkedin.com/in/sprooty/) ·
✉️ dancingdeveloper@proton.me

## Featured projects

| Project | What it is | Links |
|---|---|---|
| **[Vogt](https://github.com/TheDancingDeveloper-org/vogt)** | Self-hosted product development environment for teams and the coding agents that work with them: projects, work items, repository state, agent terminals and an MCP server in one place. | [Live demo](https://vogt-demo.thedancingdeveloper.com/) · [Releases](https://github.com/TheDancingDeveloper-org/vogt/releases) |
| **[voicepipe](https://github.com/TheDancingDeveloper-org/voicepipe)** | Rust pipeline for live, turn-taking voice calls with a language model: VAD, endpointing, barge-in, sentence-streamed speech. Bring your own STT, TTS and model. | [crates.io](https://crates.io/crates/voicepipe) · [docs.rs](https://docs.rs/voicepipe) |
| **[rustnzb](https://github.com/TheDancingDeveloper-org/rustnzb)** | Usenet binary downloader in Rust, a drop-in replacement for SABnzbd. | [rustnzb.dev](https://rustnzb.dev/) · [crates](https://crates.io/crates/nzb-core) |
| **[rustTorrent](https://github.com/TheDancingDeveloper-org/rustTorrent)** | Lightweight, self-hosted BitTorrent client in Rust with a web UI and qBittorrent-compatible API. | [rusttorrent.dev](https://rusttorrent.dev/) · [crates](https://crates.io/crates/swarmforge) |
| **[Indexarr](https://github.com/TheDancingDeveloper-org/indexarr-rs)** | Decentralized torrent indexer: DHT crawling, content classification and signed peer-to-peer index sharing, with a Torznab API. | [indexarr.net](https://indexarr.net/) |
| **[FuelWatchX](https://fuelwatch.sprooty.com/)** | Independent NSW fuel-price monitoring and analysis. | [fuelwatch.sprooty.com](https://fuelwatch.sprooty.com/) |

## Libraries and tools

- **Usenet engine crates** — [`nzb-core`](https://crates.io/crates/nzb-core),
  [`nzb-nntp`](https://crates.io/crates/nzb-nntp),
  [`nzb-news`](https://crates.io/crates/nzb-news),
  [`nzb-web`](https://crates.io/crates/nzb-web) and the
  [`nzbdav-*`](https://crates.io/crates/nzbdav-core) family, plus
  [`rust-par2`](https://crates.io/crates/rust-par2) (PAR2 verify/repair) and
  [`yenc-simd`](https://crates.io/crates/yenc-simd) (SIMD yEnc decoding).
- **BitTorrent crates** — [`swarmforge`](https://crates.io/crates/swarmforge)
  and its `swarmforge-*` components (DHT, peer protocol, trackers, UPnP).
- **[Egressy](https://github.com/TheDancingDeveloper-org/egressy)** —
  transparent Layer-3 VPN gateway for Docker containers.
- **[Cadastre](https://github.com/TheDancingDeveloper-org/cadastre)** —
  infrastructure knowledge catalogue and MCP broker for homelabs and agents.

Licences are per repository. Issues and pull requests are welcome on each
project.
