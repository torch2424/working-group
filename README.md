![AssemblyScript Logo](https://avatars1.githubusercontent.com/u/28916798?s=64) AssemblyScript "meta"
=================

A repo for discussions, goals, roadmaps, assets, and other things related to the AssemblyScript project.

If this is not what you were looking for, please see the [main AssemblyScript repo here](https://github.com/AssemblyScript/assemblyscript). Where you can also find how to sponsor the project.

# Table of Contents

* [Goals](#goals)
* [Governance](#governance)
  * [Technical Decisions](#technical-decisions)
  * [Organizational Decisions](#organizational-decisions)
  * [Teams](#teams)
    * [Compiler](#compiler)
      * [Daniel Wirtz](#daniel-wirtz)
      * [Max Graey](#max-graey)
      * [Bowen Wang](#bowen-wang)
    * [Evangelism](#evangelism)
      * [Aaron Turner](#aaron-turner)
      * [Joshua Tenner](#joshua-tenner)
      * [Willem Wyndham](#willem-wyndham)
    * [Developer Experience](#developer-experience)
      * [Joshua Tenner](#joshua-tenner-1)
      * [Willem Wyndham](#willem-wyndham-1)
      * [Bowen Wang](#bowen-wang-1)

# Goals

The current goals of the AssemblyScript project are:

* Target feature parity with WebAssembly and related technology.

* Support non-browser use cases well (i.e. serverless, blockchain, etc...).

* Stay backwards-compatible to TypeScript syntax and JavaScript APIs as much as possible and reasonable.

* Compliment current web projects, and support building WebAssembly modules "from scratch". By offering "fine-grain" control to developers.

* Focus on developer experience, and try to be a great language for new and existing web developers. 

# Governance

Following the [definitions described in opensource.guide](https://opensource.guide/leadership-and-governance/#what-are-some-of-the-common-governance-structures-for-open-source-projects). The Governance for the project is split into two parts:

## Technical Decisions

Technical Decisions can be interpreted as contributions being made to projects in the AssemblyScript Github Org.

For this, we will be following BDFL. Daniel Wirtz (@dcodeIO) is the designated lead. Thus, in the case there is conflict between contributors, the lead will be the one to make the final decision.

## Organizational Decisions

Organizational Descisions can be interpreted as contributions to the general project direction, goals, roadmap, maintainers, etc...

For this, we will be following a meritocracy. Where consensus will be requested on issues opened on this repo to get a community vote, and can find a path going forward.

## Teams

The AssemblyScript project members is divided into teams. The teams make design, architectural, and new-membership decisions for their relevant domains and repositories by consensus. If consensus can't be made, then the Compiler team (specifically @dcodeIO) may act as a tie-breaker. 

**Membership guidelines**:

* Anyone who is making significant contributions to the project (whether it be code, documentation, outreach, their own awesome project, etc...) is welcome to join the communitty and request to join a team! :)

* Membership does not require any required responsibilities outside of general activity in the communitty. The project is open source and contributions are made at one's own accord. So help when you can. If things get busy on a member's end, that is okay! We welcome back all awesome contributors back after a haitus.

* All members of a team must adhere to the [Code of Conduct](./CODE_OF_CONDUCT.md).

* Membership does not grant commit access to a repository. Commit access should be handled by the author of the repository, or by consensus of the respective team.

### Compiler

The "Compiler" team works on the AssemblyScript compiler and its standard library. Mostly, under the [AssemblyScript/assemblyscript](https://github.com/AssemblyScript/assemblyscript) repository.

#### Daniel Wirtz

![Daniel Wirtz Avatar](https://avatars0.githubusercontent.com/u/1136893?s=150&v=4)

[Github](https://github.com/dcodeIO) | [Website](https://dcode.io/)

**Author/Creator of AssemblyScript.**

#### Max Graey

![Max Graey Avatar](https://avatars0.githubusercontent.com/u/1301959?s=150&v=4)

[Github](https://github.com/MaxGraey) | [Twitter](https://twitter.com/MaxGraey)

#### Bowen Wang

[Github](https://github.com/bowenwang1996)

Notable Projects:

* Developer at [Near](https://nearprotocol.com/)

* [Smart Contract Library for AssemblyScript](https://github.com/nearprotocol/near-runtime-ts)

### Evangelism

The "Evangelism" team works on projects, demos, talks, giving feedback on "messaging" about the project, and writing articles to help grow popularity and improve outreach.

#### Aaron Turner

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

#### Joshua Tenner

[Github](https://github.com/jtenner)

Notable Projects:

* [as-pect](https://github.com/jtenner/as-pect)
* [as2d](https://github.com/as2d/as2d)

Notable Articles:

* [An AssemblyScript Primer for TypeScript Developers](https://dev.to/jtenner/an-assemblyscript-primer-for-typescript-developers-lf1)

#### Willem Wyndham

![Willem Wyndham Avatar](https://avatars0.githubusercontent.com/u/1483244?s=150&v=4)

[Github](https://github.com/willemneal)

Notable Projects:

* [AssemblyScript University Course](http://www.cs.umd.edu/class/spring2019/cmsc388I/assemblyscript.html)
* Contributor to [as-pect](https://github.com/jtenner/as-pect)

### Developer Experience

The "Developer Experience" team works on projects such as tools, or anything that helps people be productive with AssemblyScript.


#### Joshua Tenner

[Github](https://github.com/jtenner)

Notable Projects:

* [as-pect](https://github.com/jtenner/as-pect)
* [as2d](https://github.com/as2d/as2d)

Notable Articles:

* [An AssemblyScript Primer for TypeScript Developers](https://dev.to/jtenner/an-assemblyscript-primer-for-typescript-developers-lf1)

#### Willem Wyndham

![Willem Wyndham Avatar](https://avatars0.githubusercontent.com/u/1483244?s=150&v=4)

[Github](https://github.com/willemneal)

Notable Projects:

* [AssemblyScript University Course](http://www.cs.umd.edu/class/spring2019/cmsc388I/assemblyscript.html)
* Contributor to [as-pect](https://github.com/jtenner/as-pect)

#### Bowen Wang

[Github](https://github.com/bowenwang1996)

Notable Projects:

* Developer at [Near](https://nearprotocol.com/)

* [Smart Contract Library for AssemblyScript](https://github.com/nearprotocol/near-runtime-ts)
