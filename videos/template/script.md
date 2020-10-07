---
size: 720p
background: bach_cello.mp3 fade-out
transition: crossfade 0.2
theme: light
voice: Elisabeth 
---

<!--

This is just a comment, Narakeet will ignore it. Useful for metadata!

A full description of the capabilities, stage directions and other ways to
assemble a script can be found here:

https://www.narakeet.com/docs/format/

-->

![](moj_logo.png)

(pause: 3)

This is a short template video from which you'll be able to create training
videos about the Ministry of Justice's Analytical Platform.

(pause: 1)

All videos should start and end with the `MOJ` logo.

(pause: 1)

Note that characters enclosed within backticks are spelled out. Like `this`

---

![](analytic_platform_tools.png)

(pause: 1)

Scenes in the video can have a background image.

It is possible to change the tone of voice and articulation in interesting
ways.

For instance,

(voice: william)

You can change voice..!

---

![](analytic_platform_tools.png)

(voice: carol) 

Various vocal effects can be controlled via Markdown.

This is my usual voice.

_This is more important._

**This is really important.**

~~This is not so much.~~

(pause: 1)

---

![](analytic_platform_tools.png)

(voice: elisabeth) 
Finally, depending on the voice you choose to use,
fine grained pronuntiation can be controlled by `SSML`
(speech synthesis markup language).

<speak>
  <prosody rate="slow" pitch="-2st">
    Can you hear me now?
  </prosody>  
  <say-as interpret-as="verbatim">
    abcdefg
  </say-as>
</speak>

---

![](analytic_platform_tools.png)

(pause: 1)

(voice: william) 

It's possible to add subtitles too.

---

```
Adding text to a scene is easy!
```

Adding text to a scene is easy.

Just enclose it within three backticks.

---

```python
def hello(name="World!"):
    """
    Return a friendly greeting.
    """
    return f"Hello, {name}"

greeting = hello("Boris")
print(greeting)
```

(voice: carol) 
It's even possible to embed fragments of formatted code, if needed.

(pause: 2)

---

![00-05](unidling_ap.mp4)

Embedding `MP4` video is also easy.

---

![05-12](unidling_ap.mp4)

Schedule, to the second, when narration happens over a video.

---

![](narakeet.mp4)

(voice: elisabeth) 
Once you have a script, upload all the files to Narakeet. Making a video should
take no more than 5 minutes.

You may need to refine and adjust to get the best results.

---


![](moj_logo.png)

(pause: 1)

Please ensure you end your video with the `MoJ` logo.

(pause: 2)

(voice: william) 
To make any background music fade out at the end,
adjust the background property in the meta-data at
the start of the video.

(voice: carol) 
Best of luck!

(pause: 3)
