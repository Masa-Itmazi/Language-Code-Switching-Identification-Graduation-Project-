# Language-Code-Switching-Identification-Graduation-Project-
This project focuses on developing an AI-based language diarization model designed to accurately segment English-Arabic code-switched speech. Code-switching, the practice of alternating between languages within a single conversation, presents significant challenges for traditional Automated Speech Recognition (ASR) systems, which are typically designed for monolingual speech.


The project addresses these challenges by integrating state-of-the-art technologies such as Whisper and WhisperX models for transcription and alignment, and the speechbrain/lang-id-voxlingua107-ecapa model for language identification. The methodology involves several key steps: audio preprocessing, transcription, word-level alignment, language identification for each segment, and the generation of Rich Transcription Time Marked (RTTM) outputs.


The main objectives of this project include:

Providing a comprehensive review of research in code-switching and language diarization.

Evaluating methodologies, challenges, and advancements in language diarization.

Systematically analyzing available datasets for training and evaluation or creating a new dataset.

Investigating and adapting recent spoken language processing (SLP) and machine learning (ML) approaches for Arabic-English code-switching diarization.

Creating a language diarization system for Arabic-English code-switched speech with acceptable accuracy.

Assessing the system's performance using conventional metrics like Diarization Error Rate (DER), Equal Error Rate (EER), and Balanced Accuracy (BAC).

Refining and optimizing the developed system based on evaluation results.

Potential applications of this work include enhancing ASR systems, virtual assistants, and subtitle generation tools, particularly in code-switched contexts. The system achieved a Diarization Error Rate (DER) of 37.85% using the pretrained VoxLingua107-ECAPA model and 40.09% with a custom-trained model, demonstrating competitive performance in English-Arabic code-switching scenarios.
