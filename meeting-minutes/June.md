# LCCC Adminstration/Triage Meeting

## Call to Order 

The LCCC Leads will call this meeting to order.

## Adopt Governance Rules

The LCCC Leads will vote adopt Governance Rules.

The Governance Rules are documented in [LCCC Leadership Rules of Order and Governance Procedures](https://github.com/lccc-project/Governance/tree/main/leads/rules-of-order.md)

This Action Requires a Unanimous Vote.

Motion Carries

## Other Project Buisness

The LCCC Leads and meeting attendees will raise any other buisness they believe the meeting should address.

* Connor: LCCC Needs a place for procedural documents.
    * Recommend a new organization for lccc specifically and its subprojects.
    * Action Item: Create Organization for lccc - Motion Carried
        * Connor or Ray, whoever gets to it first.

## Triage Subprojects

Priority Assignments:

| Priority       | Description                                                     |
| -------------- | --------------------------------------------------------------- |
| Critical Infra | Infrastructure that form a critical part of the architecture    |
| MVP            | Target for Minimum Viable Product                               |
| Phase 1        | First Phase of Full Release, intended short term after MVP      |
| Phase 2        | Second Phase of Full Release, intended medium term              |
| Phase 3        | Third Phase of Full Release, intended long term                 |
| Maintain       | Subproject is complete, only maintence is required              |
| Deferred       | Subproject is deferred indefinitely                             |
| Suspended      | Subproject is not intended to be completed at this time         |
| Terminated     | Subproject is not intended to be completed and is to be dropped |

List of Subprojects:

| Subproject           | Category         | Owner/Maintainer | Priority       |
| -------------------- | ---------------- | ---------------- | -------------- |
| lccc (driver)        | Driver           | LCCC Leadership  | MVP            |
| lcrustc (driver)     | Driver           | Connor Horman    | Phase 1        |
| rustc-codegen-xlang  | Driver           | Ray Redondo      | Phase 1        |
| Rust Frontend        | Frontend         | LCCC Leadership  | MVP            |
| C++ Frontend         | Frontend         | Connor Horman    | Phase 2        |
| C Frontend           | Frontend         | Ray Redondo      | Phase 1        |
| Fortran Frontend     | Frontend         | Connor Horman    | Phase 2        |
| Go Frontend          | Frontend         | ---              | Deferred       |
| XIR Frontend         | Frontend         | LCCC Leadership  | MVP            |
| Zig Frontend         | Frontend         | Ray Redondo      | Phase 2        |
| JIT Frontend         | Frontend/Infra   | LCCC Leadership  | Phase 2        |
| Java Virtual Machine | Interpreted Lang | Ray Redondo      | Phase 3        |
| Lua Interpreter      | Interpreted Lang | Connor Horman    | Phase 3        |
| Arm Backend          | Backend          | Ray Redondo      | Phase 1        |
| C Backend            | Backend          | ---              | Suspended      |
| Clever-ISA Backend   | Backend          | Connor Horman    | Phase 1        |
| HBVM Backend         | Backend          | AbleCorp         | Phase 1        |
| Mircon Backend       | Backend          | Ray Redondo      | Phase 1        |
| RISC-V Backend       | Backend          | Ray Redondo      | Phase 1        |
| W65 Backend          | Backend          | Connor Horman    | MVP            |
| WASM Backend         | Backend          | Ray Redondo      | Phase 2        |
| x86 Backend          | Backend          | Connor Horman    | MVP            |
| xlang-abi            | Infra            | LCCC Leadership  | Critical Infra |
| xlang-abi-macros     | Infra            | Monadic Cat      | Phase 1        |
| xlang-backend        | Infra            | Connor Horman    | Critical Infra |
| xlang-host           | Infra            | LCCC Leadership  | Critical Infra |
| xlang-targets        | Infra            | LCCC Leadership  | Critical Infra |
| libabi               | Infra            | Ray Redondo      | Deferred       |
| cxx-stdlib           | Sys Libraries    | Connor Horman    | Phase 2        |
| libatomic            | Sys Libraries    | Connor Horman    | Phase 1        |
| librt                | Sys Libraries    | Connor Horman    | Phase 1        |
| libunwind            | Sys Libraries    | Connor Horman    | Phase 2        |
| LCRust stdlib        | Sys Libraies     | Connor Horman    | MVP            |
| lcas                 | Binutils         | Connor Horman    | MVP            |
| Clever-ISA Assembler | AS Frontend      | Connor Horman    | Phase 1        |
| HB Assembler         | AS Frontend      | AbleCorp         | Phase 1        |
| W65 Assembler        | AS Frontend      | Ray Redondo      | MVP            |
| x86 Assembler        | AS Frontend      | Connor Horman    | Phase 1        |
| arch-ops             | Infra            | Connor Horman    | Critical Infra |
| binfmt               | Infra            | LCCC Leadership  | Critical Infra |
| lcld                 | Binutils         | LCCC Leadership  | Phase 1        |
| objdump              | Binutils         | Connor Horman    | Phase 1        |
| ar                   | Binutils         | Connor Horman    | Phase 1        |
| readobj              | Binutils         | Ray Redondo      | Phase 2        |
| objcopy              | Binutils         | Ray Redondo      | MVP            |
| Abyss                | Infra            | Ray Redondo      | Deferred       |
| trustc               | Bootstrap        | Connor Horman    | Deferred       |
| cargo-autobuild      | Infra            | Connor Horman    | Phase 1        |
| target-tuples        | Infra            | Connor Horman    | Maintain       |
| xlang-hdl            | Infra            | Connor Horman    | Phase 2        |
| hdl-simulator        | Backend          | Connor Horman    | Phase 2        |
| hdl-board-output     | Backend          | Connor Horman    | Phase 3        |

## Open/Other Discussion

The LCCC Leads and Meeting Attendees may discuss anything else they see fit to have appear on the official record.

* TODO: `target-tuples`-related governance