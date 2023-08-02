# LCCC Project July Meeting

In attendance:
* [x] Emmy Carydis
* [x] Connor Horman
* [x] ~~Ray Redondo~~ Mini Baby Penguin

Other Attendees: carbotaniuman

Start time: 20:00 EDT

## General Discussion

The Leads will enter general discussions on any topic relevant to the project.

Connor: Should we have the authority to take official stances on Rust proposals:
* Ray: Yes. For it to be official, make a motion.

Connor: We should publish minutes from meetings on the Governance repo.
* Ray: We'll do it later. But we'll do it.

## Preliminary Review of LCCC Project Charter

The LCCC Leads will review the [LCCC Project Leadership Charter](https://github.com/lccc-project/tree/main/Governance/charter.md), which is to be approved by the LC Admins at the LC Admins meeting.

A motion to ratify the charter will be brought asynchronously once the charter is approved by the LC Admins.

## Project Proposals and Triage of New Projects

### Top-Level: XIR-Op

Approved

Lead: Connor Horman

Priority: Start in Phase 1, expect completion in Phase 2.

Project Description:
 
> XIR is current specified by an axiomatic model that fully defines the behaviour of all expressions. Such a spec is intended to be complete, and guarantee a lack of confusion on whether a given optimization is permitted. To aid in automatic testing and formal verification, I'd like to develop an operational specification, similar to the specification for Rust that T-opsem is creating.
> 
> The Subproject will write a syntax-similar language for XIR, called currently XIR-Op, then write the behaviour of each xlang expression in this language. The definition surface of XIR-Op would be small, to make it easy to rewrite in a PLOC.

### Target: m68k

Approved

Lead: Ray Redondo

Priority: Phase 2

Project Description: (new description; original wasn't particularly formalized)

> The Motorolla 68000 series of processors was very well-used in classic video game consoles and arcade machines. Along with supporting the 65c816, this would establish fairly complete support for using modern programming languages in 16-bit retro game development.

## Review of Non-Project (Administrative) Proposals

### Target Unification (Part 1)

Lead: Connor Horman

Priority: Phase 1

Project Description:
> The LCCC Project should attempt to unify targets -- Part 1 (with other rust compilers).
> 
> The LCCC Leads will attempt to arrange a discussion with relevant parts of rustc and gcc-rs to codify target naming rules.

Motion to Approve: Ray

Approved by Admins, to go to FCP asynchronously.

### Semantic Issue Labeling

Proposal Description:

> All lccc-project repositories should adopt semantic issue labeling, like the rust project and Clever-ISA project.
>
> Labels are broken down as follows by group:
> * A-\*: Area labels - what this pertains to. Examples: A-abstract-machine, and A-dereferenceable in unsafe-code-guidelines. LCCC Projects might have A-xlang, A-rust-type-checking, etc.
> * O-\* (style bikesheddable): Target labels - What Target does this apply to. Examples: `O-w65`, `O-windows`, `O-x86_64`.
> * C-\*: Category labels - what kind of issue is this (is this a bug, a tracking issue). Examples: C-tracking-issue, C-bug, C-informational.
> * F-\*: Feature (flag) labels - what features are in use. Examples: `F-generic-const-exprs`, `F-lccc-lang-items`.
> * I-\*: Issue type - what type of issue (ICE, unsound, non-compliance, etc.). Examples: `I-ICE`, `I-unsound`, `I-noncompliant`, `I-enhancement`, `I-unclear`, `I-spec-hole`, `I-defect`.
> * L-\* (style bikesheddable): Language Frontend - what language does this apply to (if any). `L-Rust`, `L-C`, `L-Cxx`.
> * S-\*: Status labels - What is the Status of the issue. Examples: `S-blocked-on-reviewer`, `S-blocked-on-requester`, `S-postpone`
> 
> X-\*, D-\*, and T-\* are reserved to prevent stylistic conflicts with the rust project or Clever-ISA project. T-\* may be used in the future to refer to Team labels.

Motion to approve: Ray.

Approved pending FCP.

### Conventional Commits

Proposal Description:

> All programming-centric lccc-project repositories [SHOULD](https://datatracker.ietf.org/doc/html/rfc2119) start following Conventional Commits. Explanation: https://www.conventionalcommits.org/en/v1.0.0/. The specific scope at this time will include the lccc root repository as well as the lc-binutils repository.

Motion to Approve: Ray

Approved pending FCP.

### Github Copilot policy

Approved

Proposal Description:

> LCCC should re-adopt LC's policy on Github Copilot, namely that it is banned for all contributions. Relevant link: https://githubcopilotlitigation.com/

## In re: target-tuples Ownership

The target-tuples subproject ownership will be discussed.

Connor: I want the repo
* Ray: But... No?
* Connor: But... yes. Get it to LCS.
* Ray: But more people can make the decision.
* Connor: But more people _have to_ make the decision.
* Ray: ... Fair enough.

## Open Discussion

The Leads will enter general discussions on any topic.

Emmy's tour.

## Closing

Plan to have next meeting in August

Adjourn time: 22:13 EDT