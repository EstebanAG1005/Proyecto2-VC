The TUD-Brussels Pedestrian dataset is reproduced here for convenience only. Full copyright remains with the authors (Christian Wojek, et al.), see http://www.mis.tu-darmstadt.de/tud-brussels. The converted version is provided so the associated evaluation code (dbEval) can be used to generate the associated ROC plots. 

We suggest reading the README provided with the TUD-Brussels data (avialable in the link above) before making sense of the following. The two seq files correspond to the 002/003 image pairs. Specifically V000 corresponds to the 002 images and V001 corresponds to the 003 images. The annotations are only for the 002 images, and the 003 images are provided only for additional motion information. Hence only V000 is used for evaluation. The used are the updated annotations posted in 04/2010.

Note 1: All evaluation results are reported on pedestrians 50 pixels and up. Note that the original authors evaluated on pedestrians 48 pixels and up. Therefore plots may vary slightly.

Note 2: Since the labeled bounding boxes appear to have a wide variance in the width, we standardize all bbs to have a width of .41 times the height during evaluation. A thorough discussion of this choice appears in our PAMI 2011 paper.
