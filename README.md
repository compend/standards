# Compend's Standards

This repository maintains programming standards for a variety of programming
languages, environments, and formats.

These standards are used directly by all [Compend projects][compend-org], by
other projects that want lightweight standards enforcement, and to be a template
for other organizations to base their own standards from.

## Principles

Generally, we try to adhere to the following principles when defining and
updating our coding standards:

1. **Auto-fixable**: We strongly prefer standards that can be automatically
   enforced and fixed by tooling rather than require manual human effort.

   _We want to minimize the cognitive overhead of memorizing particular style
   rules._

2. **Educational**: When documenting our standards, we strive to explain _why_ a
   particular standard is important. Additionally, for standards that are
   automatically enforced, we provide guidance on how to update code to adhere
   to it.

   _Without documenting the rationale behind a standard, we will struggle to
   revisit standards that may no longer make sense._

3. **Honor community norms**: For languages and environments where there are
   strong community standards, we prefer them.

   _This allows our code to be more familiar to developers outside of the
   Lintpipe community, and leverages each community's own knowledge of best
   practices._

4. **Readability**: Code should be quick to visually scan, minimize the amount
   of contextual code needed to understand a particular statement, avoid
   misleading formatting, etc.

   _We assume that our code will be frequently read by novices to our projects
   and/or chosen languages – as well as forgotten by ourselves promptly after
   writing it. Thus, it should be easy to jump back into._

## Table of Contents

* [Common](./common)
* [Markdown](./markdown)
* [Rust](./rust)
* [TypeScript](./typescript)
* [Standards](./standards)

## License

This repository is licensed under the [Blue Oak Model License](./LICENSE.md).

[compend-org]: https://github.com/compend
