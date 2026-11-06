# Girish Kulathumani

I work on decoding human biosignals, EEG and wrist EMG, so that a model trained on some people works for the next person. I write about brain–computer interfaces at [GreyLattice](https://greylattice.substack.com).

[GreyLattice](https://greylattice.substack.com) · [Website](https://girish-k01.github.io/) · [LinkedIn](https://linkedin.com/in/girish-kulathumani) · [Google Scholar](https://scholar.google.com/citations?user=hOmai0UAAAAJ&hl=en) · [ORCID](https://orcid.org/0009-0003-9210-0999) · [X](https://twitter.com/gk4913) · [Email](mailto:girishkulathumani@gmail.com) · [CV](https://drive.google.com/file/d/18-F6wiBKDnmmXW_tLZTtVXlL1Y-pcVFF/view?usp=sharing)
<!-- Replace the CV link with the new two-page academic CV once it's uploaded. -->

## Now · November 2026

- **Rebuilding my ML foundations by hand:** micrograd from scratch, and classical EEG decoders before deep ones. Repos marked *from scratch* were written without AI generating the code.
- **Building my own EEG decoding pipeline** for the NeurIPS 2026 EEG/EMG Foundation Challenge (Track 2). <!-- Remove this line if you didn't get registered. -->
- **Looking for research positions** in neurotechnology and biosignal machine learning.

## What I'm working toward

- **Cross-user generalisation:** EEG and wrist sEMG decoders that work on new people with little or no calibration.
- **Personalisation under privacy:** adapting a shared model to each person when the data are as personal as data gets. This is where federated learning, which I've built, meets biosignal decoding.
- **Honest evaluation:** subject-wise splits and leakage checks, because leakage inflates many reported results in this field.

## Writing: GreyLattice

Deep dives on brain–computer interfaces and computational neuroscience. Selected pieces:

- [**Brain Decoding: Toward Real-Time Reconstruction of Visual Perception**](https://greylattice.substack.com/p/glr01): a breakdown of MEG-based decoding of what people see (arXiv:2310.19812).
- [**How We Listen to the Brain, and Why It's So Hard**](https://greylattice.substack.com/p/gl02): invasive and non-invasive recording, their spatial and temporal trade-offs, and where signals degrade.
- [**The Foundations of Computational Neuroscience**](https://greylattice.substack.com/p/gl01): how the field and its core theories developed.
- [**Podcast pilot**](https://greylattice.substack.com/p/glc01): GreyLattice told as a story, mixing philosophy and deep tech.

## Selected work

### HabitatFL: federated learning for wildlife monitoring · Jan–May 2025
Federated multimodal classification of wildlife audio and images, built with Flower and Docker and run on VIT's NVIDIA DGX. Lightweight edge models (MobileNetV3, SqueezeNet) reached 87.65% accuracy on 18.2K spectrograms across 27 classes, and 69.92% on 50K images across 82 classes. [Code](https://github.com/Girish-K01/federated-learning-ai-for-biodiv)
<!-- Say whether these are federated or centralised results, and on which held-out split. -->

### JIGS: parallel encryption and authentication for secure messaging · 2024–2025
A modular secure-messaging pipeline combining ECDH key exchange with nonce-based AES-128 encryption, parallelised for speed, with its security properties checked in ProVerif. First-author paper in *Engineering Research Express* 7(2), 025276 (2025). [Paper](https://iopscience.iop.org/article/10.1088/2631-8695/addd67/meta) · [Code](https://github.com/Girish-K01/jigs-crypto-code-repo)
<!-- If you add the speedup back, state it unambiguously, e.g. "processing time cut by X% (about Nx) on N messages", matching the paper. -->

### Siren: cybersecurity through deception and adaptive analysis · 2024–2025
A deception-based defence that pairs honeypots with ML classification of attacker behaviour. Second-author paper in *Intelligent Computing: Proceedings of the Computing Conference* (2025), pp. 506–519. [Preprint](https://arxiv.org/abs/2406.06225)

### GPU-accelerated financial sentiment analysis · Jan–Apr 2024
Real-time FinBERT sentiment over news streams using Kafka and RAPIDS cuDF on an RTX 2060, cutting latency from about 8 minutes to 10 seconds. [Code](https://github.com/Girish-K01/HPC-Sentiment-Analysis)

## Experience

- **Application Engineer, Accenture**, Chennai · Oct 2025 – Oct 2026. Salesforce. Left to work on neurotechnology full time.
- **Founder and writer, GreyLattice** · Feb 2025 – present.
- **Research Assistant, Secure Systems & AI, VIT** · Jan – May 2024. Work behind JIGS and Siren.
- **Data Science & ML Extern, Google Developers × SmartBridge** · Aug – Nov 2023. Real-time weapon detection with YOLO and Flask.

## Education

BTech, Computer Science and Engineering, VIT Chennai · 2021–2025 · CGPA 8.69/10

## Tools

Python, PyTorch, scikit-learn, Flower, Docker, CUDA, RAPIDS, Kafka, FastAPI, PostgreSQL, Git.
Learning now: MNE-Python and signal processing.

---

Chennai, India (UTC+5:30) · open to relocating
