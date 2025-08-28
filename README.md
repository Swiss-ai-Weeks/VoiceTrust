# How to teach an AI to help assist with integrity to life-changing conversations?

## The Challenge
The Swiss Federal Office for Migration (SEM) on a daily basis conducts interviews with asylum applicants in order to determine their refugee status. What’s being discussed in these interviews contains sensitive personal information – effecting in content classification as confidential. The legal issues involved are complex and in order to determine an individual's refugee status, the SEM case-workers must take into account not only the relevant internal policy guidelines, but also nuanced cultural contexts, general aspects of human communication, and credibility assessments in particular. Basis for such an assessment is an accurate transcription of everything that is being said, as well as how it is being said. By contrast, today's widely available and popular speech to text transcription tools "smoothen" the transcribed content for easier consumption, thereby sacrifising the individual speech pattern and diction.

## The Objective
In order to be useful for SEM, the interview transcription output must reliably reflect the recording as accurately as possible: The tool has to transcribe exactly what is being said, including mistakes such as mispronunciations, false starts, auto-corrections, grammatical errors and hesitation markers. Fillers, halting speech patterns and pauses must be visualized.

The solution handles Switzerland's official languages (German, French, and Italian), optionally also foreign languages (e.g.: Farsi, Turkish, various Arabic dialects); it correctly transcribes names of (personal, organisational and geographical), and abbreviations; highlights expressions with several different meanings; knows punctuation rules; it distinguishes between different speakers, recognizes human voices from background noise, and decreases the time required for post-editing as compared to the existing manual process. Detailled evaluation criteria and benchmarks will be provided to the hack team.

## Support for Hackers
- Data: Synthetic interview recordings in multiple (official and foreign) languages, detailed evaluation criteria based on quality and efficiency.
-	People: SEM subject-matter experts available remotely (via phone, or video call) to clarify uncertainties, to discuss and evaluate transcription outputs.
 
## Technical Preferences
- Solution must be able to handle stereo (non-channel separated speaker) voice data. The resulting transcripts should contain time markers to facilitate comparison with the interview recordings.

## Why Hack?
Accurate asylum interview transcriptions are critical for the SEM to make fair, evidence-based decisions that uphold Switzerland's commitment to providing protection to those who truly need it while maintaining public trust in the asylum system. Enhanced transcription technology enables faster, more reliable case processing, reducing administrative burden and costs for Swiss taxpayers while ensuring consistent quality even during crisis periods when application volumes surge. Most importantly, precise documentation of refugee testimonies protects vulnerable individuals by ensuring their stories are captured faithfully, giving them the best chance for a fair assessment of their protection needs.


# Data for the Challenge "VoiceTrust"
This respository is part of the Zurich hackathon of [Swiss {ai} Week](https://swiss-ai-weeks.ch/) happening on 26/27 September 2025.

By accessing or using the data provided, you agree to the following terms and conditions.

## Terms and Conditions
> The data is provided solely for the purpose of participating in the hackathon event held in Zurich, Switzerland, and for developing solutions directly related to the specific challenge you have selected. You are strictly prohibited from using the Data for any other purpose, including but not limited to:
> - Commercial use.
> - Research or development outside the scope of this hackathon challenge.
> - Personal use or any other unauthorized activities.
> 
> The data is provided "as is" without any warranties, express or implied, including but not limited to, warranties of merchantability, fitness for a particular purpose, or non-infringement. The hackathon organizers do not guarantee the accuracy, completeness, or reliability of the data.
>
> Immediately following the conclusion of the hackathon event, you are obligated to permanently and securely delete all copies of the data, including any derived or processed data, from all your devices, storage media, and systems. 

## Source of Data
The data of this respository has been provided by [the State Secretariat for Migration](https://www.sem.admin.ch/sem/en/home.html) submitting the challenge


