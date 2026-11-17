# token-launch-radar

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/mytlyy0745/token-launch-radar/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/mytlyy0745/token-launch-radar/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token Radar — a pre-token protocol radar. It reads a sealed DefiLlama snapshot of 758 protocols, calibrates each category's FDV/TVL multiple from the live-token protocols in the same snapshot, and ranks all 198 pre-token protocols by the implied value a launch would be worth, each with a seven-step farm plan. The dashboard shows the ranked board, a detail view for every protocol with the model's own breakdown, a live-token view set aside with market caps, and the full model with every category's comparables.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input snapshot.json
node serve.mjs out
# then open http://localhost:8080/dashboard/
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=75k23xv8&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>
