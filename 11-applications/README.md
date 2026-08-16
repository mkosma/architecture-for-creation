# 11 Applications

Expressions of the Architecture, rendered for particular audiences.

## Why this exists

The Architecture has to reach the world through specific documents aimed at specific people. A board page for a policy institute, a company narrative for prospective investors, a professional profile, a course, a talk. Each has its own audience, length, register, and constraints, and each fails if written as a generic statement of the underlying ideas.

This folder is where that translation happens, and it is where the discipline of the repository is actually tested. Writing under an audience's constraints is where the temptation arrives to shade a claim, drop the awkward part, or say the thing the audience wants to hear. Keeping applications in one place, each traceable to the same source, is what makes that visible when it happens.

Applications are also the return path. The attempt to say something in two hundred words is a stress test of whether it is understood at all, and it frequently exposes a gap in the Kernel that no amount of internal work would have found. That is how this project started.

## What belongs here

One subdirectory per application, each with its own README stating its audience, purpose, constraints, and current state. Present subdirectories:

- `rstreet/` for the R Street Institute role
- `chironic/` for Chironic AI
- `personal-brand/` for LinkedIn, the personal website, and how this person is presented generally

Add subdirectories as new applications arise: a course, a talk, an investor package, a new company.

Each subdirectory holds the drafts and the shipped versions, with a note on which Kernel version the work was built against.

**Applications may differ dramatically in tone, audience, and length.** A conference introduction and a company narrative should not sound alike, and forcing them into a common voice would be a mistake, not a standard.

## What does not belong here

**They must never contradict the Kernel.** Different emphasis is expected. Different claims about the world are not. When an application cannot be written without contradicting the Kernel, stop and resolve it in `09-kernel/`. That is the whole discipline in one sentence, and every shortcut around it costs the repository its reason to exist.

Not published bios. Once a bio is live at its venue, capture it in `02-public-bios/`; this folder holds the work of producing it.

Not the internal analysis of a company. The honest examination of Chironic is a case study and lives in `04-case-studies/`; the external narrative for Chironic is an application and lives here. The two will differ, and both should be true.

Not new thinking. When drafting produces an insight, write it into `06`, `07`, or `09` first. An insight that exists only inside a deck is lost.

## How it relates

Downstream of `09-kernel/`, always. Upstream of `02-public-bios/`, where the shipped version is captured, and closely tied to `12-visual-design/`, which gives many of these expressions their form.

The test of the entire repository is here: whether an artifact for a real audience can be derived from the Kernel without distortion. If it cannot, the failure is upstream, and this folder is where that is discovered.
