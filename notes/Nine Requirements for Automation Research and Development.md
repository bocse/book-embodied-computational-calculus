

Nine requirements for automating R&D
==================================

**Created:**

_11/12/2019 3:38 PM_

**Updated:**

_11/12/2019 3:43 PM_

**Author:**

_Bogdan Bocse_





1.  Referential integrity between systems.
    1.  Identifiers: Consistently encoded throughout layered encoding abstractions;
            1.  each layer of encoding and abstraction, respectively, usually adds its own:
            2.  addressable resources (mutable/immutable \*states\*, and #functions#),
            3.  !actions/verbs/intentions!
            4.  enumerations/sets, (immutable labeled, ordered, sets)
            5.  Preconditions:
                1.  registration DNF,
                2.  cryptographic
                3.  DNF authentication
                4.  DFN, authorization
                5.  DFN,
                6.  rate limiting/capping/billing DFN\*\*, 
                7.  \*\*DNF - Discovery, Negotiation and Fulfilment
            6.  relationships
    2.  the semantic of applying each action to a \*state\* may be generalized/abstracted, but the semantic of defining the link between resource-functions (#lambdas#) and !verbs! is sentient-defined, at least as far as Scheduling-Routing-Allocation is concerned), . It is usually the adding of new relationship-types between nodes that forces the escapers, separators, interruptors, initiators, terminators to bubble-up/cluster-up into a higher-level of abstraction.
    3.  Persistent with Known-Expected Durability, Eventually Replicated with periodic cross-verification between replicas (layered reconciliation, bottom up)
    4.  Retrievable by authorized systems and by users authorized on those systems (the user is a second-class citizen)
    5.  Consideration from preserving order:
        1.  Total orders must be preserved.
        2.  Eventual orders must be indicated, together with the expected windows for reconciliation/mediation/merging/reducing events (known as "time until CFOs" signature; last known state of planned human intervention for validation;)
        3.  Partial orders must be specified, together with the computable function and the addressable state which the partition (or the partition set, partition list, partition tree, depend on)
2.  Referential integrity throughout the data lifecycle: between service requests, service responses and service logs.
3.  Semantic request of entities, attributes, relationships and collections
4.  Instant data life-cycle visibility throughout the system
    1.  Replayeable version history, signed with "vector clock chain" and physical precision/drift clock (last synced with NTP-Zurich, NTP-London and NTP-Instanbul, trusted authoritative clock, with expected offset probability distribution ( probability per 1ms, probability per 2ms, probability per 3ms; expected drift is computed based on hardware specifications )
    2.  Known accessibility (i.e. ) and durability degradation PDFs (probability distribution functions)
    3.  (...)
5.  Secret Management (...)
6.  Configuration Management (...)
7.  Typed Multi-Graph or Hyper-graph, hosted on a distributed, flexible infrastrucutre
8.  MergeSort Chain signature (the list of left/right/split decisions made by the algorithm, hased) when several partially ordered streams are merged together. The chain signature represents a way to track, a posteriori, if some consenting actor other than yourself from that chain has been processed "in front of you" or "behind of you". You can think of this as a partially recomposable queue.
9.  Binarizable DTOs and layered-semantic compression and encoding (Multi-Layered Huffman encoding):



