---
layout: default
---

![block_diagram](assets/images/block_diagram.PNG)

<h2 style="text-align: center;">Abstract</h2>
<p style="text-align: justify">Understanding the neural transformation of visual perception is a fundamental challenge in neuroscience, and one that has the potential to revolutionize AI model design. In this study, we present a novel embedding manifold to map the neural representations for natural image stimuli in the mouse visual cortex to the text embeddings, using state-of-the-art multimodal language models. Specifically, we processed anatomical and functional neural responses from various sub-regions of the mouse visual cortex and presented the same natural image stimuli to a range of image-to-text models and learned a mapping from the corresponding text embeddings to neural representations. Our results show a strong relationship between text and neural embeddings in the latent space, resulting in a text representation of neural language. To further test the decoding capacity of our neural language, we feed the encoded text-to-neural representations to a variety of state-of-the-art text-to-image models, such as Stable Diffusion, and observe a powerful regeneration of visual representations, capturing the key visual features presented as input stimuli to the mouse visual cortex. The performance of the reconstruction from the text-to-image models is proportional to the neural language encoding capacity of image-to-text models and shows a similar map of neural activations in the mouse visual cortex. This study is the first of its kind to introduce a language of mouse visual cortex neurons encoded through generative AI models, and has significant implications for both AI and neuroscience. By mapping neural representations for a given image to a text embedding space, we gain insights into the underlying structure of visual information processing in mouse as well as its functional similarity with the multimodal language models. We believe this approach has several potential applications in understanding the information processing in the mouse brain and building the next generation of AI models.</p>

<h2 style="text-align: center;">Video</h2>
<p style="text-align: justify">[DEMO video goes here]</p>

<h2 style="text-align: center;">Method and Results</h2>


![grand_figure](assets/images/grand_figure.PNG)
<h3 style="text-align: center">Overview of the Microns Dataset</h3>
<p style="text-align: justify">[Description goes here]</p>


![clusters](assets/images/clusters.PNG)
<h3 style="text-align: center">UMAP clusters representing performance of ImageToText models</h3>
<p style="text-align: justify">[Description goes here]</p>


![text2neural](assets/images/text2neural.PNG)
<h3 style="text-align: center">Performance of ImageToText models at encoding neural responses</h3>
<p style="text-align: justify">[Description goes here]</p>


![text2neural2](assets/images/text2neural2.PNG)
<h3 style="text-align: center">Distribution of word tokens for randomly sampled neurons</h3>
<p style="text-align: justify">[Description goes here]</p>

<!-- <script type="text/javascript" src="https://viewer.diagrams.net/js/viewer-static.min.js"></script> -->