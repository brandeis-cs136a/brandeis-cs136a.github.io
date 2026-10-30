---
layout: page
title: 2026
---

*Last updated: {{ "now" | date: "%B %e %Y" }}*

Read the [FULL SYLLABUS](syllabus).

{% include_relative course-intro.md %}

{% include_relative at-a-glance.md %}

## Course Topics

(the topic list below is tentative; coverage may shift depending on the pace and depth of in-class discussion)

<!-- TODO: re-link slides as they are revised from 2025 decks -->

### Module 1: Foundations

1. Course overview
1. Sound: phonetics ([Chapter 15 of SLP3](https://web.stanford.edu/~jurafsky/slp3/15.pdf)) and digital signal processing (Fourier's heat equation, Fourier transform, convolution)
1. Probability, statistics (Gaussian) and statistical modeling (MLE, [Chapter 3.1](https://web.stanford.edu/~jurafsky/slp3/3.pdf))
1. Linear algebra: vectors, dot product and cosine similarity, matrix and vector spaces ([Chapter 5.3 - 5.4](https://web.stanford.edu/~jurafsky/slp3/5.pdf))
1. ASR evaluation: WER ([Chapter 2.9](https://web.stanford.edu/~jurafsky/slp3/2.pdf), [Chapter 16.6](https://web.stanford.edu/~jurafsky/slp3/16.pdf))

### Module 2: Classical ASR

1. Statistical sequence modeling: Markov chains, HMM, and Viterbi ([Chapter 18.1 - 18.4](https://web.stanford.edu/~jurafsky/slp3/18.pdf), [Appendix A](https://web.stanford.edu/~jurafsky/slp3/A.pdf))
1. Acoustic model: GMM, HMM-GMM, and EM
1. Information theory: n-gram LM ([Chapter 3](https://web.stanford.edu/~jurafsky/slp3/3.pdf), [Appendix C](https://web.stanford.edu/~jurafsky/slp3/C.pdf))

### Module 3: Neural ASR

1. Perceptron, MLP, and first AI winter ([Chapter 6](https://web.stanford.edu/~jurafsky/slp3/6.pdf))
1. Neural renaissance: backpropagation, Boltzmann machine, ReLU ([Chapter 6](https://web.stanford.edu/~jurafsky/slp3/6.pdf))
1. Neural speech-to-text: CTC, RNN-T ([Chapter 16.5](https://web.stanford.edu/~jurafsky/slp3/16.pdf))
1. Multilingual ASR: Unicode and normalization ([Chapter 2.3](https://web.stanford.edu/~jurafsky/slp3/2.pdf), [UAX#15](https://www.unicode.org/reports/tr15/))
1. Neural sequence models: RNN, LSTM ([Chapter 14](https://web.stanford.edu/~jurafsky/slp3/14.pdf))
1. Neural frontend: CNN, residual networks ([Chapter 16.2](https://web.stanford.edu/~jurafsky/slp3/16.pdf))
1. Transformer: attention, self-attention vs. CNN, transformer architectures ([Chapter 7](https://web.stanford.edu/~jurafsky/slp3/7.pdf))

### Module 4: Frontiers

1. Generative speech: Brownian motion, diffusion, modern TTS ([Chapter 17](https://web.stanford.edu/~jurafsky/slp3/17.pdf))
1. Other speech tasks and SotA
1. Speech-language models: early/late multimodal fusion, omni-LLMs ([Chapter 8](https://web.stanford.edu/~jurafsky/slp3/8.pdf))

## Class Schedule

(the schedule ahead is tentative; slide decks are on Moodle and need a Brandeis login)

| Date | Topic | Slides |
|------------|-------|--------|
| 2026-08-28 | Course overview | [Slides](https://moodle.brandeis.edu/pluginfile.php/475377/mod_resource/content/4/01-intro.html) |
| 2026-09-01 | Sound I | [Slides](https://moodle.brandeis.edu/pluginfile.php/478299/mod_resource/content/2/02-sound-i.html) |
| 2026-09-04 | Sound II | [Slides](https://moodle.brandeis.edu/pluginfile.php/478300/mod_resource/content/1/03-sound-ii.html) |
| 2026-09-08 | Sound III<br>Probability I | [Slides](https://moodle.brandeis.edu/pluginfile.php/480078/mod_resource/content/3/W03-1-sound-iii.html)<br>[Slides](https://moodle.brandeis.edu/pluginfile.php/480086/mod_resource/content/3/W03-2-prob-i.html) |
| 2026-09-10 | Probability II | [Slides](https://moodle.brandeis.edu/pluginfile.php/480087/mod_resource/content/4/W03-3-prob-ii.html) |
| 2026-09-15 | Evaluation<br>Statistical modeling I | [Slides](https://moodle.brandeis.edu/pluginfile.php/481855/mod_resource/content/1/W04-1-eval.html)<br>[Slides](https://moodle.brandeis.edu/pluginfile.php/481856/mod_resource/content/5/W04-2-stat-i.html) |
| 2026-09-18 | Statistical modeling II | [Slides](https://moodle.brandeis.edu/pluginfile.php/481857/mod_resource/content/6/W04-3-stat-ii.html) |
| 2026-09-22 | HMM-GMM I | [Slides](https://moodle.brandeis.edu/pluginfile.php/483318/mod_resource/content/2/W05-1-hmmgmm-i.html) |
| 2026-09-25 | HMM-GMM II<br>SSH | [Slides](https://moodle.brandeis.edu/pluginfile.php/483319/mod_resource/content/2/W05-2-hmmgmm-ii.html)<br>[Slides](https://moodle.brandeis.edu/pluginfile.php/483316/mod_resource/content/2/W05-3-ssh.html) |
| 2026-09-29 | HMM-GMM III | [Slides](https://moodle.brandeis.edu/pluginfile.php/485052/mod_resource/content/3/W06-1-hmmgmm-iii.html) |
| 2026-10-02 | Classical ASR | [Slides](https://moodle.brandeis.edu/pluginfile.php/485055/mod_resource/content/2/W06-2-classical.html) |
| 2026-10-06 | Information theory | [Slides](MOODLE-URL-W07-1-infotheory-i) |
| 2026-10-09 | Midterm | |
| 2026-10-16 | Information theory II<br>SLURM in practice | [Slides](https://moodle.brandeis.edu/pluginfile.php/487976/mod_resource/content/4/W08-1-infotheory-ii.html)<br>[Slides](https://moodle.brandeis.edu/pluginfile.php/487977/mod_resource/content/4/W08-2-slurm.html) |
| 2026-10-20 | ASR evaluation discussion<br>Beyond transcription: other speech tasks and project topics | (no slides)<br>[Slides](https://moodle.brandeis.edu/pluginfile.php/489188/mod_resource/content/5/W09-2-project-i.html) |
| 2026-10-23 | Neural acoustic model I | [Slides](https://moodle.brandeis.edu/pluginfile.php/489718/mod_resource/content/5/W09-3-neural-am-i.html) |
| 2026-10-27 | Neural acoustic model II | [Slides](https://moodle.brandeis.edu/pluginfile.php/491038/mod_resource/content/6/W10-1-neural-am-ii.html) |
| 2026-10-30 | Neural seq2seq I | [Slides](https://moodle.brandeis.edu/pluginfile.php/491181/mod_resource/content/6/W10-2-seq2seq-i.html) |
| 2026-11-03 | Unicode<br>Neural seq2seq II | |
| 2026-11-06 | Neural seq2seq III  | |
| 2026-11-10 | Project pitches<br>Neural seq2seq IV | |
| 2026-11-13 | Neural front-end | |
| 2026-11-17 | Synthesis | |
| 2026-11-20 | Transformers I | |
| 2026-11-24 | Transformers II | |
| 2026-12-01 | LLM and MMLM | |
