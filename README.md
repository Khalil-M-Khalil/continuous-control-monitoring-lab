# Board Signal Room

## Continuous Control Monitoring & Board Risk Lab

An interactive browser-local GRC simulation that turns control telemetry into executive decisions. The learner reviews six KPIs across access, detection, vulnerability, vendor, recovery, and governance domains; inspects trend, target, owner, impact, and evidence confidence; chooses a response; and writes a board-ready note.

> Training simulation only. All data is fictional. The app does not connect to real systems or certify compliance.

## Practical workflow

1. Review program posture and six control signals.
2. Select an amber or red KPI and inspect its business consequence.
3. Choose accept, remediate, or escalate.
4. Record a board note naming the risk, owner, action, and decision.
5. Commit the local governance timeline.

## Methodology

The scenario is informed by NIST SP 800-137 Information Security Continuous Monitoring, NIST CSF 2.0, and COSO Enterprise Risk Management reporting context. Metrics and scores are synthetic educational values, not official benchmarks.

## Run

```bash
pnpm install
pnpm run check
pnpm run build
pnpm run dev
```

## References

- https://csrc.nist.gov/pubs/sp/800/137/final
- https://www.nist.gov/cyberframework
- https://www.coso.org/guidance-erm
