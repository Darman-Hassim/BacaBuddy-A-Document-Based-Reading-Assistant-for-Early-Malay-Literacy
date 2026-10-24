# Requirements

## Functional requirements (what the system must DO)
1. The system shall allow a user to upload a reading document in image (PNG/JPG), PDF, or plain text (.txt) format.
2. The system shall extract printed Bahasa Melayu text from an uploaded image or PDF document using Optical Character Recognition (OCR).
3. The system shall generate slow, clear spoken Bahasa Melayu audio for each sentence using Text-to-Speech (TTS).
4. The system shall transcribe the child's recorded speech and align it word by word against the reference text using Automatic Speech Recognition (ASR).
5. The system shall generate encouraging feedback in Bahasa Melayu and display a session progress report listing correct and mispronounced words.

## Non-functional requirements (how the system must PERFORM)
1. The system shall transcribe a 10 second child audio recording and return pronunciation scores within 5 seconds. (Performance)
2. The system shall process and store all children's voice recordings locally with zero external internet transmissions during runtime. (Privacy/Security)
3. The system shall extract printed Bahasa Melayu text from clear scanned pages with a Character Error Rate (CER) below 5%. (Reliability)
