# Task 06 Deep Fake

> Synthetic media disclosure: All media artifacts in this repository are AI-generated or AI-assisted synthetic media created for research and educational purposes. They do not depict or imitate any real identifiable person without consent.

## Project Description

This project documents the construction and evaluation of a short synthetic media artifact based on a written analytical narrative. The goal is not to produce a perfect deepfake, but to compare free or student-accessible AI media tools, document the process carefully, and evaluate where synthetic media succeeds or fails.

## Source Script

The source script is saved in `source_script.md`.

If a Task 5 narrative is available, this script should be adapted from that narrative. If not, the included script can be used as a starting point and revised to reflect real analysis.

## Tools Used

| Attempt | Tool | Media Type | Version / Access Tier | Output File |
| --- | --- | --- | --- | --- |
| 1 | Windows System.Speech Text-to-Speech | Audio | Built-in Windows local TTS / free local access | `artifacts/attempt1_windows_tts_david_ai_generated.wav` |
| 2 | Windows System.Speech Text-to-Speech | Audio | Built-in Windows local TTS / free local access | `artifacts/attempt2_windows_tts_zira_ai_generated.wav` |

## Reproduction Steps

1. Open `source_script.md` and copy the final script.
2. Generate Attempt 1 using a free or student-accessible synthetic voice or video tool.
3. Save the output in `artifacts/` with `ai_generated` in the filename.
4. Record the tool, settings, prompts, and result in `process_log.md`.
5. Generate Attempt 2 using a different tool, pipeline, voice, avatar, or settings.
6. Save the second output in `artifacts/` with `ai_generated` in the filename.
7. Evaluate each artifact in `evaluation.md`.
8. Run at least one detection or provenance check and record the result in `detection_provenance.md`.

## Artifact Labeling

All generated files must be clearly labeled as synthetic in the filename. Example filenames:

- `artifacts/attempt1_elevenlabs_audio_ai_generated.mp3`
- `artifacts/attempt2_heygen_video_ai_generated.mp4`

Where the medium supports it, the artifact should also include a spoken or on-screen disclosure that it is synthetic.

## Summary of What I Learned

The strongest lesson from this experiment is that even simple free text-to-speech tools can quickly produce understandable synthetic narration, but the seams are still audible. Both attempts communicated the script clearly, but neither sounded like a natural interview or broadcast recording. The voices had limited emotional range, unnatural pacing around some sentence boundaries, and a polished-but-flat tone that made the synthetic origin noticeable.

Attempt 1 used the Microsoft David Desktop voice. It sounded steady and intelligible, but the cadence was mechanical and the emphasis did not always match the meaning of the sentence. Attempt 2 used the Microsoft Zira Desktop voice. It was slightly smoother in places, but still had the same limited prosody and artificial rhythm. The comparison showed that changing voice and rate settings affects surface quality, but does not remove the deeper synthetic-media cues.

The local provenance check found no C2PA content credentials or embedded disclosure metadata in the WAV files. That means filename labeling and repository documentation are necessary for transparency. This reinforced one of the assignment's core points: synthetic artifacts need clear external labeling because the media file itself may not carry reliable provenance information.

## Repository Contents

- `source_script.md`: script used to generate the synthetic media
- `process_log.md`: detailed log of tools, prompts, settings, failures, and time spent
- `evaluation.md`: critical evaluation of each artifact
- `detection_provenance.md`: detection or provenance test results
- `artifacts/`: AI-generated synthetic media outputs
- `screenshots/`: screenshots of settings, failures, or detection results

## Ethics Note

This project does not attempt to impersonate any real identifiable person. The work is limited to synthetic or consent-based media creation for research purposes. All artifacts are labeled as AI-generated.
