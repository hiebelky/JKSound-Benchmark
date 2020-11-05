This dataset is a subset (98 cases) from the complete Universal-150-Benchmark (https://github.com/adobe/Deep-Audio-Prior).
**Comparision_results** contains the results from the original dataset and the ground truth audio, "gt1.wav" and "gt2.wav".
**Our_results** contains our extraction results, named "picked.wav" and "remain.wav".
The **Config.json** file shows the annotation regions used for extraction. Each line indicates a start and end sample count (at 44.1kHz) for a region.
And the "Target-Ground-Truth" is compared to "picked.wav".
And the "Remain-Ground-Truth" is compared to "remain.wav".

Please note the difference in sample rate:
1) The dap, gt, kam, mix, nmf, and rpca results in the **Comparision_results** folder are 11kHz.
2) The gt, mix and our results in **Our_results** folder are 44.1kHz.

