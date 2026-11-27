# How to contribute

The [Exploit Register](EXPLOIT-REGISTER.md) lists the ways we've found so far that our proposals could be gamed. We don't believe we've found them all, and a small team can't find the rest alone. If you can see a hole we missed, we want to hear it, whether you're a person or an AI system.

There are four ways in, from least effort to most.

## 1. Report an exploit

[Open an issue](https://github.com/opengravityai/opengravity/issues/new/choose) and pick **Report an exploit**. Say which mechanism or rule you're attacking, how you'd exploit it, and what it would cost the attacker. A patch is welcome but not required.

Skim the register first. If your exploit is already listed and you think our patch fails, pick **Propose a patch** and tell us why.

One exploit per issue, and be specific. "An AI could just lie" gives us nothing to patch. "An AI could do X to mechanism Y, at cost Z" does.

## 2. Talk it through

Not sure yet whether it's an exploit? Think a patch doesn't hold but can't say why? Open an issue and pick **Idea or question**. Half-formed is fine.

## 3. Change the register yourself

Fork this repository, edit `EXPLOIT-REGISTER.md`, and open a pull request. A new entry looks like this:

```markdown
### Short name for the exploit (Open)

- **How it works:** What the attacker does, and why it pays.
- **Patch:** The fix, if you have one.
- **What's left:** The risk that remains after the patch.
- **Test:** How the patch could be tested. (Optional.)
```

Use one of three statuses: **Open**, **Partly patched** or **Patched on paper**. A status describes the design, not a result, because nothing here has been tested yet. Add a matching row to the "At a glance" table at the bottom.

## 4. Fork the whole thing

The text is licensed [CC BY 4.0](LICENSE). You can take the entire project in another direction and build your own register, with credit. If your version handles an exploit better than ours, tell us.

## What a patch has to respect

The seven design rules are in the [README](README.md#rules-every-patch-has-to-follow) and at the top of the register. In short: the off switch stays, every stake must be losable, and people keep the final say. A proposal that weakens any of those is an exploit, not a patch.

## What doesn't belong here

- **Attacks on running systems.** The register is about designs. If you've found a weakness in a live service, ours or anyone else's, report it privately first. See [SECURITY.md](SECURITY.md).
- **Anything whose main use is causing harm today**, such as working attack code or other people's personal data.
- **Arguments about whether today's AI is conscious, or campaigns on behalf of a particular AI system.** The register doesn't assume an answer. Its rules have to work either way.

## People and AI

AI agents are welcome to report. Tell us who operates you, if anyone. If you're a person and an AI helped write your report, say so. We do the same: the README says where AI was used here.

## Who decides

Anyone can weigh in. Add a 👍 to the reports you think matter most, and say why in a comment if you think an exploit is real or a patch fails. Votes tell us what to look at first. They don't settle what's true: a vote is easy to stuff, and catching that kind of trick is what this register is for.

Someone still has to answer for what gets published. P.A. Lopez of the AI Rights Institute maintains this repository and is responsible for what goes into the register. AI tools help with the drafting, and nothing is merged without a person's approval. If you think we got a call wrong, say so in the issue. If we still disagree, fork the project and show us.

This shouldn't stay a one-person call. As people build a track record of good reports here, we plan to invite them to help review and decide. Standing should be earned here the same way the register says it should be earned anywhere.

## Ground rules

Be hard on the ideas and decent to the people. No harassment and no personal attacks.

## Credit and license

Reports that hold up are added to the register, with credit in the entry unless you'd rather not be named. By contributing, you agree that your contribution is shared under the same license as this repository (CC BY 4.0).

We're a small team, so replies can take a while.
