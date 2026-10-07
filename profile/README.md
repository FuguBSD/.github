# FuguBSD

FuguBSD makes small tools in two areas: language models with agents for
OpenBSD, and air-gapped tools that keep a secret safe.

[FuguTTX](https://github.com/FuguBSD/FuguTTX) is a small language model and
agent for OpenBSD system administration. It runs on the CPU of a small machine,
with no network. [FuguVM](https://github.com/FuguBSD/FuguVM) gives an agent a
real OpenBSD guest, and [FuguBench](https://github.com/FuguBSD/FuguBench) gives
it a workspace.

[FuguSeed](https://github.com/FuguBSD/FuguSeed) makes a seed phrase with dice on
paper. [FuguPass](https://github.com/FuguBSD/FuguPass) turns that seed phrase
into a password manager, and [FuguOracle](https://github.com/FuguBSD/FuguOracle)
guards each entry behind a PIN.

Each tool does one task, and states its design in a specification. The code
follows the OpenBSD model, under the ISC license. Each project keeps its own
website, and the index lives at [www.fugubsd.org](https://www.fugubsd.org/).
