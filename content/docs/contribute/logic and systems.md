+++
description = "How to contribute if you are a blueprinter or a C++ developer"
title = "Logic and Systems"
weight = 3
+++

Most of the Distributed Development project is built with Unreal's Blueprints visual scripting system. There are a few important guidelines to follow in order to keep the blueprints manageable and predictable, and not devolving into a mess of Blueprint Spaghetti.

{{< gallery "images/bpspaghet.png" "Blueprint Spaghetti" >}}

---
### Components
Try to limit per-blueprint logic as much as possible, unless a blueprint is unique. In case it is not unique, use Components.

---
### Collapsed Nodes
Collapse nodes into groups, instead of using large comment chains.

---
### C++
Shoot, we need a UE C++ expert on our team to actually doc this bit. <;^^

