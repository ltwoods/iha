This directory contains the following subdirectories and files:

README.txt				This file.
wlaslalt_train_info_clean.csv		Our cleaner WLASL-alt train split info.
wlaslalt_val_info.csv			Our cleaner WLASL-alt val split info.
wlaslalt_test_info.csv			Our cleaner WLASL-alt test split info.
100_classes/all_info_clean_100.csv	Our cleaner WLASL-alt all info for 100 classes.
100_classes/train_info_clean_100.csv	Our cleaner WLASL-alt train split info for 100 classes.
100_classes/val_info_clean_100.csv	Our cleaner WLASL-alt val split info for 100 classes.
100_classes/test_info_clean_100.csv	Our cleaner WLASL-alt test split info for 100 classes.

Each wlaslalt_*_info_clean.csv file contains the following fields:
video_id,class,sequence_length

Each *_classes/*_info_*.csv file contains the following fields:
video_id,class

where

`video_id` is the original WLASL dataset video ID
`class` is the replacement class label after incorporating the WLASL-alt changes and renumbering
`sequence_length` is the number of frames per sequence with valid data before being padded.
