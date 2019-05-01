# Gen 606 Phylogenetics Exercise


The purpose of this exercise is to familiarize you with the very basics of phylogenetic methods. There are a number of courses that expand upon this both at UNH and beyond. There are also some great tutorials that might be interesting for some: http://treethinkers.org/tutorials/

#### SOFTWARE USED

- MUSCLE
	
	- http://www.drive5.com/muscle/manual/ 
- GBLOCKS
	
	- http://molevol.cmima.csic.es/castresana/Gblocks/Gblocks_documentation.html
- PhyML	

	- http://www.atgc-montpellier.fr/download/papers/phyml_2010.pdf
	- http://www.atgc-montpellier.fr/phyml/faq.php

- eteToolkit

	- http://etetoolkit.org/treeview/
---

#### Steps for analysis

- Navigate to http://phylogeny.lirmm.fr/phylo_cgi/phylogeny.cgi

- Click Phylogeny Analysis > "a la carte"

#### Set up your Analysis

- name your pipeline

- Check Multiple Alignment, Alignment Curation, Construction of Phylogenetic Tree, Visualization
	- Alignment > MUSCLE
	- Curation > GBLOCKS
	- Tree > PhyML
	- Visualization - TreeDyn

- At the bottom of the page, check Run Work Flow > Step by Step. 

- Click Create workflow

- Paste in your nucleotide sequences, which can be found here: https://github.com/macmanes-lab/G606_Phylogenetics/blob/master/nucleotides.faa then click submit

#### Generating Results

- Alignment

	- What do the different colors mean?
	- Can you infer something about the relationship between the species based on this alignment?
	- when done, scroll to bottom of page and click "Next Step"
	

- Curation

	- Click option under 'For a more stringent selection' > Submit
	- What did curation do?
	- Why might this be important? 
	- when done, scroll to bottom of page and click "Next Step"

- PhyML Tree Building
	- There are numerous settings for Phylogeny building. For now, lets just leave to the default. 
	- Click Submit
	- Once done, click "Next Step"

- Tree Visualization
	- Submit
	- Click "Reroot (outgroup)"
	- Click Drosophila, on the tree above
	- We can look at the tree here, but it is easier to see in the next step.
	
- Using eteToolkit
	- Go to eteToolkit: http://etetoolkit.org/treeview/
	- Paste in Rooted Newick Tree (Tree rendering tab, near bottom, click "Rooted tree in Newick format")
	- What does this phylogeny mean?
	- Red numbers?
	- Why different branch lengths?
	- Are there cases where the hypothesized relationships don't make sense? Why?


---

#### Now repeat the analysis using the Protein sequences
- found here: https://github.com/macmanes-lab/G606_Phylogenetics/blob/master/prot.faa


#### Additional Exercises

There are several additional exercises that could be interesting. Many of these include changing the specific parameters or deleting steps (for instance, what happens when you don't run GBLOCKS?). Try these if interested.
 
There is also a more complicated web interface for doing phylogenetics. These analyses are done on https://www.phylo.org/. Here you can do VERY complicated analyses like you might do for a publication. Try this stuff out if you are interested. 
