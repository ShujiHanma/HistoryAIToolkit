# HistoryAIToolkit

AI toolkit for professional and amateur historians, and for anyone who wishes to contribute to the recording of history by and for the community.

Join our Discord server: https://discord.gg/WvqytcHfnD

## Project goals and scope
Some time ago Audrey come in contact with a group of historians working on interviews of survivors of relevant historical events.   
With the goal of avoiding that this highly valuable first-hand knowledge to be lost down the timeline.  
Interviews are conducted by experienced historians and also by less experienced historians and students.

Experienced interviewers are comfortable asking follow-up questions while maintaining the interviewed comfortable and cooperative.  
However, less experienced interviewers may feel intimidated by an interviewed with a strong presence, being unable to produce good follow-up questions, or risking asking questions that mais make the interviewed uncomfortable.   
Which may led to loss of the opportunity to collect good historical materials.

The goal of the project is to help to avoid thi kind of situation, by:
- Converting the audio of the interviews to text.
- Feed this text to an LLM
- Use that LLM to help to generate "comfortable" and appropriated follow-up questions to help interviewers to progress with confidence.

## Status

The code in here is a proof-of-concept to give you an idea of what we're building. It partially works. The code, documentation, and tests are still a bit unstable and need a lot of love. We need all the help we can get.

## Prototype

The scope of the prototype we hope to complete in the 2-3 weeks following PyCon UK is:

* [ ] Take interview audio in from main.py
  * [ ] Realtime microphone input
  * [x] Mock input from a short audio file simulating a piece of an interview
* [x] Transcribe the interview audio using a (preferably free) transcription package or API
* [x] Save the transcription to a text file
* [ ] Print the transcription to the console
* [ ] Pass the text to a (preferably free) LLM package or API to generate a list of follow-up interview questions
* [ ] Print the questions to the console

## Example Data

To experiment with this project using a recorded interview for test purposes, download one or more of the audio files from:
https://www.kaggle.com/datasets/audreyfeldroy/oral-history-audio-interviews

Sample oral history interviews, some with transcripts we can work with:
* https://wayback.archive-it.org/14173/20200827171043/http://transcribe.oralhistory.nypl.org/

## Getting Started

See docs/getting_started.rst
