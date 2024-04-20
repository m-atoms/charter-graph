# charter-graph
Convert SF Charter into a graph database

### Manual document preprocessing
Preprocessed file: `sf_charter_04192024_simplified.txt`

Note: tried to parse html but charter doc is too heterogenous. Manually processing instead:

1. Downloaded as text from [source](https://codelibrary.amlegal.com/codes/san_francisco/latest/sf_charter/0-0-0-52610)
    - Unchecked Charter, The San Francisco Codes, Preface to the 1996 Charter, Article XVIII, Charter Appendicies, and Appendix A-F
2. Deleted table of contents from Articles
3. Deleted Editor's notes
    - 11 total
    - left in Section 13.110 subsection (c)
4. Deleted Sections which were repealed, reserved, or renumbered
    - 2.102 repealed
    - 2.111 repealed
    - 4.116 repealed
    - 4.130 renumbered
    - 4.138 repealed
    - 6.107 repealed
    - 9.111-1 repealed
    - 15.104 repealed
    - 15.106 repealed
    - 15.108 repealed
    - 16.100 reserved
    - 16.102 reserved
    - 16.123-7 repealed