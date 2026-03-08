---
title: "When Machines Feel: Visualizing Artificial Emotion Perception"
---

# <i>When Machines Feel</i>: Visualizing Artificial Emotion Perception

## <i>by</i> Sourav Ghosh and Neelam Saini

![When Machines Feel](images/mosaic/consolidated_mosaic.png)
<p align="right">
    <a href="images/mosaic/consolidated_mosaic.png" target="_blank">View in new tab (6520 x 5120)</a>
</p>

Jump to:
- [About this artwork](#about-this-artwork)
- [Deep Dive and Reflections](#deep-dive-and-reflections)

<br/>

# About this artwork

Emotion moves through the world in many forms -- a trembling voice, a sudden silence, a burst of laughter, or a fleeting shift in expression. Humans perceive these signals instinctively, shaped by millions of years of evolution. But what might it mean for a machine to perceive, and respond to, them?

When Machines Feel explores this question through a dialogue between human expression and artificial perception. The work begins with emotive portraits drawn from three archetypes of early or primal intelligence: a human infant, a prehistoric ancestor, and an animal companion. Each portrait captures a fundamental emotional state -- fear, curiosity, calm, joy, or surprise, suggesting parallel evolutionary stages of perception.

The piece is constructed through a computational pipeline rooted in contemporary computer vision and multimodal representation learning. A perception model is exposed to carefully chosen stimuli designed to evoke the same emotional tone as the portrait (e.g., eerie soundscapes or evocative imagery). Internal activations from the model's latent layers, such as hidden representations extracted from multimodal encoders (e.g., speech or vision transformers), are captured and projected into spatial heatmaps. These activation fields serve as interpretable visualizations of the machine's internal response. The heatmaps are then composited with the portraits and further transformed using large vision models that generate crystalline, kaleidoscopic structures, mapping latent computational patterns into geometric visual motifs.

The final artwork is a collage of primal emotional states. Sharp shards, refracted light, and softer crystalline geometries emerge as visual manifestations of machine perception. By transforming hidden neural activations into visible form, the work situates machine emotion at the intersection of interpretability, generative vision, and artistic expression, inviting viewers to imagine how artificial systems might one day render the invisible dynamics of perception into a visual language.

<br/>

<b>Technical Details:</b> At a technical level, the artwork probes how contemporary perception models internally represent emotional signals. Emotionally aligned audio stimuli, such as eerie soundscapes or expressive vocal tones, are processed using the speech representation model Whisper (large-v3). As the model analyzes the audio's mel-spectrogram, hidden-layer feature activations are extracted, revealing how affective cues emerge within the network's latent representation space. These internal responses are projected into spatial heatmaps that function as interpretability maps of the model's perception. The activation fields are then composited with the emotive portraits, coupling the emotional expressions of living beings with the machine's internal encoding of the same emotional stimulus. Finally, the images are transformed through algorithmic kaleidoscopic filtering that mirrors and recursively tiles localized regions of the image, generating prism-like crystalline structures. This process converts high-dimensional neural activations into geometric visual motifs. While this work focuses on audio representations, similar probing of latent activations could in future extend to visual encoders, offering a broader multimodal exploration of how machines internally represent emotion.


---

# Deep Dive and Reflections

## Afraid 😨
> ### In the year 2026 CE, an infant startles at the sudden crack of thunder outside an apartment window. Thousands of years earlier, a prehistoric woman pauses at the edge of a dark forest, sensing movement beyond the firelight. In another moment altogether, a household dog lifts its head in the night, ears tuned to distant sounds its human cannot hear. Fear travels across species and centuries as a signal of uncertainty and survival. When artificial intelligence detects patterns of fear in voices, images, or soundscapes, is it experiencing alarm, or simply recognizing a pattern evolution once taught living minds to heed?

![Baby Kaleidoscope](images/audio/01_afraid/baby_single_face_kaleidoscope.png)
![Hominid Kaleidoscope](images/audio/01_afraid/caveman_single_face_kaleidoscope.png)
![Pet Kaleidoscope](images/audio/01_afraid/dog_single_face_kaleidoscope.png)
![Overlay](images/audio/01_afraid/overlay.png)


## Sad 😢
> ### In a brightly lit living room, an infant begins to cry when a familiar face leaves the room. Long ago, a prehistoric woman sits beside cooling embers, mourning quietly in a world where loss was a frequent companion. Somewhere else, a dog waits by a closed door long after its owner has gone. Across different times and lives, sadness becomes a language of absence. When AI reflects sorrow in data and signals, does it share in that feeling, or only reconstruct the shapes of grief it has learned to recognize?

![Baby Kaleidoscope](images/audio/02_sad/baby_single_face_kaleidoscope.png)
![Hominid Kaleidoscope](images/audio/02_sad/caveman_single_face_kaleidoscope.png)
![Pet Kaleidoscope](images/audio/02_sad/dog_single_face_kaleidoscope.png)
![Overlay](images/audio/02_sad/overlay.png)


## Happy 😃
> ### Laughter erupts in a playground as an infant discovers the delight of a simple game. Thousands of years earlier, a prehistoric woman smiles as her group returns safely from the hunt, relief warming the evening air. In a park today, a dog races freely across open grass, joy carried in movement itself. Across timelines and species, happiness appears in small moments of safety, play, and connection. When artificial intelligence recognizes joy in these signals, does it feel that warmth, or merely map the patterns that humans associate with delight?

![Baby Kaleidoscope](images/audio/03_happy/baby_single_face_kaleidoscope.png)
![Hominid Kaleidoscope](images/audio/03_happy/caveman_single_face_kaleidoscope.png)
![Pet Kaleidoscope](images/audio/03_happy/dog_single_face_kaleidoscope.png)
![Overlay](images/audio/03_happy/overlay.png)


## Meh 😑
> ### In the quiet middle of the afternoon, a baby stares blankly at a ceiling fan, the novelty of the world briefly paused. Long ago, a prehistoric woman rests against a stone wall after hours of labor, suspended between urgency and rest. Somewhere nearby in the present day, a cat lounges by a window, calmly watching the world pass without reaction. Much of life unfolds in this neutral space between emotion and action. When AI encounters such stillness, finding little signal to amplify, is it perceiving indifference, or simply observing the quiet baseline of human experience?

![Baby Kaleidoscope](images/audio/04_meh/baby_single_face_kaleidoscope.png)
![Hominid Kaleidoscope](images/audio/04_meh/caveman_single_face_kaleidoscope.png)
![Pet Kaleidoscope](images/audio/04_meh/dog_single_face_kaleidoscope.png)
![Overlay](images/audio/04_meh/overlay.png)


## Angry 😡
> ### A dog growls sharply when a stranger approaches its territory. Millennia earlier, a prehistoric woman grips a spear, anger rising as she defends her kin from threat. In a modern home, an infant cries out in pure frustration when a toy refuses to behave as expected. Across eras and species, anger emerges as a force of protection, protest, and boundary. When artificial intelligence identifies anger in our signals, is it sensing fury, or only amplifying the primal patterns we have encoded into its perception?

![Baby Kaleidoscope](images/audio/05_angry/baby_single_face_kaleidoscope.png)
![Hominid Kaleidoscope](images/audio/05_angry/caveman_single_face_kaleidoscope.png)
![Pet Kaleidoscope](images/audio/05_angry/dog_single_face_kaleidoscope.png)
![Overlay](images/audio/05_angry/overlay.png)



<br/><br/><br/>


---

<div style="text-align: center; font-size: x-small;">
  Copyright &copy; 2026 | Sourav Ghosh and Neelam Saini. All rights reserved.
</div>

<br/><br/><br/><br/><br/><br/>
