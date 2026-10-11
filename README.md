# Artur Panek

I build software, electronics and infrastructure. Usually the interesting part is where they meet.

## Public work

- [RuntimeTruth](https://artur.panek.tech/work/runtimetruth/) — compares Codex runtime settings, permissions and instruction files with a reviewed baseline. It can also verify signed baselines. [Source](https://github.com/sidelobe-labs/runtimetruth) · [PyPI](https://pypi.org/project/runtimetruth/)
- [PowerContract](https://github.com/sidelobe-labs/powercontract) — checks oscilloscope CSV captures against electrical limits and timing requirements written in YAML. [PyPI](https://pypi.org/project/powercontract/)
- [HA Blast Radius](https://artur.panek.tech/work/ha-blast-radius/) — finds Home Assistant entity references before a rename or removal. [Source](https://github.com/artur-panek/ha-blast-radius)
- [HA Forensic Lab](https://artur.panek.tech/work/ha-forensic-lab/) — records Home Assistant events and saves incident timelines for debugging. [Source](https://github.com/artur-panek/ha-forensic-lab)
- [MailForensics](https://artur.panek.tech/work/mailforensics/) — traces outbound email through application logs, Postfix, filters and relays. [Source](https://github.com/artur-panek/mailforensics) · [PyPI](https://pypi.org/project/mailforensics/)
- [route-explain](https://artur.panek.tech/work/route-explain/) — shows which route Linux selects for a flow and the rules and tables involved. [Source](https://github.com/artur-panek/route-explain) · [PyPI](https://pypi.org/project/route-explain/)

RuntimeTruth and PowerContract are published under [Sidelobe](https://github.com/sidelobe-labs).

## Engineering notes

- [AI agent configuration at runtime](https://artur.panek.tech/notes/ai-agent-config-vs-runtime/) — how to check the settings Codex actually resolves, not just what a config file says.
- [Debugging Linux policy routing](https://artur.panek.tech/notes/linux-routing-kernel-evidence/) — start with a kernel route lookup, then inspect the rules and tables behind it.
- [Home Assistant dependencies and state changes](https://artur.panek.tech/notes/home-assistant-static-vs-runtime/) — why finding configuration references and tracing an event are separate jobs.
- [What Postfix `status=sent` means](https://artur.panek.tech/notes/postfix-status-sent/) — why acceptance by a relay is not proof of inbox delivery.

[Portfolio](https://artur.panek.tech/) · [Engineering notes](https://artur.panek.tech/notes/) · [LinkedIn](https://www.linkedin.com/in/artur-panek-pl/) · [Sidelobe](https://sidelobe.dev/)
