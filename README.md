# Nasality Analysis Pipeline

**Nasality Analysis Pipeline** is a tool to visually assess nasalization in vowels. It generates plots comparing your **target vowels** to a **baseline vowel** that is known to be oral. By comparing formants across these plots, you can quickly evaluate whether nasalization is present. The script provides an interactive interface where you inspect the data and make your decision with a simple click.

---

## Features

- Generates **waveforms, spectrograms, and spectra** for your target vowels.  
- Compares target vowels (red) with baseline vowels (black) for easy visual analysis.  
- Supports customizable labeling systems for stress and following nasal consonants.  
- Streamlines what would traditionally be a manual, time-consuming process.

---

## Example Interface

<img width="1337" height="752" alt="Analysis Interface" src="https://github.com/user-attachments/assets/a52d6c4c-b34f-4e52-824a-5234f973ae50" />

- **Waveform** of the entire word is shown above.  
- **TextGrid** highlights the specific segments.  
- **Spectrogram** of the word is displayed on the right.  
- **Spectra** of the target vowel are shown in red, with the baseline vowel frequencies below in black.

---

## Usage

1. Provide your **baseline audio** (e.g., [ɐ] in *pug*), which represents the underlying vowel configuration of the nasal /aN/ in Portuguese.  
2. Input your **target vowel** (e.g., /a/ in *panela*, *canavial*) and input directory.  
3. The pipeline uses default parameters suitable for pre-tonic vowels (stress level 1) and following nasal consonants (any of the three Portuguese nasal consonants, separated by `|`).  
4. Inspect the plots and click the appropriate button to classify the vowel as **nasalized**, **oral**, or **uncertain**.

> This pipeline follows the methodology of Seara (2000) and Barbosa & Madureira (2015). Note that it provides a **categorical analysis**, while more advanced quantitative methods exist.

---

## References

- BARBOSA, P. A.; MADUREIRA, S. *Manual de fonética acústica experimental: aplicações a dados do português.* São Paulo: Cortez, 2015.  
- SEARA, I. C. et al. *Estudo acústico-perceptual da nasalidade das vogais do português brasileiro.* 2000.

---

## Contact

For questions or issues, reach me at: **marquettog@gmail.com**
