# AU-OTLD-blq
A set of blq files that contain harmonic parameters for 11 major tidal constituents modelled at 360 Australian GNSS sites' locations using a variety of ocean tide models and Greens functions (Earth models). The blq files were generated with CARGA software at the Free Ocean Tide Loading Provider (http://holt.oso.chalmers.se/loading). The ocean tide loading displacements timeseries could be reconstructed using HARDISP software utility from IERS software package. 
Files naming conventions were design to contain all the important parameters:
- dataset key [GA | None], convenient when working with multiple datasets;
- ocean tide model [FES2004 | FES2012 | FES2014b | GOT4.10c | GOT4.8 | TPXO8_atl | TPXO9_atl | TPXO9v2a_atl];
- Greens function [GBe | PREM | STW105 | S362ANI];
- dissipation correction applied [d | None];
- spatially varying water density and compressibility corrections [c | s | None]. Both applied [c] or only spatially varying water density correction applied [s];
- No water conservation correction is applied to conserve water mass [w | None];
- Centre of Mass correction [CM | CE] present [CM] or not [CE]. CM blq files should only be used with JPL native orbit and clock products solutions, CE in all other cases (CODE, ESA, IGS etc. products solutions).
