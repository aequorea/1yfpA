# 1yfpA
Glycosylating YFP

<p align="center">
  <img src="1yfpA.png" width="500"/>
</p>

We are not the first to try designing glycosylation sites into a GFP based molecule. In "Expression of a glycosylated GFP as a bivalent reporter in expcytosis" (DOI:10.1007/s00299-009-0799-7), three N-linked glycosylation sites were engineered into a GFP based molecule. These sites were residues 80, 133, and 172. Residue 80 did not fold. Residue 133 folded and was glycosylated. Residue 172 was mutated with some additional inserted residues. It folded but was not glycosylated. This paper was nice in that it clearly illustrated each of the possible outcomes of engineering glycosylation sites into an existing protein.

The howto may be found in 1yfpA.steps. The predictions may be found in gly.out. gly20 predicts 81 potential glycosylation sites.

We note that gly20.py does not suggest residue 80 as a potential glycosylation site. This was the site that did not fold. However gly20.py does suggest residues 133 and 172 as potential glycosylation sites. Although residue 172 was not engineered as point mutations, we note that mutations in the vicinity of 172 did not result in a misfolded protein, and residue 133 not only folded but was glycosylated as well.

We note that at least one prediction will likely not be glycosylated with an outward pointing glycan chain as the sidechain is pointing inward toward YFP's solvent pocket. This is residue 203. A more sophisticated solvent accessibility algorithm or some other method of telling the difference between the inside and the outside of the protein might be desireable. Meanwhile what to do about residues with sidchains pointing toward cavities is being resolved manually. In this case, it might be interesting to see what happens if the mutation is made anyway since it might result in a molecule with different spectral properties.

