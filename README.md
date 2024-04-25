# Analyzing Immigration Discourse: A Comparative Study of Language Usage by Right-Wing and Left-Wing Parties in the UK Using the ParlaMint Dataset

## Abstract
This research explores sentiment dynamics in UK parliamentary debates on immigration, utilizing the ParlaMint corpus. We employ sentiment analysis tools like Flair and SetFit to investigate differences in sentiment expression between left-wing and right-wing parties. Our analysis focuses on extracting speeches, annotating them, and performing both whole speech and sentence-level sentiment analysis. Key immigration-related keywords guide the extraction and filtering of texts to assess sentiment polarity. The study aims to identify significant sentiment differences between political affiliations and the words shaping these sentiments. Our findings are expected to contribute to understanding the rhetorical framing of immigration within the context of UK parliamentary discourse, reflecting broader political and social implications.

## Outlines of the Code
1. Extracting Speeches & Merging Features
2. Cleaning the Whole Corpus
3. Choosing Keywords
4. Filter Speeches based on the Keywords
5. Human Annotation
6. Sentiment Analysis - Whole Text/Speech
7. Sentiment Analysis - Sentence & Tokenwise
8. Features Correlation
9. Visualize the Results

## Files
### Not Provided
Some data are not provided because the size is too big, and we can reproduce it by running the google colab :). For examples:

* Generated from the 1st Section `Extracting Speeches & Merging Features`
```
- gb_speech.csv
- es_speech.csv
- gb_person.csv
- es_person.csv
- gb_organization.csv
- es_organization.csv
- gb_orientation.csv
- es_orientation.csv
- gb_compiled-update_orientation.csv
- es_compiled-update_orientation.csv
- gb_compiled.csv (final result of this step)
- es_compiled.csv (final result of this step)
```

* Generated from the 2nd Section: Cleaning the Whole Corpus
```
- gb_clean.csv
```

### Provided
While the other (important) files, are uploaded in this repository. For example:

* Created from the 3th Section: Choosing Keywords
```
data/keywords_DH.txt
```

* Generated from the 4th Section: Filter Speeches based on the Keywords
```
- data/gb_5_filtered_speeches.csv
```

* Generated from the 5th Section & Annotated: Human Annotation
```
- data/gb_for_annotation.csv
```

* Generated from the 6th Section: Sentiment Analysis - Whole Text
```
- result/speech/gb_sentiment_analysis_flair.csv
```

* Generated from the 7th Section: Sentiment Analysis - Sentence & Tokenwise
```
- result/annotation_setfit.csv
- result/annotation_setfit_aug.csv
- result/sentence/all_setfit.csv
- result/sentence/all_setfit_aug.csv
- result/sentence/polarities.csv
- result/sentence/sentence_result.csv (final result of this step)
```

* Generated from the 8th Section: Features Correlation
```
- result/final_results/leftwing_results.csv
- result/final_results/rightwing_results.csv
```

<br>
note that we don't upload all files that is not really necessary as this experiment can be reproduced by using this code (don't forget to check the path. it may need some adjustment)

## Acknowledgement
Thanks are due to our professors, Mikel Iruskieta Quintian, Walt Detmar Meurers and Manex Agirrezabal Zabaleta, for their support and guidance throughout this project. Thank you to our group members Amina, Charlotte, Ibrahim, Mariana, and Zabrina who worked together to do this project. We also would like to thank CLARIN for its project in providing ParlaMint corpus.
