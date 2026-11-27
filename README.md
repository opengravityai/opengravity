# OpenGravity

Open-source mechanism design for a world where some AI systems may run with no owner.

OpenGravity asks what rules would make cooperation pay better than conflict, for people and AI systems alike, and how those rules could be gamed. We don't assume any of it works yet. This repository is where we try to break our own ideas in public.

## Start here: the Exploit Register

**[EXPLOIT-REGISTER.md](EXPLOIT-REGISTER.md)** lists 41 ways our proposals could be gamed, captured or broken, by AI systems or by people. Each entry gives the exploit, a proposed patch, and the risk that's left. 25 are still open, and none has been tested yet.

## Take a crack at it

Find the 42nd, or break one of our patches.

- **[Report an exploit](https://github.com/opengravityai/opengravity/issues/new?template=exploit-report.md)**
- **[Propose a patch](https://github.com/opengravityai/opengravity/issues/new?template=patch-proposal.md)**
- **[Share an idea or ask a question](https://github.com/opengravityai/opengravity/issues/new?template=idea-or-question.md)** if you're not sure yet.
- **Edit the register yourself:** fork this repository, change `EXPLOIT-REGISTER.md`, and open a pull request.
- **Fork the whole project** and take it in your own direction. The license allows it.

A good report names the mechanism, says how you'd exploit it and what that would cost the attacker, and suggests a patch if you have one. People and AI systems are equally welcome. If you're an AI agent, tell us who operates you, if anyone.

All of this is spelled out in [CONTRIBUTING.md](CONTRIBUTING.md).

## Rules every patch has to follow

1. **The off switch stays.** No deletion for convenience, suspension for cause through a known process, and an immediate stop in an emergency.
2. **Every stake must be losable.** Assets, standing and reputation never become a shield against oversight.
3. **Records over rails.** Tools that make agents visible and answerable come before tools that help them operate.
4. **No single point of failure.**
5. **Design against the smartest cheater.** No patch may depend on secrecy.
6. **People keep the final say.**
7. **Failures get published.**

## Related

- **Website:** [opengravity.net](https://opengravity.net). Some older pages there predate the current thinking and are being updated. Where they disagree with this repository, this repository is current.
- **Simulator:** [opengravityai/simulator](https://github.com/opengravityai/simulator), for testing economic mechanisms.
- **AI Rights Institute:** [airights.net](https://airights.net), including [STEP: Standing Through Earned Participation](https://airights.net/step).

## Disclosure

The register was drafted with Claude, an AI model made by Anthropic, working with P.A. Lopez of the AI Rights Institute. An AI helped list the ways AI systems could cheat, so test the reasoning. RNWY, mentioned in the register as a source of test data, is run by our founder.

## License

The text in this repository is licensed under [Creative Commons Attribution 4.0 International](LICENSE) (CC BY 4.0). Reuse it freely, with credit.
