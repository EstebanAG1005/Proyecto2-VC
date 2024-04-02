The Daimler Pedestrian dataset is reproduced here for convenience only. Full copyright remains with the authors (M. Enzweiler and D. M. Gavrila), see http://www.gavrila.net/Research/Pedestrian_Detection/Daimler_Pedestrian_Benchmark_D/Daimler_Pedestrian_Detection_B/daimler_pedestrian_detection_b.html
The converted version is so the associated evaluation code (dbEval) can be used to generate the associated ROC plots. 

Note 1: All evaluation results are reported on pedestrians 50 pixels and up. All bicyclists, motorcyclist, pedestrian groups and partially visible pedestrians in the original annotation were set to "ignore" and not included in the evaluation, simplifying the detection task somewhat.

Note 2: Since the labeled bounding boxes appear to have a wide variance in the width, we standardize all bbs to have a width of .41 times the height during evaluation. A thorough discussion of this choice appears in our PAMI 2011 paper.

Note 3: The Daimler dataset is grayscale unlike the other datasets. As such, only a subset of the detection algorithms were applicable (those that did not rely on color information).
