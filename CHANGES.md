# VERSIONS HISTORY #

Changes in version 0.1.3 (2020121100) - Hurray project week!
---------------------------------------------------
- Let admins copy files to content bank too (#11)
- Migrate depending on a subset of content-types (#19)
- Allow async module deletes (#14)
- Other fixes and improvements:
  * Set grade type to None when maxgrade is 0 (#7)
  * Rawscore and maxscore can not be null (#8)

Thanks to Eric Merrill, GaRaOne and Alexander Bias and all the contributors who have created issues, fixes and improvements.

Changes in version 0.1.2 (2020062400) - Welcome Beta
---------------------------------------------------
- Some migration errors fixes:
  * Use "enable skipping" from the competency API to avoid migration failed error (#1)
  * Set contextid properly in event trigger (#3)
  * Replace wrong table name and hardcoded prefix