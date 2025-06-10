# Aviation Communication Corpus (ATC-420)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15549416.svg)](https://doi.org/10.5281/zenodo.15549416)

This dataset contains 420 audio recordings (2 hours) collected from LiveATC.net, along with manual transcriptions and force-alignment annotations created by our research team. The corpus was developed to support academic research on automatic speech recognition (ASR) and phonetic alignment in aviation communication.

## 📁 Repository Structure

```bash
.
├── raw/
│   ├── RJAA-APP-20240528-001.wav
│   ├── RJAA-APP-20240528-001.txt
│   ├── ...
│   └── RJAA-APP-20240528-420.wav
│       RJAA-APP-20240528-420.txt
├── annotation/
│   ├── RJAA-APP-20240528-001.TextGrid
│   ├── ...
│   └── RJAA-APP-20240528-420.TextGrid
```

- `raw/`: Contains 420 `.wav` recordings sourced from LiveATC.net and their corresponding manually transcribed `.txt` files.
- `annotation/`: Contains `.TextGrid` files generated using the [Montreal Forced Aligner](https://montreal-forced-aligner.readthedocs.io/), aligned with our transcriptions.

## 🧾 Licensing and Permissions

This dataset is released for **academic, non-commercial use only**.

> **Source and Acknowledgement**:  
> The original recordings were obtained from [LiveATC.net](https://www.liveatc.net) with permission for academic research.  
> Transcriptions and annotations were produced by our team as part of an academic study.  
> 
> Please include the following acknowledgement in any publication or derivative work:
> 
> > "Original audio recordings were obtained from LiveATC.net with permission. Transcriptions and annotations were created by the authors. This dataset is released for academic, non-commercial use only."

## 📚 Citation

If you use this corpus in your work, please cite it as:

(To be completed upon publication)
> Tang, L. (2025). Xxxxxxxxx

## 📬 Contact

For questions or collaboration, please contact:  
**Li Tang** (tangli19961030@gmail.com)
**Veronica Khaustova** (veranika.aizu@gmail.com)
**Julián Villegas** (julian@u-aizu.ac.jp)

---
**DOI**: `10.5281/zenodo.15549415`
