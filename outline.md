---
title: Outline
chapter: Generics are collaborative
counters: [ex,def]
bibliography: /home/erik/References/cdd.json
csl: /home/erik/References/apa.csl
link-citations: true
endnotes: true
---

# Generics are quirky

On the surface, characterizing generic sentences (henceforth, *generics*), such as [Bears](#bears), appear to involve plural predication -- a property being applied to a group of individuals.

But it is commonly accepted that in the case of generics, surface appearances don't reflect underlying structure.[^varieties] The problem is that generics are *quirky* -- the proportion of the subject class that must satisfy the predicate varies from one example to the next.[^quirkyex] The standard solution to this problem involves positing additional, quantificational, structure at logical form. Quirkiness is captured by the variable force carried by the *GEN* quantifier [e.g., @leslie2007, @cohen2004, many others].

I propose to defend the simplified, predicational view of generic sentences against the challenge of quirkiness. My strategy is to first make the challenge more difficult. Not only are generics quirky, they're also *fickle*, and fickleness seems to provide additional demand for underlying structure.

But exploring the nature of fickleness reveals the need to factor conversational context into our semantic analysis, and the manner in which context operates in generic discourse provides a way to preserve the predicational analysis in the face of quirkiness.

\goop{ex}{bears}

: (Bears)

    > **Surface**: Bears are dangerous. \
      **Predication**: Dangerous(Bears) \
      **Quantification**: GEN(Bears)(Dangerous)

[^varieties]: Sentences involving bare plurals are often taken to be a class twice-divided. Characterizing generics (**I**) are distinguished, in terms of their logical structure, from existential plurals (**E**)
and direct kind generics (**D**).

    \goop{ex}{varieties}

    : (Plural varieties)

        > **I**. Bears are dangerous.
                 $\rightarrow GEN(bears)(dangerous)$ \
          **E**. Bears are frolicking.
                 $\rightarrow\exists X (X \subseteq bears \land X \in frolicking)$ \
          **D**. Bears are endangered.
                 $\rightarrow endangered(bears)$

[^quirkyex]: The following set provides an example of the quirkiness of characterizing generics. (a) is true, since most all grizzlies have brown fur. But, while (b) is true even though very few polar bears have ever tasted human, (c) is false even though most **SUBJECT** satisfy **PREDICATE**.

    \goop{ex}{quirky}

    : (Quirky generics)

        > a) Grizzlies are brown.
          b) Polar bears eat humans.
          c) [False even though a lot satisfy.]

# Generics are fickle

In addition to their quirkiness, generics exhibit *fickle* behavior in extended discourse. Consider the following exchange:

\goop{ex}{teddy}

: (Teddy bears)

    > **A**:  Bears are dangerous. \
      **B**:  What about Teddy bears? \
      **A**:  I didn't mean *all* bears.

The naturalness of *B*'s response to *A*'s first utterance, the dialogue *initiation*,[^initiation] suggests that bare plural sentences are susceptible to correction,[^susceptible] which pushes us toward a more strict representation of the content of the initiation. That is, it seems that *B* is disputing *A*'s claim in [Teddy bears](#teddy), and the most natural way to formalize disagreement is in terms of commitment to conflicting content.

But *A*'s rejoinder indicates that plurals are also resilient to refutation.[^resilient] The response suggests that the original claim was intended to be compatible with *B*'s challenge, which pushes us toward a less strict interpretation of the initiation content.[^otherfickleness]

[^initiation]: As we'll be dealing with extended discourse a fair bit, it will be helpful to have some terminology on the table. I refer to the opening utterance of a bit of dialogue as the *initiation*, and the last utterance as the dialogue's *completion*. Intermediate utterances that follow in the same topic discussion are *continuations*. The significance of these elements of a discourse will come out later on. [Cf. @clark1992a]

[^susceptible]: What this susceptibility amounts to will be explored in the discussion to follow. For now, I will gloss it as a tendency to be used in a way that projects *conjecture*, which is itself a force used when a claim goes beyond the evidence for it available to the speaker. Alternatively, a corollary of susceptibility is that plural predications are *strong* -- they project uniform application of the predicate to the subject class.

[^resilient]: Resilience, too, is a technical term to be developed in what follows. For now, I take it to entail that there is room for a speaker to retrench in the face of correction. A natural consequence of resilience is that plurals are *weak* -- they allow for exceptions to the expressed rule.

# Fickleness and logical form

We are thus pulled in opposite directions in providing a formal semantics of generics, which is a pretty good indicator that there is something pragmatic going on with them [@sterken2015 provides additional arguments for the context sensitivity of generics]. This contextual variability deepens the challenge for the predicational analysis of generics, for the reason that other attempts commonly focus on the *kind* associated with the subject class as the subject of the predication. @liebesman2011, for instance, suggests that quirkiness arises from the multitude ways in which kinds can inherit properties from their members. [See also @mcconnell-ginet2012]. But this metaphysical approach runs into trouble with fickleness. If variability is a matter of property instantiation, then a single predicate must express different properties in different contexts. The threat of massive ambiguity is imminent.

Thankfully, the kind is not the only subject in the vicinity, and the beginnings of a contextual treatment of generics are provided in @schwarzschild1994. Schwarzschild's plurality-based account of the *distributive*/*non-distributive* distinction for plurals can be leveraged to capture the fickleness of generics as well.

My contention is that the referent of the subject is frequently a non-maximal plurality composed from members of the subject class. Plural predicates include both individuals and pluralities formable from those individuals. So, for a generic to be true is just for the appropriate non-maximal subject plurality to be included in the predicate class.

[^sterken]: See @sterken2015 for additional arguments for the context sensitivity of characterizing generics.

# Fickleness and discourse dynamics

The missing piece is a story for how context factors into determining the referent of the subject in a way that allows for the requisite variability. The mechanism of fickleness is at base a form of context-shifting like that advocated by @gillies2010, which in turn depends upon the existence of multiple contexts that are potentially relevant to an utterance, as suggested by @vonfintel2008 in their examination of phenomena similar to fickleness in the context of epistemic modals.

This, I suggest, is right as far as it goes, but it doesn't go far enough. For the discourse in [Teddy bears](#teddy) is not just any dispute. It is *coherent* in a way that demands further explantion [cf. @kehler2000]. The interlocutors aren't merely disagreeing, they are *negotiating* on the context [cf. @richard2004].

# Navigating fickleness collaboratively

Semantically, generics are undistinguished predications of a property to a plurality. Quirkiness derives from the collaborative refinement process. If I assert a generic sentence and there there is no correction, my uniform attribution goes through. But if you contest, you can do so without rejecting my proposal outright, you can refine it by partitioning the subject plurality as you see fit. I, too, can further the negotiation.

Capturing the process of negotiation requires a workspace, akin to a programming *sandbox* separate from our conversational scoreboard [cf. @clark1992a] In this space, we can negotiate on a particular discourse element without infecting the rest of the conversational scoreboard. This is important, for in negotiation nothing has yet been mutually accepted. The boundaries of this workspace are set by the nature of the proposals over which we are negotiating; this is captured by treating statements as issuing *propositional radicals* that are *saturated* by a contextually determined element. When negotiation is complete, the final product is *merged* into the conversational scoreboard.

\newpage

# References {-}
