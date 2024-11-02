# Public Domain Relay

Relay / bridge / gateway between centralized and decentralized ecosystems.

## Philosophy

- The approach we aim to take is to enable the current default most widely adopted methodology first: git + CI/CD
  - First centralized: GitHub + GitHub Actions
  - Next decentralized: Forgejo + Forgejo Workflows
- We'll later move into the next phase which will be SCITT + ORAS.

We aim to leverage as many existing codebases as possible. We aim to write as
little code as possible. The goal being to enable effective use of policy to
gate AI based contributions of code and modifications to policy. Thereby scoping
the AI's range of influence.

Our policies will at first be purely technical. We'll later move into code
review based on alignment to a repositories values and strategic plans and
principles. These will likely translate into granular technical policy
definition.

## Links

- [Reference Implementation](https://github.com/publicdomainrelay/reference-implementation/)
  - [Architecture Design Records](https://github.com/publicdomainrelay/reference-implementation/tree/main/docs/adrs/)
    - [Decentralized Governance](https://github.com/publicdomainrelay/reference-implementation/blob/main/docs/adrs/governance.md)
  - [Notes](https://github.com/publicdomainrelay/reference-implementation/tree/main/docs/notes/)
    - [Attestations as a Backbone for Trust and Verification](https://github.com/publicdomainrelay/reference-implementation/blob/main/docs/notes/backbone.md)
  - [Living Threat Models](https://github.com/johnlwhiteman/living-threat-models)
    - [Securing Rolling Releases in Poly-Repo Environments](https://github.com/dffml/dffml/blob/main/docs/tutorials/rolling_alice/0000_architecting_alice/)

## Miscellaneous

- [Protopia](https://kk.org/thetechnium/protopia/): *"the best term for the massive set of interlinked projects of activists, thinkers, and practitioners around the world who seek to contribute to the necessary and desirable transformations of societies around the world"*
  - For example: The publishers of this content relay information found other places and the work of others and active working groups (IETF, OpenSSF, etc.) into yet another jumping off location as public domain content for others to get involved with existing efforts and broadcast the work of others with the aim of alignment to preexisting widely adopted best practices. We aim to kint together existing work as much as possible and write as little new code as possible to implement secure patterns for decentralized software development.
- Profile picture reused under MIT License from [`intel/dffml`](https://github.com/intel/dffml) thanks to [Jason Long](https://jasonlong.me) who contributed it.
