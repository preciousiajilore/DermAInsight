# DermAInsight

<img src="./UI:UX/Logo_v3_draw_final_logo_circle (1).png" alt="Logo" width="200"/>


<h2>Dataset</h2>

DermAInsight leverages the SCIN Dataset from Google Research.
The SCIN dataset, developed in collaboration with physicians at [(https://med.stanford.edu/)](https://med.stanford.edu/), includes over 10,000 images of skin, nail, and hair conditions. Designed to reflect the diverse range of concerns people search for online, it supplements typical clinical datasets. All contributions were made voluntarily through a Crowdsourcing Method, with informed consent, under an institutional review board-approved study in the US.


<h2>Figma Demo</h2>

Check out our Figma demo to see what the app should look like: [Figma Demo](https://www.figma.com/proto/qS49QQcyvwg2B2IteOcyb9/dermAInsight-Prototype?node-id=198-605&t=H7uY7SvuJVobRigo-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=198%3A605)

<h2>Our Model</h2>
<h3>Architecture</h3>
ResNet-50 model with deep conditional neural network using Tensorflow and Keras Libraries. Pre-trained on a dataset of large-skin lesion images. Using Adam optimizer, Categorical Cross Entropy233 Loss, Learning rate = 1e-4

<h3>Fine-Tuning</h3>
Fine-tuning some of the top layers of the ResNet-50 model allows the network to adapt pre-trained features more specifically to our dataset. Utilizes the ImageDataGenerator for data augmentation and loading. Trained on 10 epochs with batch size 32.



