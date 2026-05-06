k. Look at your UPGMA tree: Can you agree that *Carica papaya* is most closely related to *Passiflora edulis* out of the six plants that you have looked at? (The sequences in the alignment are simulated, but we made sure that the closest relatives for the six plants are all accurate).

l. Is Broccoli more closely related to Papaya or to Tapioca? To Tapioca or to Passionfruit?

m. Can you represent your tree in the newick format? Once you have done it, open your newick file in a tree visualisation software. We recommend FigTree (download from https://github.com/rambaut/figtree/releases). You may be asked to install Java in order to use it, which should be easy to do after a quick Google. If you prefer not to do that, you can try the software iTOL instead, which runs in your browser (https://itol.embl.de/).

&lt;page_number&gt;5&lt;/page_number&gt;

---


## Page 6

Try different visualization options (e.g. rotate branches, show a polar display) to make sure they all represent the same tree.

You have now drawn your first phylogenetic tree using UPGMA. UPGMA is a great method to learn how to go from DNA sequence to tree. However, UPGMA has some limitations: For instance, by splitting the distance between the leaves in half, UPGMA assumes that all the lineages in the tree follow the same evolutionary clock (the ultrametricity assumption mentioned above). This is sometimes a good approximation, but it is rarely accurate in natural systems where different organisms often evolve at different speeds. Think about bacteria: they can sometimes evolve antibiotic resistance within a few generations, while mammals cannot evolve that quickly.

n. Can you think of an example of two groups of sequences that, while homologous, do not evolve at the same rate? If you can't think of a specific, real case, try to imagine one based on what you know.

Next time, you will learn how some more advanced tree-building methods, such as Maximum Parsimony and Maximum Likelihood, have overcome some of the limitations of UPGMA.

o. The same data was used to make a Neighbour-Joining tree, and the resulting phylogeny looks as follows:

(Carica:0.01458, ((Passiflora:0.01250,Manihot:0.05417):0.09167, (Cannabis:0.01042,Humulus:0.00625):0.13750):0.02917,Brassica:0.08542);

Paste this into a plain text file and open it in FigTree and try various displays. What differences do you see between your tree and this one? How does this reflect differences between the UPGMA and Neighbour-Joining Algorithms?

p. Some phylogenetic analyses (e.g. see https://en.wikipedia.org/wiki/Rosids) indicate that the root in this tree should be between at the branch that separates Brassica and Carica with everything else. Using your unrooted tree as a reference (use the radial display if that helps), try drawing your tree by hand as a rooted tree by placing the root in the correct branch. In order to check if your rooted tree is correct, select in FigTree the branch and click “Reroot”. Do the results differ? Based on the UPGMA tree, is the group Brassicales (including Brassica and Carica) closer to Rosales (including Humulus and Cannabis) or to Malpighiales (including Manihot and Passiflora)? And based on the Neighbour-Joining tree?

&lt;page_number&gt;6&lt;/page_number&gt;
