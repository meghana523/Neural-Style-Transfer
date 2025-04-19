# Neural-Style-Transfer

*COMPANY*:  CODTECH IT SOLUTIONS

*NAME*:  PERUBOINA LAKSHMI MEGHANA

*INTERN ID*:  CT12WOI

*DOMAIN*:  ARTIFICIAL INTELLIGENCE

*DURATION*:  8 WEEKS

*MENTOR*:  NEELA SANTOSH

*Over View*:
*Neural Style Transfer (NST) is a deep learning technique that combines the content of one image with the artistic style of another to generate a new, stylized image. Introduced by Gatys et al. in 2015, this technique uses convolutional neural networks (CNNs) to achieve artistic transformation, making it possible to render a photograph in the style of famous painters like Van Gogh or Picasso.*

*The core idea of NST is to use a pre-trained CNN, typically the VGG-19 network, to extract feature representations from images. NST works by minimizing a loss function that consists of two parts: content loss and style loss. The content loss ensures that the generated image retains the structure and layout of the content image, while the style loss ensures that the generated image reflects the texture and color patterns of the style image.*

*The process starts with an initial image (often random noise or a copy of the content image). This image is gradually updated using gradient descent to minimize the total loss. The CNN is not retrained; instead, it is used as a feature extractor. The content representation is typically taken from deeper layers of the network, where the image's semantic structure is captured. Style representation is extracted from multiple layers using Gram matrices, which capture the correlations between different filter responses.*

*NST is computationally intensive because it involves optimizing the image pixels directly through multiple iterations. To address this, researchers later developed fast style transfer techniques using feed-forward networks trained specifically to apply a particular style in real-time.*

*In summary, Neural Style Transfer is a creative application of CNNs that blends the visual features of two images, producing artwork-like results. It has influenced fields such as digital art, augmented reality, and photo editing, showing the power of neural networks beyond traditional classification tasks.*

*Output*:
![Image](https://github.com/user-attachments/assets/228735ac-a785-42d4-b11f-5a8706a8f3e5)
