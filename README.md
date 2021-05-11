MannheimSearchJoinsEngine
=========================

A Search Join is a join operation which extends a user-provided table with additional attributes based on a large corpus of heterogeneous data originating from the Web or corporate intranets. 

This repository contains the code of the MannheimSearchJoinEngine which automatically performs such table extension operations based on a large corpus of Web data. Given a local table, the MannheimSearchJoinEngine searches the corpus for additional data describing the entities contained in the input table. The discovered data are joined with the local table and are consolidated using schema matching and data fusion techniques. As a result, the user is presented with an extended table and given the opportunity to examine the provenance of the added data.

More information about the MannheimSearchJoinEngine is found in the following paper: Oliver Lehmberg, Dominique Ritze, Petar Ristoski, Robert Meusel, Heiko Paulheim, Christian Bizer: The Mannheim Search Join Engine, Journal of Web Semantics, Volume 35, Part 3, 2015,Pages 159-166. https://doi.org/10.1016/j.websem.2015.05.001 as well as on the project's website: http://searchjoins.webdatacommons.org/
