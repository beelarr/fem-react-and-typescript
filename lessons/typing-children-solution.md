---
path: "/typing-children-solution"
title: "Typing Children (Solution)"
order: "2E"
section: "The Fundamentals"
description: "In which we determine what type to use for child components in React."
---

How do we type this? Well. We have a few choices.

- `JSX.Element;`: ðĐ This doesn't account for arrays at all.
- `JSX.Element | JSX.Element[];` ð This doesn't accept strings.
- `React.ReactChildren;`: ðĪŠ Not at even an appropriate type; it's a utility function.
- `React.ReactChild[];`: ð Accepts multiple children, but it doesn't accept a single child.
- `React.ReactNode;`: ð Accepts everything.
