<h1>The Sports-1M Dataset</h1>

![http://cs.stanford.edu/people/karpathy/deepvideo/sz70sx.jpg](http://cs.stanford.edu/people/karpathy/deepvideo/sz70sx.jpg)

Academic dataset that accompanies the paper "[Large-scale Video Classiﬁcation with Convolutional Neural Networks.](http://cs.stanford.edu/people/karpathy/deepvideo/)" (Andrej Karpathy, George Toderici, Sanketh Shetty, Thomas Leung, Rahul Sukthankar, Li Fei-Fei).

This dataset contains 1,133,158 video URLs which have been annotated automatically with [487 labels](https://code.google.com/p/sports-1m-dataset/source/browse/labels.txt). The annotation was done via the [YouTube Topics API](https://developers.google.com/youtube/v3/guides/searching_by_topic). If you wish to use the YouTube API yourself, we have provided the topic ID for each of the classes [here](https://code.google.com/p/sports-1m-dataset/source/browse/sports_mids.txt). Example thumbnails for each class can be found [here](http://cs.stanford.edu/people/karpathy/deepvideo/classes.html).


## Getting the Data ##

If you'd like to download the necessary files for this benchmark, run the following command:
```
git clone https://code.google.com/p/sports-1m-dataset/
```

Once you have downloaded the data, please read the [README](https://code.google.com/p/sports-1m-dataset/source/browse/README) file in order to see how to use this data.

## Text File Format ##
The [487 labels](https://code.google.com/p/sports-1m-dataset/source/browse/labels.txt) file is encoded in UTF-8. Therefore, in order to be able to read all the label names correctly you need to make sure that you are using an UTF-8 compatible text editor.

## Notes ##
There is a [discussion group](https://groups.google.com/forum/#!forum/sports-1m-dataset) about this dataset. Please post specific questions there, and group members may be able to help.