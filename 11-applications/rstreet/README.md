# R Street

The application that started everything.

## Why this exists

The attempt to rewrite a short biography for the R Street Institute board page is what opened the inquiry that became this repository. The bio would not come out right, and the reason turned out to be that the underlying question had never been answered: what is this person actually for. Two hundred words cannot be written until that is settled, which is why a small task refused to stay small.

That history gives this folder a particular standing. It is an ordinary application, subject to the same rules as any other, and it is also the origin artifact. When the Kernel is written, this bio is the first honest test of whether it works.

## What belongs here

Work aimed at R Street: the board chair biography, any statement of the role, and other material produced for the institute in that capacity.

Keep the drafts, in sequence, with a note on which Kernel version each was built against. For an application this short, the sequence of attempts is unusually informative, since each failed draft marks a place where the underlying thinking was not yet resolved.

Record the venue's constraints explicitly: length, voice, third person, what the institute's other board pages look like. Constraints are part of the problem, and a draft written without them is not a draft of this document.

Note also that the byline is a separate field from the body text on the institute's site. It carries its own claim and needs its own decision.

## What does not belong here

Not the published version. Once it is live on rstreet.org, capture it in `02-public-bios/`, which holds what the world actually reads.

Not the R Street case study. An analysis of R Street as an institution, examined through the Architecture, belongs in `04-case-studies/`.

Not biographical facts. Career records are evidence and live in `01-biographical-sources/`. This folder is for the expression, not the raw material.

## How it relates

Derived from `09-kernel/`, constrained by `07-principles/`, and drawing its facts from `01-biographical-sources/`. Its current published state, and the contradiction it carries with the 2026 resume, are recorded in `02-public-bios/`.

The origin of the whole undertaking is documented in `00-discovery-sessions/discover-session-001.md`, which opens with this exact task.
