# DevOS

An Ubuntu-based, developer-focused Linux distribution designed to reduce friction in everyday development workflows.

## What is DevOS?

DevOS is a developer-oriented Linux distribution built on top of Ubuntu. It focuses on providing a curated development environment while reducing the friction of configuring tools, workflows, and system utilities manually.
Instead, the project focuses on integrating existing technologies into a simpler, more cohesive developer workflow.

> Do not reinvent what already works. Reduce friction where it actually matters.

## Project Rollback

DevOS includes a CLI-based project snapshot and rollback system.

Developers can create named checkpoints of their project, inspect available snapshots, restore previous states, and remove snapshots they no longer need.

```bash
devos setroll "before dependency upgrade"
devos rollist
devos rollback 3
devos delicious 3
