# KOMPASSI-Renderer-Plugin
VST/LV2/VST3 plugins of the KOMPASSI-Renderer

This is a demo implementation of our new parametric spatial audio renderer for headphone or loudspeaker rendering of multichannel recordings. It retains the flexibility of our earlier method called COMPASS [1 - 6] while improving significantly in terms of robustness and audio quality. It uses a new and more advanced parametric model of the sound scene, and an improved rendering solution. The demo plugin is limited at the moment to Ambisonic input and head-tracked binaural delivery, but we intend to gradually update the plugin with additional functionality, such as loudspeaker rendering for flexible setups, and support for custom microphone arrays.

We call the improved method nCOMPASS - a detailed technical report on it will be published soon!

For questions, comments, or feedback on its use, please contact us at:
archontis.politis_at_tuni.fi

References:

[1] Politis, A., Tervo, S., & Pulkki, V. (2018). COMPASS: Coding and multidirectional parameterization of ambisonic sound scenes. In 2018 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (pp. 6802-6806).

[2] Politis, A., Tervo, S., Lokki, T., & Pulkki, V. (2018). Parametric multidirectional decomposition of microphone recordings for broadband high-order ambisonic encoding. In Audio Engineering Society Convention 144.

[3] McCormack, L., Politis, A., & Pulkki, V. (2021). Parametric spatial audio effects based on the multi-directional decomposition of ambisonic sound scenes. In 2021 24th International Conference on Digital Audio Effects (DAFx) (pp. 214-221).

[4] McCormack, L., Politis, A., Gonzalez, R., Lokki, T., & Pulkki, V. (2022). Parametric ambisonic encoding of arbitrary microphone arrays. IEEE/ACM Transactions on Audio, Speech, and Language Processing, 30, 2062-2075.

[5] McCormack, L., & Politis, A. (2022). Estimating and reproducing ambience in ambisonic recordings. In 2022 30th European Signal Processing Conference (EUSIPCO) (pp. 314-318).

[6] McCormack, L., Hold, C., & Politis, A. (2023). Parametric architecture for the transmission and binaural reproduction of microphone array recordings. In Audio Engineering Society Conference: AES 2023 International Conference on Spatial and Immersive Audio.
