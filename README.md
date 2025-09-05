# AI-Assisted Forensic Transcription for Asylum Interviews

## The Challenge
The Swiss Federal Office for Migration (SEM) on a daily basis conducts interviews with asylum applicants in order to determine their refugee status. What’s being discussed in these interviews contains sensitive personal information – effecting in content classification as confidential. The legal issues involved are complex and in order to determine an individual's refugee status, the SEM case-workers must take into account not only the relevant internal policy guidelines, but also nuanced cultural contexts, general aspects of human communication, and credibility assessments in particular. 

Basis for such an assessment is an accurate transcription of everything that is being said, as well as how it is being said. By contrast, today's widely available and popular speech to text transcription tools "smoothen" the transcribed content for easier consumption, thereby sacrifising the individual speech pattern and diction.

## The Objective
In order to be useful for SEM, the interview transcription output must reliably reflect the recording as accurately as possible: The tool has to transcribe exactly what is being said, including mistakes such as mispronunciations, false starts, auto-corrections, grammatical errors and hesitation markers. Fillers, halting speech patterns and pauses must be visualized.

### Key Requirements:
- Handle Switzerland's official languages (German, French, and Italian)
- Optionally support foreign languages (e.g., Farsi, Turkish, various Arabic dialects)
- Correctly transcribe names (personal, organizational, and geographical) and abbreviations
- Highlight expressions with multiple meanings
- Apply proper punctuation rules
- Distinguish between different speakers
- Recognize human voices from background noise
- Reduce post-editing time compared to existing manual processes

## Evaluation Criteria
Forensic-grade speech-to-text - preserving every "um," false start, pause, etc. - has highest priority.

### Primary Features (Must-Have)

#### Official Language Support
- Can it handle German, French, or Italian?
- Can it recognize polite forms?
- Can it recognize punctuation?
- What problems exist, if any?

#### Speaker Recognition
- Does it recognize different speakers?
- One entry per speaker?
- Separation of background noise (throat clearing vs. device operation vs. external noise)?
- What problems exist, if any?

#### Speech Patterns
- Does it detect pauses > 3 seconds (long pauses)?
- Does it recognize hesitant speech (< 3 seconds)?

#### Interpreting Language
- Does it recognize sequences in interpreter language?
- What problems exist, if any?

#### Filler Words
- Recognizes all filler words
- Recognizes only some filler words
- Does not recognize any filler words

#### Transcription Accuracy
- Transcribes completely (including meta-comments, false starts, etc.)?
- No omissions?
- No additions?
- No 'free inventions'?
- Handling of code switching?
- Handling of expressions with multiple meanings? How is this indicated?
- Plural/singular correctly reproduced?
- Pronouns correctly reproduced?
- Personal names correctly reproduced?
- Geographical names correctly reproduced?
- Abbreviations correctly reproduced?

#### Post-Processing Effort
- No effort required
- Little effort required (< 10 minutes)
- High effort required (> 15 minutes)

### Secondary Features (Nice-to-Have)
- Confidence scoring - Flag uncertain transcriptions for human review
- Cultural context tagging - Highlight culturally-specific expressions

## Support for Hackers
SEM subject-matter experts available remotely (via phone, or video call) to clarify uncertainties, discuss transcription outputs, and provide evaluation feedback.
 
## Technical Requirements and Preferences
- The solution must handle stereo (non-channel separated speaker) voice data
- The solution should include time markers in  to facilitate comparison with the interview recordings

## Data

### Provided Materials:
- Synthetic audio recording of an asylum interview with interviewer, interviewee, and translator
- Transcription conventions for commenting, highlighting, and tagging transcription output

**Privacy & Ethics:** Under Swiss Data Protection Law, voice is classified as particularly sensitive personal data. The participating speakers have consented to use the recording for voice-to-text transcription experiments. Additionally, speaker voices have been anonymized using state-of-the-art voice anonymization technology from French startup Nijta.com.

All materials are available in the /data folder. By accessing or using the data provided, you agree to the following terms and conditions.

### Terms and Conditions
The data is provided solely for the purpose of participating in the hackathon event held in Zurich, Switzerland, and for developing solutions directly related to the specific challenge you have selected. You are strictly prohibited from using the Data for any other purpose, including but not limited to:
- Commercial use
- Research or development outside the scope of this hackathon challenge
- Personal use or any other unauthorized activities

The data is provided "as is" without any warranties, express or implied, including but not limited to, warranties of merchantability, fitness for a particular purpose, or non-infringement. The hackathon organizers do not guarantee the accuracy, completeness, or reliability of the data.

Immediately following the conclusion of the hackathon event, you are obligated to permanently and securely delete all copies of the data, including any derived or processed data, from all your devices, storage media, and systems. 

### Source of Data
The data of this respository has been provided by [the State Secretariat for Migration](https://www.sem.admin.ch/sem/en/home.html) submitting the challenge

## Why Hack?
Accurate asylum interview transcriptions are critical for the SEM to make fair, evidence-based decisions that uphold Switzerland's commitment to providing protection to those who truly need it while maintaining public trust in the asylum system. Enhanced transcription technology enables faster, more reliable case processing, reducing administrative burden and costs for Swiss taxpayers while ensuring consistent quality even during crisis periods when application volumes surge. Most importantly, precise documentation of refugee testimonies protects vulnerable individuals by ensuring their stories are captured faithfully, giving them the best chance for a fair assessment of their protection needs.

## About SEM
The State Secretariat for Migration (SEM) is responsible for all matters covered by legislation on foreign nationals and asylum seekers in Switzerland.

**Protection from Persecution:** Switzerland affords temporary or long-term protection to foreign nationals who face persecution in their native countries or who must escape the ravages of war. Asylum seekers undergo an asylum procedure to determine whether they qualify for refugee status.
*Watch this video to get an impression of an [asylum interview] (https://asylum-info.ch/en/asylum-procedure)
