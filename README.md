
# Multilingual Text-to-Speech Synthesis Using FastSpeech2

## Languages
- English
- Telugu

## Model details
- Architecture: FastSpeech2
- Training checkpoint: 20000
- Sample rate: 22050 Hz
- Environment: Kaggle GPU

## Submission contents
- Source code and configuration files for both languages
- English and Telugu synthesized test audio
- Original inference plots
- Duration, pitch and energy analysis
- Test sentence JSON and CSV files
- Training and validation loss curves
- Validation evaluation results
- Bilingual comparison graphs
- Final evaluation report

## Model checkpoints
The two trained model checkpoints are supplied separately in:
FastSpeech2_Trained_Models.zip

## Evaluation note
Duration, pitch and RMS energy plots are measurements from
the generated audio. They are not direct visualizations of
the internal FastSpeech2 variance predictor tensors.

The evaluation uses a limited set of test and validation
samples. Audio quality and intelligibility should be
assessed through listening and, where possible, ASR metrics.
