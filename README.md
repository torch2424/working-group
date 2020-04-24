![AssemblyScript Logo](https://avatars1.githubusercontent.com/u/28916798?s=64) AssemblyScript Working Group
=================

A repo for discussions, goals, roadmaps, assets, and other things related to the AssemblyScript project.

If you are looking for the AssemblyScript compiler, please see the [main AssemblyScript repo here](https://github.com/AssemblyScript/assemblyscript). Where you can also **find how to sponsor the project**.

# Table of Contents

* [Goals](#goals)
* [Governance](#governance)
  * [Technical Decisions](#technical-decisions)
  * [Organizational Decisions](#organizational-decisions)
* [Groups](#groups)
  * [Working Group](#working-group)
  * [Communitty Group](#communitty-group)
* [Teams](#teams)
  * [Compiler](#compiler)
  * [Advocate](#advocate)
  * [Developer Experience](#developer-experience)
* [Getting Involved](#getting-involved)

# Goals

The current goals of the AssemblyScript project are:

* Target feature parity with WebAssembly and related technology.

* Support non-browser use cases well (i.e. serverless, blockchain, etc...).

* Stay backwards-compatible to TypeScript syntax and JavaScript APIs as much as possible and reasonable.

* Complement current web projects, and support building WebAssembly modules "from scratch". By offering "fine-grain" control to developers.

* Focus on developer experience, and try to be a great language for new and existing web developers. 

# Governance

Following the [definitions described in opensource.guide](https://opensource.guide/leadership-and-governance/#what-are-some-of-the-common-governance-structures-for-open-source-projects). The Governance for the project is split into two parts:

## Technical Decisions

Technical Decisions can be interpreted as contributions being made to projects in the AssemblyScript Github Org.

For this, we will be following BDFL. Daniel Wirtz (@dcodeIO) is the designated lead. Thus, in the case there is conflict between contributors, the lead will be the one to make the final decision.

## Organizational Decisions

Organizational Descisions can be interpreted as contributions to the general project direction, goals, roadmap, maintainers, etc...

For this, we will be following a meritocracy. Where consensus will be requested on issues opened on this repo to get a community vote, and can find a path going forward.

# Groups

The AssemblyScript project has meetings and and correspondance divided into groups. These groups communicate and work together very closely, and provides a way for focused discussions for those who need that.

## Working Group

The working group is for those who would like to contribute to the project directly. Whether that be through getting advice on technical implementations, showing off a new tool they are building, or just generally talking about the AssemblyScript project and where it is headed.

**Anyone working on anything related to the AssemblyScript project is welcome to participate in the Working Group!**

## Communitty Group

The [community group](https://github.com/AssemblyScript/community-group) is for those who would like to discuss with other communitty members (including members of the working group) using AssemblyScript in their applications. The goal being that they can prioritize their core feature requests and use cases and communicate that to the working group. Which can help reduce duplicating efforts amongst the communitty, and allow the communitty to be collectively more productive!

# Teams

The AssemblyScript project members is divided into teams. The teams make design, architectural, and new-membership decisions for their relevant domains and repositories by consensus. If consensus can't be made, then the Compiler team (specifically @dcodeIO) may act as a tie-breaker. 

**Membership guidelines**:

* Anyone who is making significant contributions to the project (whether it be code, documentation, outreach, their own awesome project, etc...) is welcome to join the communitty and request to join a team! :)

* Membership does not require any required responsibilities outside of general activity in the communitty. The project is open source and contributions are made at one's own accord. So help when you can. If things get busy on a member's end, that is okay! We welcome back all awesome contributors back after a haitus.

* All members of a team must adhere to the [Code of Conduct](./CODE_OF_CONDUCT.md).

* Membership does not grant commit access to a repository. Commit access should be handled by the author of the repository, or by consensus of the respective team.

## Compiler

The "Compiler" team works on the AssemblyScript compiler and its standard library. Mostly, under the [AssemblyScript/assemblyscript](https://github.com/AssemblyScript/assemblyscript) repository.

**Daniel Wirtz**

![Daniel Wirtz Avatar](https://avatars0.githubusercontent.com/u/1136893?s=150&v=4)

Author/Creator of AssemblyScript.

[Github](https://github.com/dcodeIO) | [Website](https://dcode.io/)

**Max Graey**

![Max Graey Avatar](https://avatars0.githubusercontent.com/u/1301959?s=150&v=4)

[Github](https://github.com/MaxGraey) | [Twitter](https://twitter.com/MaxGraey)

**Bowen Wang**

[Github](https://github.com/bowenwang1996)

Notable Projects:

* Developer at [Near](https://nearprotocol.com/)

* [Smart Contract Library for AssemblyScript](https://github.com/nearprotocol/near-runtime-ts)

**Joshua Tenner**

[Github](https://github.com/jtenner)

**Duncan Uszkay** 

![Duncan Uszkay Avatar](https://avatars2.githubusercontent.com/u/8670351?s=150&v=4)

[Github](https://github.com/DuncanUszkay1)

Notable Projects:

* Developer at [Shopify](https://www.shopify.com/)

## Advocate

The "Advocate" team works on projects, demos, talks, giving feedback on "messaging" about the project, and writing articles to help grow popularity and improve outreach.

**Aaron Turner**

![Aaron Turner Avatar](https://avatars0.githubusercontent.com/u/1448289?s=150&v=4)

[Github](https://github.com/torch2424) | [Website](https://aaronthedev.com/)

Notable Projects: 

* [WasmBoy](https://github.com/torch2424/wasmboy)
* [VaporBoy](https://github.com/torch2424/vaporBoy)
* [Wasm Matrix](https://github.com/torch2424/wasm-matrix)
* [Wasm By Example](https://github.com/torch2424/wasm-by-example) 

Notable Talks:

* [WebAssembly for JavaScript developers](https://youtu.be/ZlL1nduatZQ)

Notable Articles:

* [Benchmark of WebAssembly vs ES6](https://medium.com/@torch2424/webassembly-is-fast-a-real-world-benchmark-of-webassembly-vs-es6-d85a23f8e193)

**Joshua Tenner**

[Github](https://github.com/jtenner)

Notable Projects:

* [as-pect](https://github.com/jtenner/as-pect)
* [as2d](https://github.com/as2d/as2d)

Notable Articles:

* [An AssemblyScript Primer for TypeScript Developers](https://dev.to/jtenner/an-assemblyscript-primer-for-typescript-developers-lf1)

**Willem Wyndham**

![Willem Wyndham Avatar](https://avatars0.githubusercontent.com/u/1483244?s=150&v=4)

[Github](https://github.com/willemneal)

Notable Projects:

* [AssemblyScript University Course](http://www.cs.umd.edu/class/spring2019/cmsc388I/assemblyscript.html)
* Contributor to [as-pect](https://github.com/jtenner/as-pect)

## Developer Experience

The "Developer Experience" team works on projects such as tools, or anything that helps people be productive with AssemblyScript.


**Joshua Tenner**

[Github](https://github.com/jtenner)

Notable Projects:

* [as-pect](https://github.com/jtenner/as-pect)
* [as2d](https://github.com/as2d/as2d)

Notable Articles:

* [An AssemblyScript Primer for TypeScript Developers](https://dev.to/jtenner/an-assemblyscript-primer-for-typescript-developers-lf1)

**Willem Wyndham**

![Willem Wyndham Avatar](https://avatars0.githubusercontent.com/u/1483244?s=150&v=4)

[Github](https://github.com/willemneal)

Notable Projects:

* [AssemblyScript University Course](http://www.cs.umd.edu/class/spring2019/cmsc388I/assemblyscript.html)
* Contributor to [as-pect](https://github.com/jtenner/as-pect)

**Bowen Wang**

[Github](https://github.com/bowenwang1996)

Notable Projects:

* Developer at [Near](https://nearprotocol.com/)

* [Smart Contract Library for AssemblyScript](https://github.com/nearprotocol/near-runtime-ts)

# Getting Involved

We're happy to help you get involved! Currently, there are a few things you could do to start getting involved with the working group:

* Reach out to a team member, and get invited to the AssemblyScript slack.

* Join one of our [upcoming public meetings](https://github.com/AssemblyScript/working-group/issues?q=is%3Aissue+is%3Aopen+public+meeting).

* Open an issue on the [working-group issues](https://github.com/AssemblyScript/working-group/issues), or any of the [AssemblyScript repositories](https://github.com/AssemblyScript).
