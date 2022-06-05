# music_enjoy（0.0.10）


## Project Introduction

I believe that everyone has such an experience, often inadvertently hear a certain song played by others, and become interested in it.

Since I only remembered some lyrics, I opened Baidu and searched for the song. After finding the song name, I opened the network and searched for the song. Then the classics came, "I'm listening to the "xxx" song clips, and I have opened the VIP to listen to the full version." Exit this page now to avoid wasting valuable time).

As a senior "white prostitute" netizen, I can only do it myself. Hence this simple python package.

Since Wangyiyun has copyright, we can go to B station to search for related videos and listen to this song, but if you want to enjoy it with headphones anytime, you can't keep B station open in the background all the time, right? It's not good for listening to other songs either. So there is an idea: climb down the songs of station b and import them into NetEase cloud disk. This will really "listen to" ~~~


## Instructions

### package installation

- Domestic Tsinghua source

```shell
pip install music_enjoy -i https://pypi.tuna.tsinghua.edu.cn/simple
```



### Usage example


```python
import music_enjoy as me

url = 'https://www.bilibili.com/video/BV1aP4y177x2/?spm_id_from=autoNext' # your video url
dest = './1.m4a' 			# Resource storage location, which can be an absolute path or a relative path
audio_or_video = 'audio' 	# Download audio or video

me.bilibili(url=url, dest=dest, audio_or_video=audio_or_video)
```



## Currently supported features

### Bilibili Barrage Network video and audio download separately



## Features under development

### Audio and video synthesis

### Cool me, cool dog download


### 

### 

