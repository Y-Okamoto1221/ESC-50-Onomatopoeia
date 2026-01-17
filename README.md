# ESC-50-Onomatopoeia

ESC-50-Onomatopoeia is the onomatopoeic word dataset including 18,600 onomatopoeic words for 31 kinds of environmental sounds (e.g., dog, keyboard typing) included in ESC-50 [1].
The ESC-50-Onomatopoeia also contains self-reported confidence scores to the onomatopoeic words, which can be used to evaluate the appropriateness of onomatopoeic words.
This dataset is designed and collected for researches on environmental sound recognition and synthesis using onomatopoetic words. If you use the ESC-50-Onomatopoeia, please cite this GitHub repository.  

## Contents

The ESC-50-Onomatopoeia dataset consists of the following contents:

- Onomatopoeic words for environmental sounds

	We collected a total of 18,600 onomatopoeic words for for 31 kinds of environmental sounds (e.g., dog, keyboard typing). Each onomatopoeic word was collected from Japanese speakers in katakana, which is a Japanese syllabary. We converted each onomatopoeic word written by katakana into the English phoneme representation, which follows the conversion rule of [katakana2accphrase.csv](https://github.com/Y-Okamoto1221/ESC-50-Onomatopoeia/katakana2accphrase.csv).

- Self-reported confidence scores

	We collected 18,600 confidence scores for onomatopoeic words workers themselves transcribed. The self-reported confidence score enables us to evaluate the appropriateness of onomatopoeic words on the basis of the judgement of the person giving the onomatopoeic words.

- WorkerID

	The dataset includes anonymized IDs of workers who gave onomatopoeic words and confidence scores.

Onomatopoeic words of English phoneme representation and Japanese syllabary are included in this dataset.

**Note that ESC-50-Onomatopoeia does not contain sound files, which can be obtained from [here](https://github.com/karolpiczak/ESC-50).**


## File format

The ESC-50-Onomatopoeia consists of following one csv file:

- ESC_50_Onomatopoeia.csv
	``[Worker ID, Wav name in ESC-50, Onomatopoeic words by Japanese syllabary, Onomatopoeic words by English phoneme representation, Self-reported confidence score]``

## Terms of use

The ESC-50-Onomatopoeia may be used for 
- Research by academic institutions
- Non-commercial research, including research conducted within commercial organisations
- Personal use.

If you want to use for commercial purposes, please contact Yuki Okamoto (y-okamoto@ieee.org).
Re-distribution is not permitted, but you can use a part of this dataset (e.g., 〜10 onomatopoeic words) in your website or blog post.
Please cite this paper when you use this dataset in your research paper, blog post, and preprint.

### Citation
```
@misc{esc50_onomatopoeia,
  title        = {ESC-50-Onomatopoeia},
  author       = {Yuki Okamoto},
  year         = 2026,
  note         = {\url{https://github.com/Y-Okamoto1221/ESC-50-Onomatopoeia}}
}
```

## Acknowledgment

This work was supported by JSPS KAKENHI Grant Number 22KJ3027. 


## References
[1] K. J. Piczak, "ESC: Dataset for Environmental Sound Classification," In proceedings of the 23rd Annual ACM Conference on Multimedia, pp. 1015-1018, 2015.