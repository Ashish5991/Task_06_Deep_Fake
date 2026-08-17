# Detection and Provenance Check

> Synthetic media disclosure: The artifacts checked here are AI-generated synthetic media created for research and educational purposes.

## Detection / Provenance Method

Tool or method used: Local provenance/metadata inspection of generated WAV files

Date tested: 2026-07-08

Artifact tested: `artifacts/attempt1_windows_tts_david_ai_generated.wav` and `artifacts/attempt2_windows_tts_zira_ai_generated.wav`

Detector URL or provenance method: Inspected the generated WAV files for embedded metadata/provenance indicators and C2PA-style content credentials. The local check searched the file contents for `c2pa`, `C2PA`, `ContentCredentials`, and `ai_generated`. The artifacts were generated locally with Windows System.Speech rather than through a platform that automatically attaches provenance credentials.

## Result

Did the tool identify the artifact as synthetic? No embedded provenance marker or content credential was found through local inspection.

Confidence score, if provided: Not applicable. This was a provenance/metadata check, not a statistical detector.

Explanation provided by detector, if any: Not applicable.

Screenshot filename, if saved: None.

## Interpretation

Was the result accurate? Yes. The files are synthetic, but the WAV files themselves do not appear to carry a durable embedded disclosure or provenance signal.

Did the detector explain its reasoning? Not applicable because this was a local provenance inspection rather than a detector with an explanatory model.

Would this result help a viewer understand whether the artifact was synthetic? No. A listener would need the filename, README disclosure, spoken disclosure, or repository documentation to know the artifact is synthetic. This shows why external labeling remains important when provenance metadata is absent.

## Optional Re-Test

If you re-encoded, screen-recorded, compressed, or uploaded the artifact elsewhere, record whether the detection/provenance result changed.

No re-encoding or upload test was performed. If the files are converted to another format later, the repository disclosure and filename labeling should be preserved because embedded provenance is not present.
