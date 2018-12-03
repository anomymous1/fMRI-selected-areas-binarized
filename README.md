# fMRI-selected-areas-binarized
fMRI selected areas binarized

Contains files for all 8 subjects corresponding to regions 3 - 16, 59 -62, and 81 - 90. Each file has the voxels correponding to the subject and region, plus a final column containing the binarized imageability data for each word.

The files are post-processed for hemodynamic response delay, words with no imageability ratings have been excluded and the the imageability ratings in the last column have been binarized.

An additional file containing the selected voxels using random forests paired with ELMo embeddings is also added. The first 640 columns of that file correspond to the voxels, followed by 1024 ELMo columns and finally, the binarized imageability metric is presented in the last column.

Some of the files had to be compressed because they were too big.

Participant 2 misses the file for Region 60.
