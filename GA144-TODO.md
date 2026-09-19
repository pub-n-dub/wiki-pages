# GA144 Wikipedia article — improvement TODO

The local `GA144.wikitext` matches the live English Wikipedia article as checked on 19 September 2026. Make proposed changes through Wikipedia’s normal editing workflow and avoid overwriting intervening live edits.

## Highest priority: citation completeness

- [ ] Add an inline citation to the first paragraph of **Architecture**, which currently makes uncited claims about local RAM and ROM, independent execution, lack of a global clock/shared memory, blocking reads and writes, explicit routing, and deadlock avoidance.
- [ ] Prefer the peer-reviewed cryptography paper for core architecture and asynchronous-operation claims: Schneider, von Maurich, Güneysu and Oswald, “Cryptographic Algorithms on the GA144 Asynchronous Multi-Core Processor: Implementation and Side-Channel Analysis,” *Journal of Signal Processing Systems* (2014), DOI [10.1007/s11265-014-0872-5](https://doi.org/10.1007/s11265-014-0872-5).
- [ ] Use the Berkeley Chlorophyll work for the programming model, distributed local memory, and neighbour communication. Cite the final published paper where possible, rather than relying only on the master’s report: [Chlorophyll: Synthesis-Aided Compiler](https://mangpo.net/papers/chlorophyll-pldi14.pdf).
- [ ] Check each performance and power statement against the cited GreenArrays data book. Keep “GreenArrays specified” attribution for vendor figures, and do not turn a vendor specification into an unqualified measured result.

## Stronger independent coverage

- [ ] Add the independent DesignSpark hands-on article where it supports the overview, package/evaluation-board discussion, and vendor performance claims: [Hands on with a 144 core processor](https://www.rs-online.com/designspark/hands-on-with-a-144-core-processor).
- [ ] Seek independent editorial coverage of the GA144’s architecture, applications, manufacturing, or commercial availability in semiconductor trade press and conference proceedings.
- [ ] Search for follow-on research that uses or evaluates GA144, especially work that reports measurements, programming difficulties, or comparisons with other spatial/asynchronous processors.
- [ ] Use independent sources for analytical or evaluative claims; retain GreenArrays manuals chiefly for pin counts, interfaces, package details, revision identifiers, and stated specifications.

## Article clarity and precision

- [ ] Consider replacing or explaining “144-core microprocessor” with “array of 144 F18A stack-computer nodes” in the lead, if sources use that more precise terminology.
- [ ] Cite the lead’s architecture description directly, rather than relying on later sections for verification.
- [ ] Review “announced for sale” versus “released to production” and “available from stock”; distinguish the October 2010 production release from 2011 production availability where sources do so.
- [ ] Verify that the I/O count and list apply specifically to the production G144A12 revision, not only an earlier GA144-1.10 prototype brief.
- [ ] Standardize spelling to the variety already established by the live article (for example, “neighbouring” and “analogue”), unless Wikipedia’s article-level consensus changes it.

## Maintenance

- [ ] Check that cited URLs remain live and replace unstable company-news links with archived versions where a stable archival copy is available.
- [ ] Preserve the existing research-use section: it is a major strength because it establishes independent academic use of the processor.
- [ ] Before publishing, preview citation placement and ensure every non-obvious technical assertion has a source immediately nearby.
