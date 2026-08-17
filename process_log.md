# Process Log

> Synthetic media disclosure: This log documents AI-generated synthetic media creation for research and educational purposes.

## Attempt 1

Date: 2026-07-08

Tool: Windows System.Speech Text-to-Speech through PowerShell

Version / access tier: Built-in Windows local speech synthesis; free local access

Media type: WAV audio

Free-tier limits: No paid tier used. Limited to installed Windows desktop voices and local TTS quality.

Input script: `source_script.md`, Working Script section, with an added spoken disclosure at the beginning: "This is synthetic audio generated for a research assignment."

Prompt or settings: Voice `Microsoft David Desktop`; rate `1`; volume `100`; output format WAV.

Output filename: `artifacts/attempt1_windows_tts_david_ai_generated.wav`

Approximate duration: 97.3 seconds

Time spent: About 15 minutes, including checking available voices, generating the first file, measuring duration, and regenerating to keep the artifact under two minutes.

What worked: The tool generated a clear, intelligible spoken version of the full script. The output was fast to create, required no account, and did not require paid credits.

What failed: The first version was about 122 seconds, slightly over the target length, so it had to be regenerated with a faster rate. The final voice still sounded synthetic because of flat emotion, mechanical pacing, and limited emphasis.

Changes to try next: Compare against another installed voice and a slightly different rate to see whether the synthetic cues become less noticeable.

Screenshots or notes: No screenshots captured for this local command-line generation step.

## Attempt 2

Date: 2026-07-08

Tool: Windows System.Speech Text-to-Speech through PowerShell

Version / access tier: Built-in Windows local speech synthesis; free local access

Media type: WAV audio

Free-tier limits: No paid tier used. Limited to installed Windows desktop voices and local TTS quality.

Input script: Same script as Attempt 1.

Prompt or settings: Voice `Microsoft Zira Desktop`; rate `1`; volume `100`; output format WAV.

Output filename: `artifacts/attempt2_windows_tts_zira_ai_generated.wav`

Approximate duration: 96.0 seconds

Time spent: About 10 minutes after Attempt 1, including generation and duration check.

What worked: The second voice produced clear narration with a slightly different tone and cadence. It was useful for comparing how voice selection changes perceived quality while keeping the script and generation pipeline constant.

What failed: The output still sounded synthetic. The pacing was more consistent than human speech, emotional emphasis was limited, and some phrasing sounded read aloud rather than spoken naturally.

Changes from Attempt 1: Changed the voice from `Microsoft David Desktop` to `Microsoft Zira Desktop` while keeping the same script, volume, and rate.

Screenshots or notes: No screenshots captured for this local command-line generation step.

## Additional Iterations

Use this section for any extra attempts, revised prompts, new voices, new avatars, or different export settings.
