<!----- Conversion time: 0.59 seconds.


Using this Markdown file:

1. Cut and paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β17
* Thu Oct 17 2019 15:21:12 GMT-0700 (PDT)
* Source doc: https://docs.google.com/a/ucsb.edu/open?id=1kvJwCJKHdZCeIw6CEYxeqsgYuSmZhzY_iQ4Lb_GrLl4
----->


# Generic pathway
E.g., L0 > L1 > external-query-sys (e.g., cuahsi, gbif)

EDI can mediate contributions to external query systems. Two that we anticipate working with are
* CUAHSI (for met and hyrdo data) and 
* GBIF (for organism abundance). 

## Mediation entails 

1. housing data packages compatible with the external system 
2. understanding the management model of the external system, including but not limited to
    1. manual steps
    2. Potential for automated push or harvester (pull). 
        1. EDI is not committing to a harvester at this time
        2. A registry (for either case - ie, how does automation know which datasets to act on?)
        3. Location of processing scripts 
            1. L0 _ L1 > L2 > push
    3. Compatibility with EDI style of time-series handling, (eg, with contributions as entire datasets rather than single values )

Per the notes from ESIP ClimHydroDB2 meeting, we need a write up describing a generic pathway

E.g., data goes from L1 to an external-query-system via a harvester, process resembling


1. Deposit L0 is in EDI, in native format and resolution
2. Convert and deposit L1 in EDI, in harmonized format 
3. Level 2: average values to a specific resolution 

<!-- Docs to Markdown version 1.0β17 -->
