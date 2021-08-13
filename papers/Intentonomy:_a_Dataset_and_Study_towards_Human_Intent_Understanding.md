[**Intentonomy: a Dataset and Study towards Human Intent Understanding**](https://github.com/Big-Brother-Pikachu/Paper-Contributions-Analysis#3-intentonomy-a-dataset-and-study-towards-human-intent-understanding)

# Contributions in my words

1. They built a new dataset called Intentonomy dataset which is aimed at human intent understanding. They carefully selected the intent labels using psychology knowledge and ingeniously designed the annotation process to ensure quality.
2. They used this dataset to analysis how visual content within images contributes to the understanding of human intent. Results showed that different intent categories have different preferences on objects and context, and further, specific objects/context classes. Also, there are some intent classes which visual information only is not enough to describe.
3. Based on the above discoveries, they proposed a novel method for intent recognition with two specific designs. It guided the network to focus on the region of objects and/or contexts according to intent categories. Also it used hashtags to complement visual information. Experiment results demonstrated the effectiveness of this method and verified the effect of each component.

# Contributions they claim

1. A novel dataset of 14,455 high-quality images, each labeled with one or more human perceived intent. This dataset, which we call Intentonomy, offers a total of 28 intent labels supported by a systematic social psychological taxonomy proposed by experts.
2. A systematic study to show how commonly used object and context information, as well as textual information, contribute to intent recognition.
3. We introduce a framework with the help of weakly-supervised localization and an auxiliary hashtag modality that is able to narrow the gap between human and machine understanding of images.

# Contributions in my words modified

1. They built a new dataset called Intentonomy **consisting of 14,455 high-quality images, each labeled with one or more human perceived intent** ~~, which is aimed at human intent understanding~~. They carefully selected **28** intent labels using psychology knowledge and ingeniously designed the annotation process to ensure quality.
2. They used this dataset to analysis how visual content within images contributes to the understanding of human intent. Results showed that different intent categories have different preferences on objects and context, and further, specific objects/context classes. Also, there are some intent classes which visual information only is not enough to describe.
3. Based on the above discoveries, they proposed a novel method for intent recognition with two specific designs. First, it guided the network to focus on the region of objects and/or contexts according to intent categories. Second, it used hashtags to complement visual information. Experiment results demonstrated the effectiveness of this method and verified the effect of each component.