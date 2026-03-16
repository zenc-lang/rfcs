# Zen C RFCs (Request for Comments)

The "RFC" (request for comments) process is intended to provide a consistent and controlled path for new features to enter the Zen C language and standard library.

Many changes, including bug fixes and documentation improvements, can be implemented and reviewed via the normal GitHub pull request workflow on the main [`zenc` repository](https://github.com/zenc-lang/zenc). 

However, some changes are "substantial", and we ask that these be put through a bit of a design process and produce a consensus among the Zen C core team and community.

## When to write an RFC

You need to follow this process if you intend to make "substantial" changes to Zen C or its documentation. What constitutes a "substantial" change?
* A new language feature (such as a new keyword, syntax change, or type system rule).
* Removing language features.
* Changes to the interface of the standard library (`std`).
* New core tooling or changes to the build system/CLI behavior.

If you just want to fix a bug or optimize an existing compiler pass, **you do not need an RFC**. Just open a PR on the main repo!

## The RFC Lifecycle

1. **Socialize the Idea:** Before writing a formal RFC, float your idea in the [Zen C Discord](https://discord.com/invite/q6wEsCmkJP) to gauge interest and gather initial feedback.
2. **Draft the Proposal:** Fork this repository, copy `0000-template.md` to `text/0000-your-feature-name.md`, and fill it out completely.
3. **Submit a Pull Request:** Open a PR against this repository. The community and maintainers will debate the proposal in the PR comments... So, be prepared to revise your draft!
4. **Final Comment Period (FCP):** Once the core team believes the RFC is fully mature and consensus is reached (or unresolvable disagreement is mapped out), a maintainer will propose to Accept or Reject it, initiating a 7-day Final Comment Period.
5. **Resolution:** If accepted, the PR is merged into this repository. The RFC is now **Active** and ready to be implemented in the Zen C compiler!

*Note: An accepted RFC is not a guarantee that the core team will immediately write the code for it. It simply means the design is approved, and PRs implementing it will be accepted.*

## Getting Started

Ready to propose a feature? Read and copy the [**RFC Template (`0000-template.md`)**](0000-template.md) to get started.