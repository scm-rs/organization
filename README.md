# Supply Chain Management in the context of Rust

This is the organizational repository for the [`scm-rs`](https://github.com/scm-rs/) organization.

## Purpose

The purpose of the organization is to maintain and foster Rust-based crates in the context of (software) supply chain
management. Commonly used crates many might need, but few might want to maintain. This should be a shared effort to
keep things going.

This repository specifically is there to host content of the organization itself.

## Communication channels

* [#scm-rs:matrix.org](https://matrix.to/#/#scm-rs:matrix.org)
* [GitHub Discussions](https://github.com/orgs/scm-rs/discussions)

## Governance

The idea is to keep things simple and efficient. On the other side, to create a diverse group of maintainers. Any
maintainer of the organization should be capable of accepting PR, making changes, and publishing new versions for all
crates. Meaning that a maintainer of the organization is a maintainer for all repositories and crates.

It may be challenging to initially have a diverse set of contributors. But that is the goal.

Becoming a maintainer of the organization should be driven by merit. Contributing to projects in a significant way.
This can either be a stream of contributions to existing repositories of the organization or by contributing an
existing project to the organization. Existing maintainers can make proposals, like nominating a new maintainer, or
accepting a new project. If there is either a 2/3rd majority accepting the proposal, or no veto after 14 days, the
proposal is accepted.

## Projects

All projects based on Rust and fitting into the context of software supply chain management are welcome. We prefer to
have existing maintainers transfer their projects to the organization. However, if there's a consensus that it makes
sense forking existing projects, that is an option too.

As it is important that maintainers on the organization are capable to release new versions, it is a requirement to have
the organization set up to publish new versions of those crates on `crates.io`.

## Development process

A few things we want to ensure:

* Semantic version compatibility
* A consistent set of dependencies for the onboarded crates
* A mostly automated release process
* A common CI and release setup

Those requirements should be there to ensure that anyone can easily maintain the project.

## Questions & answers

* **Why is this necessary?**

  All of those crates are foundational crates. Gladly, some people invested time and getting things going. However, for
  some of those crates, people moved on, lost interest, or have other priorities in their lives. That is understandable
  and perfectly fine. But it may be a problem for people using those crates.

  In some cases, people would actually provide PRs and put in the effort. But the original maintainers don't have the
  time, capacity or will to do the final step of releasing a new version.

  This effort has to goal to spread the load of maintaining all of those crates between a pool of experienced people,
  willing to help.

* **What is the motivation of the original initiators?**

  [@mrizzi](https://github.com/mrizzi) and [@ctron](https://github.com/ctron): We work at Red Hat on
  the [Trustification](https://github.com/trustification) project. Which requires a lot of crates from this
  organization. Some require patches and fixes. We could do this in our own forks and patch things up with "cargo
  patch". However, we believe it makes more sense to try coming up with a community driven approach of a diverse set of
  people.

* **Why not move to an open-source foundation?**

  That is definitely an option. But an initial attempt, getting there, finding the right foundation, turned out to be
  much harder than expected. So let's try a more hands-on approach, and start with a GitHub organization. If there is
  an interest in moving this to a foundation, and there is a candidate accepting those crates, this would definitely
  be a goal for the future.

* **You mentioned forking repositories. Is that really necessary?**

  We prefer to have existing maintainers contribute their projects to this organization. However, it is understandable
  that not everyone is comfortable doing this. Or, there simply is no way to reach existing maintainers.

  In such cases, having a fork may be the only viable option in continuing to maintain the project. Also, if a crate
  is based on another crate, which has been updated or re-released in this organization.

* **When using the term "organization", what does that exactly mean?**

  We are not talking about a legal entity. Just about a "GitHub organization" and the people behind it.
