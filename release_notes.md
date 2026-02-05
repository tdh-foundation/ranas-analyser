#RELEASE NOTES

##v1.0.1
User changes:
- In the "Introduction" sheet, the signalling of invalid values in red for "Interface language" and "Chart language" was fixed. (Their conditional formatting conditions had been mistakenly copied from another cell.)
- In the "demo version", the "data" sheet was simplified (removal of irrelevant data columns).
- The first public "Legacy" version of the RANAS Analyser was produced.

Developer changes:
- Realised that, to optimise computation, dynamic arrays and volatile functions (INDIRECT()) should be computed in-sheet, not in the Name Manager, otherwise they will be recomputed on each call. They can still be named in the Name Manager (to make other formulae more readable) by referencing the in-sheet spilled range with # (e.g., $A$1#).
- In consequence, sheet "dataCopy" was created, where dataFirstRow, dataRefCol, dataHeaders and dataRange are computed (and defined in the Name Manager), and then referenced by other formulae.
- Other dynamic arrays (e.g., behaviourData1, behaviourScore, isDoer) are computed in HiddenTables, then defined in the Name Manager.
- Many formulae (in-sheet, conditional formatting rules) were redesigned to avoid the use of INDIRECT() (volatile function, computationally expensive).
- More generally, all formulae were reviewed and optimized if possible.
- Some user-defined functions were introduced in the Name Manager to simplify in-sheet formulae. (Only possible in the Excel 365 version.)
- In HiddenTables, generalVariablesTable was replaced with manualEntryVariablesTable. This table now only contains variables whose values are manually defined in it (their formula in the Name Manager being a lookup in this table).
- A new hidden table was introduced, structuredFormulaeTable, to list structured versions of formulae (except the most trivial ones) for named ranges, user-defined functions, conditional formatting rules and data validation rules. A column is also used to store "Legacy" versions of some formulae.
- For in-sheet formulae that require a "Legacy" replacement, the formulae are stored as text near the corresponding cells, or above/below the table, and highlighted in yellow. This is to facilitate the production of the "Legacy" version of the file when adapting it from the "Excel 365" version.
- Errors listed in the errorMessagesTable are now defined in the Name Manager and their value just called by name in the "condition" column. They can thus be easily reused to simplify formulae (e.g., errorNoDataSheet, which is used in many other formulae).
- The complicated formula that was used to compute the recommended cutoff level was abandoned and replaced with a new hidden table, recommendedCutoffTable, from which cutoffLevelRecommended is now computed, making it conceptually simpler.

##v1.0.0
- First public version of the RANAS Analyser.
<img width="3258" height="636" alt="image" src="https://github.com/user-attachments/assets/caa19630-4d5c-48c5-8250-1f68e914259b" />
