# Polymers

Geometries and COSMO-files (from Gaussian 16) of n-mers of the following polymers:

+ Poly(ethylene glycol) [peg]
+ Poly(lactic acid) [pla]
+ Poly(lactic-co-glycolic acid), model 1 [plga1]
+ Poly(lactic-co-glycolic acid), model 2 [plga2]
+ Poly(vinylpyrrolidone) [pvp]

These liquid-phase geometries were (more or less randomly) extracted from MD simulations of systems of longer polymer chains. Although they are still just snapshots in a sea of billions possible conformations, this approach eliminates the need for any additional geometry optimization or refinement at QM level, in my opinion.

For each polymer, we extracted a representative trimer, tetramer, and pentamer, which allows for generating sigma-profiles based on averaging more different monomer units.

Geometries of other polymer types can be directly adopted from the Amsterdam Modeling Suite Database (https://www.scm.com/doc/COSMO-RS/COSMO-RS_Databases.html#adfcrs-polymers-2019; only trimers).

Note: plga1 and plga 2 differ in both geometry and ratio of LA/GA units.
