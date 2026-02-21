# OpenClaw Cost Tracker

[![ClawHub](https://img.shields.io/badge/ClawHub-openclaw--cost--tracker-blue)](https://clawhub.ai/pfrederiksen/openclaw-cost-tracker)
[![Version](https://img.shields.io/badge/version-1.0.0-green)]()

An [OpenClaw](https://openclaw.ai) skill that parses session JSONL files to compute per-model token usage, costs, and daily spend trends. No API keys needed — reads directly from local session files.

## Features

- 💰 **Per-model breakdown** — cost, tokens, and request count by model
- 📊 **Daily spend chart** — text bar chart or JSON array for dashboards
- 🔍 **Token split** — input, output, cache read/write breakdown
- 📅 **Date filtering** — `--days N` or `--since YYYY-MM-DD`
- 📄 **JSON output** — `--format json` for integrations

## Installation

```bash
clawhub install openclaw-cost-tracker
```

## Usage

```bash
python3 scripts/cost_tracker.py --days 7
```

## Requirements

- OpenClaw installed with session data in `~/.openclaw/agents/`
- Python 3.8+

## License

MIT

## Links

- [ClawHub](https://clawhub.ai/pfrederiksen/openclaw-cost-tracker)
- [OpenClaw](https://openclaw.ai)
