Channel choice
==============

  -------------- --------------------
  **Created:**   *4/1/2020 1:10 PM*
  **Updated:**   *4/3/2020 5:00 PM*
  -------------- --------------------

\

Given two actors which have a set of opened, available and trusted
channels which to establish or which to use, while establishing, what
would the agents consider when choosing a channel:

\

Before opening channel attention is turned towards availability:

-   Expected Availability in Peer Connection Pool

-   Expected Availability of Network

-   Expected Routing Availability to Destination

-   Audit Considerations (will my attempt at achieving/establishing this
    connection be reported externally, by peer?)

-   Journaling Considerations (will my attempt at achieving/establishing
    this connection be reported externally?)

-   Anonymity/Interceptability Consideration (depends mainly on routing,
    encryption)

-   Anonymity/Traceability Consideration

\

After opening channel:

-   Expected Latency

-   Expected Additional Cost

-   Expected Clock Offset (Distribution of Offset; Distribution of
    Differential Offset)

-   Integrity guarantee (per packet, per higher forms of aggregation)

-   Order-of-decoding guarantee (TCP)

\

\

\

 
