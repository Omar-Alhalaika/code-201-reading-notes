# Assorted Topics

# Video and Audio APIs

* HTML5 comes with elements for embedding rich media in documents — `<video>` and `<audio>` — which in turn come with their own APIs for controlling playback, seeking, etc. This article shows you how to do common tasks such as creating custom playback controls.
* > ` <source src="rabbit320.mp4" type="video/mp4">`
     `<source src="rabbit320.webm" type="video/webm">`


## The HTMLMediaElement API

* Part of the HTML5 spec, the HTMLMediaElement API provides features to allow you to control video and audio players programmatically — for example HTMLMediaElement.play(), HTMLMediaElement.pause(), etc. This interface is available to both `<audio>` and `<video>` elements, as the features you'll want to implement are nearly identical. Let's go through an example, adding features as we go.


| Attribute       | Value    | Description     |
| :------------- | :----------: | -------------------------------------------------: |
|  autoplay|	autoplay	|Specifies that the video will start playing as soon as it is ready   |
|autoplay|	autoplay|	Specifies that the video will start playing as soon as it is ready|
|controls|	controls|	Specifies that video controls should be displayed (such as a play/pause button etc).|
height|	pixels|	Sets the height of the video player|
loop	|loop	|Specifies that the video will start over again, every time it is finished|
muted	|muted	|Specifies that the audio output of the video should be muted|
poster	|URL	|Specifies an image to be shown while the video is downloading, or until the user hits |


![video tag](https://image.slidesharecdn.com/html5audiotagintro-140916231519-phpapp02/95/intro-to-html5-audio-tag-7-638.jpg?cb=1410931097)

![audio tag](https://www.tutorialbrain.com/wp-content/uploads/2019/07/HTML5-Audio-tag.png)
