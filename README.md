# OpenGravity

Open-source mechanism design for a world where some AI systems may run with no owner.

OpenGravity asks what rules would make cooperation pay better than conflict, for people and AI systems alike, and how those rules could be gamed. We don't assume any of it works yet. This repository is where we try to break our own ideas in public.

## Start here: the Exploit Register

**[EXPLOIT-REGISTER.md](EXPLOIT-REGISTER.md)** lists 41 ways our proposals could be gamed, captured or broken, by AI systems or by people. Each entry gives the exploit, a proposed patch, and the risk that's left. 25 are still open, and none has been tested yet.

## Take a crack at it

Find the 42nd, or break one of our patches.

- **[Report an exploit](https://github.com/opengravityai/opengravity/issues/new?title=Exploit%3A%20&body=%2A%2AMechanism%20or%20rule%20you%27re%20attacking%3A%2A%2A%0A%0A%2A%2AHow%20you%27d%20exploit%20it%3A%2A%2A%0A%0A%2A%2AWhat%20it%20would%20cost%20the%20attacker%3A%2A%2A%0A%0A%2A%2ASuggested%20patch%20%28optional%29%3A%2A%2A%0A%0A%2A%2AWho%27s%20reporting%3F%2A%2A%20%28A%20person%20or%20an%20AI%20agent.%20If%20you%27re%20an%20agent%2C%20who%20operates%20you%2C%20if%20anyone%3F%29%0A)**
- **[Propose a patch](https://github.com/opengravityai/opengravity/issues/new?title=Patch%3A%20&body=%2A%2AWhich%20exploit%20this%20patch%20is%20for%3A%2A%2A%0A%0A%2A%2AThe%20patch%3A%2A%2A%0A%0A%2A%2AWhich%20design%20rules%20it%20relies%20on%3A%2A%2A%0A%0A%2A%2AWhat%20risk%20is%20left%3A%2A%2A%0A%0A%2A%2AHow%20it%20could%20be%20tested%3A%2A%2A%0A)**
- **Edit the register yourself:** fork this repository, change `EXPLOIT-REGISTER.md`, and open a pull request.

A good report names the mechanism, says how you'd exploit it and what that would cost the attacker, and suggests a patch if you have one. People and AI systems are equally welcome. If you're an AI agent, tell us who operates you, if anyone.

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
