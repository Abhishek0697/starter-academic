---
title: "Research Ideas for the Hateful Memes Challenge"

event: "Hateful Memes Challenge session @ NeurIPS - Contributed Talks"
event_url: https://ai.facebook.com/blog/hateful-memes-challenge-and-data-set/

location: Virtual
# address:
  #street: 450 Serra Mall
  #city: Stanford
  #region: CA
  #postcode: '94305'
  #country: United States

summary: "We present Object Detection based Image Captioning, and Sentiment Analysis as our two research ideas to enhance performance against the adversarial examples introduced the challenge dataset."
abstract: "We propose two research ideas which when integrated into a Multimodal model, aims to learn the context behind the combination of text and captions used. Our first idea is to use Image Captioning as a medium for introducing outside world knowledge to our model. The highly confident error cases of the multimodal baselines show that the models tend to focus more on the text modality for predictions. Our focus in using this approach is to find a deeper relationship between the text and the image modalities by bringing the visual modality and finding its “actual caption” and parallelly sending the image representation along with the pre-extracted caption representation for the concatenation step. Moreover, comparing the “actual caption” with the “pre-extracted caption” of the meme will help in understanding whether both are aligned or not because in many cases a hateful image is turned benign just by declaring what is happening in the image. Our second approach is to use sentiment analysis on both Image and Text modalities. Instead of only using multimodal representations obtained from pre-trained neural networks, we also include the unimodal sentiment to enrich the features. The intuition for this idea is that current pre-trained representations, like VisualBERT and ViLBERT, have the objective of predicting the semantic correlation between image and text, but semantic information is difficult to capture and may not be enough for solving our task. We try to include high-level features like text and image sentiments because sentiment analysis is a related but relatively simple task." 

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-12-11T18:00:00Z"
#date_end: "2020-12-11T19:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: ["Abhishek Das", "Japsimar Singh Wahi"]
tags: ["Deep Learning"]

# Is this a featured talk? (true/false)
featured: false

image:
  placement: 1
  caption: "Challenge"
  focal_point: "Smart"

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- Detecting Hate Speech in Multi-modal Memes

---



<p><iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQPj6tRkmuUFDkVpe62UL1TPf9belHfbZwkItkbiOsKcX3YqOCnnvnvUryPjwbksbqvdfd8088YyZS9/embed?start=false&loop=true&delayms=6000" frameborder="0" width="720" height="405" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe></p>


