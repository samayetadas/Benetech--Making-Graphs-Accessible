# Benetech--Making-Graphs-Accessible

# Dataset Description

The competition's dataset comprises about 65,000 comprehensively-annotated scientific figures of four kinds: bar graphs (both horizontal and vertical), dot plots, line graphs, and scatter plots. While the majority of the figures are synthetic, there were several thousand figures extracted from professionally-produced sources. The task was to predict the data series depicted in the test set figures.

For visualizing the data and the data description , please click the link:
https://www.kaggle.com/competitions/benetech-making-graphs-accessible/data

# Competition metrics
You may refer to this notebook for the python implementation of the metric for Benetech competition

Better solutions has already been posted in public for this competition as it is closed now.You may refer to:

* https://www.kaggle.com/competitions/benetech-making-graphs-accessible/discussion/418786
* https://www.kaggle.com/competitions/benetech-making-graphs-accessible/discussion/418430
* https://www.kaggle.com/competitions/benetech-making-graphs-accessible/discussion/418420
* https://www.kaggle.com/competitions/benetech-making-graphs-accessible/discussion/418466

# Models tried
* Donut- Donut , Document understanding transformer, is a new method of document understanding that utilizes an OCR-free end-to-end Transformer model. Donut does not require off-the-shelf OCR engines/APIs, yet it shows state-of-the-art performances on various visual document understanding tasks, such as visual document classification or information extraction (a.k.a. document parsing).The model takes the image as input and directly outputs the text. It is just an image encoder and text decoder.

  You can study more about donut from: https://github.com/clovaai/donut
  Code Requirements : GPU P100
  
* Deplot- Deplot is based on the same architecture as Pix2Struct. It is designed to convert visual plots or charts into text. The approach taken by DePlot involves breaking down the visual language reasoning challenge into two stages: plot-to-text translation and reasoning over the resulting text. This is achieved through a modality conversion module (named as DePlot), which translates images into linearized tables. The resulting text can then be used to prompt a large language model (LLM), which can reason over the graph data using its few-shot reasoning capabilities.

  Code Requirements : GPU P100  


