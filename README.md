## DATA ANALYSIS
### Sequence clean up with Bioedit
* Open Bioedit window
* Click open and navigate to your sequence folders
* Select the forward and reverse .abi files by holding down Ctrl and selecting both files
* Click on the forward electro chromatogram
* Go to view
* Choose editable sequence 
* Click on the reverse electro chromatogram
* Go to view
* Choose editable sequence 
* Click view again 
* Choose reverse complement 
* Go to edit
* Copy Fasta format 
* Go to forward sequence window (containing nucleotides)
* Click file
* Import from clipboard (two sequences will appear on the window)
* Highlight both sequences (highlight one then Ctrl and click the next)
* Go to sequence 
* Choose Pairwise alignment -> select (Align 2 sequences; allow ends to slide)
* An output box with the aligned sequence will be opened along with a summary report box (which gives identity or similarity)
* Minimize the summary box
* Highlight both sequences in the output box 
* Go to alignment
* Choose create consensus sequence
* On the mode switch from select/slide to Edit – then do the editing ( put the cursor in front of the nucleotide you want to edit, turn on caps lock and type the letter 
* During sequence cleaning you can click the box (View conservation by plotting identities to standard as a dot) 
* This turns all the areas of consensus into dots for easy locations of where there are nucleotide mismatches between forward and reverse sequences.
* Also once you are done cleaning you can click the box (Shade identities and similarities in alignment window)
* change the shade threshold to 60% 
* This allows you to crosscheck an make sure you did not miss any unresolved areas in your sequence 
* After editing, click on the consensus sequence 
* Go to edit
* Copy sequence to clipboard (FASTA Format) 
* Open word document 
* Paste 
* After editing, click on the consensus sequence 
* Go to edit
* Copy sequence to clipboard (FASTA Format) 
* Open word document 
* Paste 
* On consensus title, add the sequence title
* You can then search for you primer tails
* Remove the forward primer tail from your sequence 
* Search for the reverse complement of your reverse primer within your sequence and remove. 
* Your clean sequence is ready for further analysis

### Sequence Analysis with MEGA 7Open MEGA 7 

* Click on the Align drop down menu
* Select build/edit alignment
* Select option create new alignment
* Are you building dna or protein alignment? – select DNA
* Go to your word document containing your sequences and copy all
* Go to the Alignment Explorer dialbox which has opened in MEGA 
* Hit cntrl+v on your keyboard to paste your sequences Once the sequences have appeared on the alignment explorer
* Go to the alignment dropdown menu
* Select alignment type: Clustal W or Muscle 
* Accept the default parameters and click “Compute”
* After alignment is done click on data menu 
* Select Export alignment 
* Select mega format
* Save in a location on your computer where you can find itClose the alignment explorer 
* Go to Phylogeny menu on the main MEGA explorer
* Select the type of tree you want to draw (maximum likelihood, UPGMA, Neighbor joining, maximum parsimony)
* Under the Analysis preferences; 
* change the test of phylogeny to bootstrap method
* Change the number of bootstrap replications to 1000
* Select the model type you want to use (Tamura-Nei, etc)
* Click compute
* Wait for your tree

### Evolutionary Distance and Pcoa
* Go to Distance menu on the main MEGA explorer
* Select “compute pairwise distances”
* Navigate to your folder and select your alignment file  
* Select your preferences and click “compute
* When the distance matrix is created you need to export it in excel 
* Click on the excel tab, the write options box will appear
* Select ‘information to write = distances’
* Select ‘export type = matrix’
* Click “print”
