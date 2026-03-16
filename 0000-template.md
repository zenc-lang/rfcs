# RFC Template

- **Author(s):** (Your Name(s)/GitHub Handle(s))
- **Status:** Draft
- **Created:** (YYYY-MM-DD)

*(Instructions: Copy this template, fill it out, and submit it as a PR to this repository. Delete this instruction block before submitting.)*

---

## 1. Summary
One short paragraph explaining the feature. What is it, and what does it do? (Keep this simple enough that a new user could understand the gist of it).

## 2. Motivation
Why are we doing this? What specific use case does it support? What is the expected outcome? Prove that this feature solves a real problem that systems programmers face in Zen C today.

## 3. Detailed Design
This is the bulk of the RFC. Explain the feature with enough detail that a core contributor could read this section and go write the parser/codegen for it.
* Show clear "Before" and "After" syntax examples.
* Explain edge cases and how the compiler should handle them.
* Explain how this interacts with existing features (for example, does it break memory safety? Does it complicate type inference?).

## 4. Drawbacks
Why should we *not* do this? Every feature adds compilation time, parser complexity, or cognitive load for the user. An RFC without drawbacks is incomplete. Be honest about the costs of this proposal.

## 5. Alternatives Considered
What other designs did you consider? Why is this proposed design better than those alternatives? What happens if we simply do nothing and reject this RFC?

## 6. Prior Art
How do other systems languages (C, C++, Rust, Zig, Go, Swift) handle this exact problem? Did you borrow this syntax from somewhere else? 

## 7. Unresolved Questions
What parts of this design are you still unsure about? What do you explicitly want the community to help you figure out during the PR review process?