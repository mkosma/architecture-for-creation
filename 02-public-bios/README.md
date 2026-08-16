# 02 Public Bios

Every biography that faces outward, kept as published.

## Why this exists

A bio is the smallest possible expression of the Architecture, and the hardest. Two hundred words have to carry a claim about what a person is for. Most bios fail at this without anyone noticing, because a list of impressive things reads as an answer while making no claim at all.

This folder exists because these documents are already deployed. They sit on an institute's website, a professional network, a law firm's page, a conference program. They are being read right now, by people forming a judgment. Whatever the Kernel eventually says, these are the versions currently doing the work in the world, and they were mostly written before anyone knew what the Architecture was.

Collecting them makes two things visible. First, the drift: the same person described as four different people across four venues, each true, none coherent with the others. Second, the gap between what the bios claim and what the Architecture actually holds. This project began with exactly that gap, in exactly one of these documents.

## What belongs here

Every public biography, captured as published:

- R Street
- LinkedIn
- Breeze Law
- Chironic
- conference bios and speaker introductions
- the personal website
- anything else where a third party publishes an account of who this is

Capture the live version, not a copy of the draft that was sent. What the venue actually published is what the world reads. Include the URL and the retrieval date, and keep a rendering (HTML or PDF) alongside any text extraction, since a live page changes without notice and a captured page does not.

Keep superseded versions rather than overwriting them. The sequence is informative.

## What does not belong here

**The goal is not consistency of wording.** Do not edit these into agreement, and do not sand off a venue's house style. A speaker introduction and a board page should not sound alike.

**The goal is consistency of underlying Architecture.** Where two bios imply different claims about what this person is doing and why, that is the finding worth recording, and it is resolved in `09-kernel/` rather than by quietly rewriting one of them.

New bios being drafted do not belong here. A bio in progress is an application: it lives in `11-applications/`, and it lands here once it is published. Private career records belong in `01-biographical-sources/`, since a resume is evidence and a bio is a performance.

## How it relates

This folder is both evidence and scoreboard. As evidence, it shows how the story has been told in public and where the tellings diverge. As scoreboard, it is where the canonical rule gets tested: once the Kernel exists, every document in here can be checked against it, and the ones that contradict it are the work queue for `11-applications/`.

The R Street bio in particular is the origin artifact of this entire repository. It is the document that would not come out right, and the reason the underlying question got asked.

## Current holdings

| File | Source | Captured |
| --- | --- | --- |
| `rstreet-monty-kosma.{html,pdf,md}` | rstreet.org people page | 2026-08-16 |
| `linkedin-profile-2026-08-16.{pdf,md}` | LinkedIn's own profile export | 2026-08-16 |
| `montykosma-com.{html,pdf,md}` | montykosma.com, which serves a frameset over a published Google Doc | 2026-08-16 |

Two gaps worth closing: Breeze Law and Chironic have no capture here yet.

Note that the R Street page and the 2026 resume in `01-biographical-sources/` give two different present-tense identities. That is a live contradiction, and it is the kind this folder exists to surface.
