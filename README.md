# 1yfpA
Glycosylating YFP

<p align="center">
  <img src="1yfpA.png" width="500"/>
</p>

We are not the first to try designing glycosylation sites into a GFP based molecule. In "Expression of a glycosylated GFP as a bivalent reporter in exocytosis" (DOI:10.1007/s00299-009-0799-7), three N-linked glycosylation sites were engineered into a GFP based molecule. These sites were residues 80, 133, and 172. The mutant GFP with the mutation at residue 80 did not fold. The one with the mutation at residue 133 folded and was glycosylated. The one with the mutation at residue 172 was mutated with some additional inserted residues. It folded but was not glycosylated. This paper was nice in that it clearly illustrated each of the possible outcomes of engineering glycosylation sites into an existing protein.

The howto may be found in 1yfpA.steps. The predictions may be found in gly.out.

We note that gly21.py does not suggest residue 80 as a potential glycosylation site. This was the mutation site that caused the molecule to not fold. However gly21.py does suggest residues 133 and 172 as potential glycosylation sites. Residue 172 was not engineered as point mutations so we would not like to make any conclusions about our prediction at this location. The protein with the mutation at residue 133 not only folded but was glycosylated as well.

We note that at least one prediction will likely not be glycosylated with an outward pointing glycan chain as the sidechain is pointing inward toward YFP's solvent pocket. This is residue 203. A more sophisticated solvent accessibility algorithm or some other method of telling the difference between the inside and the outside of the protein might be desireable.

