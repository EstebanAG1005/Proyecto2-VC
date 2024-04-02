The ETH Pedestrian dataset is reproduced here for convenience only. Full copyright remains with the authors (Andreas Ess, et al.), see http://www.vision.ee.ethz.ch/~aess/dataset/. The converted version is so the associated evaluation code (dbEval) can be used to generate the associated ROC plots. 

The three seq files correspond to the left frames of the three sequences from "Setup 1 (chariot Mk I)". Specifically:
 set00/V000 corresponds to the 999 frame "BAHNHOF" sequence, 
 set01/V000 corresponds to the 451 frame "JELMOLI" sequence, 
 set02/V000 corresponds to the 354 frame "SUNNY DAY" sequence, 
The annotations used are the updated annotations provided by Christian Wojek in Feb. 2010.

Note 1: All evaluation results are reported on pedestrians 50 pixels and up. Note that in their PAMI paper the original authors evaluated on pedestrians 60 pixels and up and pedestrians closer than 15m. Also the three sets were previously evaluated individually. Therefore plots are not directly comparable.

Note 2: Since the labeled bounding boxes appear to have a wide variance in the width, we standardize all bbs to have a width of .41 times the height during evaluation. A thorough discussion of this choice appears in our PAMI 2011 paper.

