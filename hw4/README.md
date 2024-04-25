# [hw3_extend.ipynb](./hw3_extend.ipynb)

almost same as [hw3.ipynb](../hw3/hw3.ipynb), but it

- grab competition description for hw4
- stores competitions, tags, tag_comps in a google sheet

# [hw4.ipynb](./hw4.ipynb)

in hw4, we do

- summarize the competition description by using [mt5-base-summary](https://huggingface.co/twwch/mt5-base-summary) in Hugging Face
- extract keywords in summarized descrption by [jieba-tw](https://github.com/APCLab/jieba-tw/tree/master) as a way to generate more tags for competitions
- use [networkx](https://networkx.org/documentation/stable/reference/generated/networkx.drawing.layout.spring_layout.html#spring-layout) to draw the networkgraph with
  - competition title(blue)
  - keywords(green)
  - tags(from hw3)(red)

so the competition can be visually linked with each other by keywords and tags
[google colab](https://colab.research.google.com/github/yatta03/112-2PL/blob/main/hw4/hw4.ipynb)

<!-- the final [graph](https://drive.google.com/file/d/1hD7xN1cXBnYeAWWH-VkzukZcmxOyqx8z/view?usp=sharing) -->

the final graph:
[link](https://drive.google.com/file/d/1hD7xN1cXBnYeAWWH-VkzukZcmxOyqx8z/view?usp=sharing)
