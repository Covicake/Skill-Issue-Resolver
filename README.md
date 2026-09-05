# Skill-Issue-Resolver

> Instantly diagnoses your loss as a skill issue, so you don't have to ask.

A lightweight, dependency-free, zero-config diagnostic tool for competitive
gaming. Feed it your excuse, and it will get to the bottom of things —
which is, statistically, you.

## Features

- **Instant diagnosis.** No loading screens, no "analyzing replay," no
  waiting for the tribunal. Verdict in milliseconds.
- **State-of-the-art excuse rejection.** Detects common cope keywords
  (`lag`, `ping`, `smurf`, `controller`, `unlucky`, and more) and rebuts
  each one individually.
- **100% offline.** Your shame never leaves your machine.
- **No false positives.** It has never once been wrong.

## Installation

```bash
git clone https://github.com/Covicake/Skill-Issue-Resolver.git
cd Skill-Issue-Resolver
chmod +x skill-issue
```

No dependencies. No build step. No excuses.

## Usage

Pass your excuse as an argument:

```bash
./skill-issue "the game lagged"
```

```
Skill issue.
Excuse "the game lagged" rejected: the only thing lagging was your aim.
```

Try another one:

```bash
./skill-issue "my controller is broken"
```

```
100% skill issue, 0% lag.
Excuse "my controller is broken" rejected: the controller isn't the one missing shots.
```

Not sure what your excuse even is? Run it with no arguments for a quick,
context-free verdict:

```bash
./skill-issue
```

```
Skill issue.
```

For convenience, alias it so it's always one command away from the truth:

```bash
alias L='~/projects/Skill-Issue-Resolver/skill-issue'
```

## FAQ

**Q: I lost because of lag/my team/a smurf/a hacker. Can this be fixed?**
A: No.

**Q: Can I configure it to sometimes not say "skill issue"?**
A: No.

**Q: Is this scientifically validated?**
A: It has a 100% agreement rate with everyone who beat you.

**Q: Will this hurt my feelings?**
A: Yes. That's the product.

## Contributing

PRs adding new excuse keywords are welcome. PRs disputing the verdict will
be closed as a skill issue.

## License

MIT. Your losses, however, remain entirely your own.
