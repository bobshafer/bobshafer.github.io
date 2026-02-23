Here is an introduction written for a general reader.

---

# What This Is About

Imagine you are trying to understand why the universe follows the rules it does — why quantum mechanics looks the way it does, why probability works the way it does at the smallest scales, why particles seem to be in multiple places at once until you measure them.

The usual approach is to start with quantum mechanics as given — to assume its rules and then show they work. This document takes a different path. It asks: what is the minimum you have to assume about how anything continues to exist, and what follows from that alone?

The answer is surprising. Almost everything we associate with quantum mechanics — the wave-particle duality, the probability rule at the heart of measurement, the way two particles can be entangled across space, the impossibility of knowing both position and momentum exactly — all of it falls out of a handful of simple ideas about continuation. Not assumed. Derived.

---

# The Central Idea: Continuation

Everything that exists continues — or it doesn't exist anymore.

This sounds trivial but it isn't. It means existence is not a static thing. It's a process. A system exists only insofar as it has somewhere to go next — some admissible next state. The moment it has no viable continuation, it ceases.

We call this the Principle of Continuation. It's the starting point. Everything else is built from it.

---

# Two Regimes

The framework distinguishes two fundamental modes of being.

**The elastic regime** is when a system has multiple viable continuations simultaneously — when the future is genuinely open. Think of a wave spreading outward in all directions, exploring every possible path at once. Nothing has been decided yet. All options are live.

**The committed regime** is when a continuation has been selected and inscribed — when something has actually happened. A record has been written. The wave has collapsed to a point. This moment is irreversible.

We call these O-mode and G-mode. Every system is always somewhere on the spectrum between them — either propagating through possibilities or crystallized into actuality.

The central question of the framework is: what mathematical structure must exist at the interface between these two regimes?

The answer to that question is quantum mechanics.

---

# The Structure, Layer by Layer

**Layer 1: The category of continuations**

We start with a collection of states — any states, from subatomic particles to musical ideas to financial situations — and the transitions between them. Each transition has a viability: how admissible it is, ranging from zero (impossible) to one (certain). Composing transitions multiplies their viabilities.

This gives us a mathematical object called an enriched category. It immediately produces a notion of distance — the minimal cost to get from one state to another — and a notion of a sphere of becoming: all the states reachable within a given cost budget. This sphere is not a metaphor. It is the formal object corresponding to the future light cone in physics.

**Layer 2: Branching**

When a system has multiple possible continuations simultaneously, we need to represent that plurality without yet committing to any of them. We formalize this as branching structure — a way of keeping track of alternatives without selecting among them.

We require one thing of this structure: that branching and sequential continuation be compatible. If you continue along path A and then choose between B and C, that must be the same as choosing between "A then B" and "A then C." This is called distributivity.

Here is the first surprise: requiring distributivity forces a specific mathematical structure. The only consistent way to assign numerical values to alternatives that respects distributivity is linear addition. Superposition — the quantum mechanical principle that alternatives combine by adding — is not assumed. It falls out as the unique representation that makes branching and sequence compatible.

**Layer 3: Amplitudes**

Once we have linear combination of alternatives, we can assign complex number amplitudes to paths. Serial paths multiply their amplitudes. Parallel alternatives add theirs. The field of complex numbers ℂ provides the natural home for these amplitudes because it allows for phase — a kind of directional information that can cause alternatives to cancel each other out or reinforce each other. This cancellation is what produces interference patterns.

At this stage we have a rich elastic structure but no probabilities yet.

**Layer 4: Commitment and the Born Rule**

When a system commits — when the elastic regime collapses into a definite record — classical probability must emerge. The record is described by a Boolean algebra of events with additive probabilities. This is ordinary classical logic: something either happened or it didn't.

The compatibility requirement between the elastic regime and the committed regime is severe. We need a function that converts complex amplitudes into classical probabilities. This function must:

- Be indifferent to the overall phase of the amplitude (since phase has no classical meaning)
- Respect the multiplicative structure of serial continuation
- Produce classically additive probabilities for mutually exclusive outcomes

These three requirements together force a specific form: the probability must be proportional to the amplitude magnitude raised to some power α. A further argument — that classical additivity must hold for alternatives with arbitrary relative phases — forces α = 2 exactly.

The result is the Born rule: probability equals the squared magnitude of the amplitude.

This is not assumed. It is the unique function that makes elastic plurality and classical commitment compatible. It is derived as a compatibility theorem.

**Layer 5: Hilbert Space**

Once we have the Born rule, the mathematical structure of Hilbert space follows automatically. The amplitudes form a vector space. The Born rule provides an inner product. Mutually exclusive events correspond to orthogonal subspaces. The geometry of quantum mechanics emerges from the geometry of compatibility between the two regimes.

**Layer 6: Composite Systems**

When two systems are independent — when their continuations don't constrain each other — their cost structures add and their amplitudes multiply. The mathematical structure that represents this is the tensor product of their Hilbert spaces.

Here is a second surprise: most states in a tensor product are not of the form "system A in state X and system B in state Y." Most states in the combined space are entangled — they cannot be factored into independent descriptions of the two systems. Entanglement is not a special exotic phenomenon that needs to be explained. It is the generic case. Unentangled states are the special case.

Bell's theorem — the demonstration that quantum correlations between distant systems cannot be explained by any local classical mechanism — follows directly from the tensor structure and the Born rule, without any additional assumptions.

**Layer 7: Space, Momentum, and Uncertainty (Optional)**

If we add the assumption that the continuation structure is homogeneous — that it looks the same everywhere, that there is a consistent notion of translation — then additional structure emerges. Position and momentum appear as conjugate quantities, related by Fourier duality. The Heisenberg uncertainty principle — the impossibility of knowing both exactly — follows from their mathematical relationship. Planck's constant ℏ appears as a scale parameter of the representation.

This layer requires explicit additional assumptions about symmetry and is therefore presented separately from the core.

---

# What Has Been Derived and What Has Been Assumed

**Assumed (primitive):**

- States exist and have admissible transitions with multiplicative viability
- Branching and sequential continuation are distributively compatible
- Commitment produces classical Boolean probabilities
- The probability assigned to an elastic alternative depends only on its magnitude, not its phase
- Serial probabilities obey a chain rule

**Derived (not assumed):**

- Linear superposition of alternatives
- Complex amplitude structure
- The Born rule (probability = squared magnitude)
- Hilbert space geometry
- Tensor product structure for composite systems
- Entanglement as the generic case
- Bell nonlocality without faster-than-light signaling

**Derived with additional symmetry assumptions:**

- Position and momentum as conjugate observables
- Fourier duality between their representations
- Heisenberg uncertainty principle
- Canonical commutation relations

---

# Why This Matters

Quantum mechanics has been spectacularly successful for a century. It predicts experimental results with extraordinary precision. But it has always carried an air of mystery — its rules work, but why they are the rules has never been fully clear.

This framework offers an answer. The rules of quantum mechanics are not arbitrary features of our particular universe. They are the inevitable mathematical consequences of two things: that systems continue to exist by having viable next states, and that committing to a definite outcome requires compatibility with classical probability.

Any system with those two properties — elastic plurality before commitment, classical additivity after — must obey the Born rule, must have Hilbert space geometry, must exhibit entanglement, must violate Bell inequalities.

The universe is quantum mechanical not because it happens to be, but because continuation and commitment are both real, and Born is the only bridge between them.
