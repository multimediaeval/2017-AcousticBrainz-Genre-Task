# Results

The final submissions are (115 runs):

* `baseline` (8 runs): 2 runs for task1 on all 4 datasets.
* `dbis` (40 runs): 5 runs for task1 and 5 runs for task2 on all 4 datasets.
* `icsi` (15 runs): 5 runs for task1 on 3 datasets (no `allmusic`).
* `jku` (32 runs): 3 runs for task1 and 5 runs for task2 on all 4 datasets.
* `kart` (16 runs): 4 runs for task1 on all 4 datasets.
* `samirit` (4 runs): 1 run for task1 on all 4 datasets.

For the baseline:

* `run1` is random, following the distribution of labels found in the development sets.
* `run2` always predicts the most popular genre in the development set.

The solid grey lines mark the performance of the random baseline, and the dotted lines mark the performance of the popularity-based baseline. The numbers indicate whether the run belongs to task1 or task2.

All results are also available in a [CSV file](allscores.csv). 

## Per-track average metrics
### Per-track Precision vs Recall for all labels

![AllMusic - per track - all labels](png/320x240_allmusic_Rtrackall.png) ![Discogs - per track - all labels](png/320x240_discogs_Rtrackall.png)

![Lastfm - per track - all labels](png/320x240_lastfm_Rtrackall.png) ![Tagtraum - per track - all labels](png/320x240_tagtraum_Rtrackall.png)

### Per-track Precision vs Recall for genre labels

![AllMusic - per track - genre labels](png/320x240_allmusic_Rtrackgen.png) ![Discogs - per track - genre labels](png/320x240_discogs_Rtrackgen.png)

![Lastfm - per track - genre labels](png/320x240_lastfm_Rtrackgen.png) ![Tagtraum - per track - genre labels](png/320x240_tagtraum_Rtrackgen.png)

### Per-track Precision vs Recall for subgenre labels

![AllMusic - per track - subgenre labels](png/320x240_allmusic_Rtracksub.png) ![Discogs - per track - subgenre labels](png/320x240_discogs_Rtracksub.png)

![Lastfm - per track - subgenre labels](png/320x240_lastfm_Rtracksub.png) ![Tagtraum - per track - subgenre labels](png/320x240_tagtraum_Rtracksub.png)

## Per-label average metrics
### Per-label Precision vs Recall for all labels

![AllMusic - per label - all labels](png/320x240_allmusic_Rlabelall.png) ![Discogs - per label - all labels](png/320x240_discogs_Rlabelall.png)

![Lastfm - per label - all labels](png/320x240_lastfm_Rlabelall.png) ![Tagtraum - per label - all labels](png/320x240_tagtraum_Rlabelall.png)

### Per-label Precision vs Recall for genre labels

![AllMusic - per label - genre labels](png/320x240_allmusic_Rlabelgen.png) ![Discogs - per label - genre labels](png/320x240_discogs_Rlabelgen.png)

![Lastfm - per label - genre labels](png/320x240_lastfm_Rlabelgen.png) ![Tagtraum - per label - genre labels](png/320x240_tagtraum_Rlabelgen.png)

### Per-label Precision vs Recall for subgenre labels

![AllMusic - per label - subgenre labels](png/320x240_allmusic_Rlabelsub.png) ![Discogs - per label - subgenre labels](png/320x240_discogs_Rlabelsub.png)

![Lastfm - per label - subgenre labels](png/320x240_lastfm_Rlabelsub.png) ![Tagtraum - per label - subgenre labels](png/320x240_tagtraum_Rlabelsub.png)

