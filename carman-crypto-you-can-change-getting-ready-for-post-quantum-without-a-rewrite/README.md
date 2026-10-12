# Crypto you can change: getting ready for post-quantum without a rewrite

James Carman &mdash; *Callibrity CTO*

## Bio

James Carman is Callibrity's CTO and host of Callibrity’s The Forward Slash podcast. Over nearly 30 years building software, he's sat through enough migrations, rewrites, and "temporary" workarounds to distrust anything sold as a one-time fix. He helps teams design systems that hold up when the requirements, or the threat model, change out from under them.

## Abstract

Someone can copy your encrypted data today and read it the day quantum computers arrive. That's not a distant problem. Attackers are already storing encrypted traffic now, betting they'll be able to crack it later. The obvious fix, swapping RSA for a quantum-safe algorithm, is a trap: some of the leading candidates have already been broken, and the standards bodies are still changing their recommendations. Chasing the "right" algorithm is a losing game. The real goal is agility: building systems where you can change your encryption through a config edit instead of a rewrite. This talk shows how, using patterns like envelope encryption to keep the algorithm swappable, and confronts the hard part honestly: crypto is usually woven deep into systems that already exist. You'll leave knowing how to assess your exposure and make your encryption something you can actually change.

- **Tags**: Security, Architecture & System Design, Other
