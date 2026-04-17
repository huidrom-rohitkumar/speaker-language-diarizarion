# Speaker and Language Diarization (MTP)

## Overview
This project focuses on designing a system for speaker and language diarization—segmenting continuous audio into homogeneous regions corresponding to individual speakers and languages.

The work is being carried out as part of my Master's Thesis (MTP) at IIT Kharagpur and aims to build a robust pipeline for real-world audio understanding.

---

## Problem Statement
Given a continuous audio stream, the goal is to:
- Identify "who spoke when" (speaker diarization)
- Identify "which language was spoken when" (language diarization)

This problem is challenging due to:
- Overlapping speech
- Background noise
- Speaker similarity
- Language switching within conversations

---

## Approach (Planned Pipeline)

The system is being designed as a modular pipeline:

1. **Audio Preprocessing**
   - Noise handling and segmentation
   - Voice Activity Detection (VAD)

2. **Feature Extraction**
   - Extraction of acoustic features (e.g., MFCCs / filterbanks)

3. **Embedding Generation**
   - Deep speaker embeddings using models such as ECAPA-TDNN

4. **Clustering**
   - Grouping segments based on embedding similarity (e.g., Agglomerative / Spectral clustering)

5. **Language Identification**
   - Classification of segments into languages

6. **Segmentation Output**
   - Final diarized timeline of speakers and languages

---

## System Design Goals
- Robust performance on real-world noisy audio
- Modular architecture for experimentation
- Potential for real-time or near real-time inference

---

## Current Status
🚧 **Ongoing Master's Thesis Project (MTP)**

### Completed
- Problem formulation and literature review
- Identification of suitable model architectures (e.g., ECAPA-TDNN)
- Initial pipeline design

### In Progress
- Feature extraction pipeline
- Embedding model integration

### Planned
- Clustering and segmentation implementation
- Evaluation on benchmark datasets
- Optimization for real-time inference

---

## Applications
- Meeting transcription and analysis
- Call center analytics
- Surveillance and audio intelligence
- Multilingual conversation understanding

---

## Key Challenges
- Handling overlapping speech
- Robustness to noise and reverberation
- Speaker similarity in embeddings
- Accurate segmentation in mixed-language audio

---

## Future Work
- Integration with speech-to-text systems
- End-to-end diarization pipeline
- Deployment on edge devices
- Performance optimization for streaming scenarios

---


---

## Status
🚧 Code, experiments, and results will be added incrementally as the project progresses.
