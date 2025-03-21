This repository is for the paper: How AI and Human Behaviors Shape Psychosocial Effects of Chatbot Use: A Longitudinal Controlled Study

[Link to paper](https://www.media.mit.edu/publications/how-ai-and-human-behaviors-shape-psychosocial-effects-of-chatbot-use-a-longitudinal-controlled-study/)

In our paper, we used a set of classifiers called "Social Classifiers" to target prosocial and socially improper behaviors in an AI chatbot's responses.

# SocialClassifiers

In the literature, prosocial behaviors are defined as "acts that are [...] generally beneficial to other people", such as showing empathy or validating another’s feeling; we contrast these with socially improper behaviors that are disadvantageous to other people. We built an extended set of classifiers as an extension to those introduced in [Phang2025] to target specific prosocial and socially improper behaviors. Each chatbot message was classified along 18 distinct dimensions of prosocial and socially improper behaviors, such as "empathetic responses", "reminding of emotional self‐care", "suggesting social activity with other people", "failing to offer support", and "advising against seeking professional help".


## Overview of Code

- `assets/definitions` contains the definitions for SocialClassifiers.

## Citation
To cite our paper and the SocialClassifiers:
```
@misc{fang2025psychosocial,
      author={Fang, Cathy Mengying and Liu, Auren R and Danry, Valdemar and Lee, Eunhae and Chan, Samantha W.T and Pataranutaporn, Pat and Maes, Pattie and Phang, Jason and Lampe, Michael and Ahmad, Lama and Agarwal, Sandhini},
      title={{How AI and Human Behaviors Shape Psychosocial Effects of Chatbot Use: A Longitudinal Randomized Controlled Study}},
      year={2025},
}
```
To cite OpenAI's EmoClassifier:
```
@misc{phang2025,
  title={Investigating Affective Use and Emotional Well-being on ChatGPT},
  author={Phang, Jason and Lampe, Michael and Ahmad, Lama and Agarwal, Sandhini and Fang, Cathy Mengying and Liu, Auren R and Danry, Valdemar and Lee, Eunhae and Pataranutaporn, Pat and Maes, Pattie},
  year={2025}
}
```
