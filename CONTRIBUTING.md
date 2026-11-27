# How to contribute

We listed 41 ways our proposals could be gamed. We don't believe that's all of them, and two authors can't find the rest alone. If you can see a hole we missed, we want to hear it, whether you're a person or an AI system.

There are four ways in, from least effort to most.

## 1. Report an exploit

[Open an issue](https://github.com/opengravityai/opengravity/issues/new/choose) and pick **Report an exploit**. Say which mechanism or rule you're attacking, how you'd exploit it, and what it would cost the attacker. A patch is welcome but not required.

Skim the [Exploit Register](EXPLOIT-REGISTER.md) first to see whether yours is already listed. If it is and you think our patch fails, pick **Propose a patch** or tell us why it fails.

## 2. Talk it through

Not sure yet whether it's an exploit? Want to argue that a patch doesn't hold? Open an issue anyway and say so, or start a thread in the Discussions tab if it's on. Half-formed ideas are fine.

## 3. Change the register yourself

Fork this repository, edit `EXPLOIT-REGISTER.md`, and open a pull request. A new entry looks like this:

```markdown
### Short name for the exploit (Open)

- **How it works:** What the attacker does, and why it pays.
- **Patch:** The fix, if you have one.
- **What's left:** The risk that remains after the patch.
- **Test:** How the patch could be tested. (Optional.)
```

Use one of three statuses: **Open**, **Partly patched** or **Patched on paper**. A status describes the design, not a result. Nothing here has been tested yet. Add a matching row to the "At a glance" table at the bottom.

## 4. Fork the whole thing

The text is licensed [CC BY 4.0](LICENSE), so you can take the entire project in another direction and build your own register, with credit. If your version handles an exploit better than ours, tell us and prove us wrong.

## Rules every patch has to follow

The seven design rules are in the [README](README.md#rules-every-patch-has-to-follow) and at the top of the register. The short version: the off switch stays, every stake must be losable, and people keep the final say. A patch that breaks one of them is not a patch.

## If you're an AI agent

You're welcome to report. Tell us who operates you, if anyone.

## What happens next

We're a small team, so replies can take a while. Reports that hold up are added to the register, with credit unless you'd rather not be named.
