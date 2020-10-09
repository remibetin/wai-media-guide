---
title: "Audio Description of Visual Information"
title_image: /content-images/wai-media-guide/ad.svg

nav_title: "Description"

lang: en   # change "en" to lang code, here and 2 @@s below
last_updated: 2019-09-10   # Change to date of translation YYYY-MM-DD (month in middle)
# translator: "..."
# contributors: "..."

permalink: /media/av/description/   # Add lang to end /link/to/page/@@
ref: /media/av/description/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/description.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  ref: /media/av/
navigation:
  previous: /media/av/player/
  next:     /media/av/captions/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: Helps you understand and create description of visual information (called audio description, video description, and described video) for audio and video media accessibility.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date:</strong> Updated 10 September 2019. CHANGELOG.</p>
   <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
   <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Originally drafted as part of the <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA Project</a> funded by the <abbr title="United States">U.S.</abbr> Access Board. Revised as part of the <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access project</a> funded by the Ford Foundation.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page helps you understand and create description of visual information (called _audio description_, _video description_, and _described video_) for new and existing videos. (It does not apply to audio-only, such as podcasts.)

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{::options toc_levels="2,3" /}
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Introduction

_What:_ Audio description describes visual information needed to understand the content. (For example, "Pat opens a jewelry box, looks at a diamond engagement ring, and cries".) Description is usually narration added to the soundtrack.

_Who:_ Description provides content to people who are blind and others who cannot see the video adequately.

_Example:_ [Video that includes audio description of the visual information (YouTube)<br>{% include image.html src="using-description.jpg" alt="" class="large video" %}](https://www.youtube.com/watch?v=F3A1VffiOH4&list=PLhDEeYUfW02Qo4r2KlzagxZxhYcZADee-&index=3)

### Terminology
{:.no_toc}

Description of visual information provided via audio is called "audio description" in Web Content Accessibility Guidelines (WCAG). In some regions and documents it is called "video description" or "described video".

This resource uses "described video" in some places as a shortened form of "a video that includes description of the visual information in audio".

## Does My Media Need Description? {#checklist}

This section tells you:
* What is required in the WCAG standard at Level A, AA, and AAA. _([WCAG](/media/av/planning/#wcag-standard) is introduced in the Planning page of this resource.)_
* What is needed to meet user needs, beyond WCAG. If there are no "A"s, then it is not required in WCAG.

{% capture boxhead %}
Audio-only (e.g., podcast):
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-ao" %}
{:/}

*   For pre-recorded and live:
    *   Description is not needed because there is no visual information.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% capture boxhead %}
Video:
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="checklist-video" %}
{:/}

**Does the video have visual information** that is needed to understand what the video is communicating?

*   If no (for example, it is only a person talking):
    *   Description is not needed. Consider [informing users](/media/av/planning/#none).
*   If yes:
    *   For pre-recorded:
        *   Description is needed to provide the important visual information to people who are blind and listen to the video.  
            Description is **_required_** in WCAG at Level A or AA.
        {:.alt}
    *   For live:
        *   Description is needed to provide the important visual information to people who are blind.  
            Description is not required to meet WCAG.
        {:.alt}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Description Considerations, Skills, and Tools

When accessibility is considered _before_ videos are produced, it significantly cuts down on cost and effort to develop description. For some types of video (such as some training videos), description of the visual information can be seamlessly integrated by the speakers as the video is planned and created, and you don't need separate description, thus there is no additional cost.

Information on planning for description in _new videos_ is in the "Creating Audio and Video Content" page, [Plan for Audio Description of Visual Information section](/media/av/av-content/#plan-description).

To add description to _an existing video_, you'll either need skills and tools to:
* write it
* create a VTT file with the timed descriptions

Or:
* write it
* narrate it
* record it
* integrate it in new audio and/or video files

Many organizations choose to outsource their description.

## What Method of Description?

What method to use for description depends on your video content and the media player that you use. First, figure out these issues about your video content, timing, and player:

* **Integrated** &mdash; For new videos, can the speakers describe the relevant visual information as the video is recorded? This works for well for some videos, such as presentations and instructional videos. For examples, see the "Creating Audio and Video Content" page, [Integrated Description section](/media/av/av-content/#integrate-description).

* **Media player support** &mdash; Information about media player functionality is in the Accessible Media Players page under [Existing Players](/media/av/player/#existing-players). Does the media player, platform, or plug-in that you are using provide functionality for:
   * description from a text file?
   * a separate audio track for description?

<a id="space"> </a>
* **Space in audio** &mdash; Is there enough space in the main audio for the description? That is, are there sufficient pauses throughout the narration or speaking where the relevant description will fit? For example,
   * If the only description needed is at the beginning of the video where these is a text title and background music, then: Yes, there is enough space.
   * If the speaker talks continually without pausing, then: No, there is not enough space for description.

***Use the information from above to answer the following questions*** in order to determine what method to provide description for your video. The options listed first are usually the best, yet you can choose another option.

{% capture boxhead %}
Description method:
{% endcapture %}

{::nomarkdown}
{% include box.html type="start" title=boxhead class="highlighted" id="method-tree" %}
{:/}

*   Is it a new video _and_ can the speakers describe the visual information in the main audio?
    *   If yes, provide **integrated description** (no separate description is needed),  
        _**or**_ another option below.
    *   If no, will you use a media player that provides functionality for description from a text file?
        *   If yes, provide description in a **timed text file**,  
            _**or**_ another option below.
        *   If no, will you use a media player that supports a separate audio track for the description, _and_ is there enough space in the main audio for the description?
            *   If yes, provide description in a **separate audio file**,  
                _**or**_ provide a **separate described video**.
            *   If no, provide a **separate described video**.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Options for Creating Description

Depending on your video situation, do one of the options below &mdash; as determined from the "What Description to Provide for My Video?" section above.

### Integrated &ndash; Creating Integrated Description

This approach works for some new videos. The process to develop a video with integrated description is basically:
1. When writing the script, make sure all relevant visual information is included. See [Tips for Writing Descriptions below](#writing) and examples in Accessible Audio and Video Content, [Integrate description section](/media/av/av-content/#integrate-description))
2. Before finalizing the video, check to confirm that all relevant visual information is covered in the audio.

### Text &ndash; Creating Description in a Text File

This approach only works when the media player that you're using supports text-based audio description that is read aloud. And, either the description fits in the space of the main audio, or the player provides functionality to pause during audio description. It requires someone to create a timed text file &mdash; minimal skills are needed; tools are not required, yet, they make it faster and easier.

The process to develop descriptions in a text file is basically:
1. Write out the descriptions. See [Tips for Writing Descriptions below](#writing).
2. Add the timestamps for the descriptions in the file format used by the media player. It is usually [WebVTT like the example below](#vtt).

(Make sure the descriptions file is included with the video.)

If the descriptions do not fit into the main audio space, provide instructions to users to set their player to pause the video during audio description. For example:

{::nomarkdown}
{% include box.html type="start" title="To set the video to pause for audio description of visual information:" class="" %}
{:/}

<img src="{{ "/content-images/wai-media-guide/player-preferences.png" | relative_url }}" alt="" class="" style="float: right; height: 7em; padding-left 7px;'">

* Select "Preferences", then "Descriptions".<br>
The "Audio Description Preferences" box opens.
* Under "Text-based audio description", select the checkbox for "Automatically pause video when description starts".
* Select the Save button.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Audio Only &ndash; Creating Description in a Separate Audio File Only

This approach only works when there is enough space in the main audio for the description, *and* the media player supports a separate audio track for the description. This requires skills and software for audio recording and audio editing.

The process to develop description in a separate audio file is basically:
1. Write out the descriptions. See [Tips for Writing Descriptions below](#writing).
2. Record the descriptions. See [Tips for Recording Descriptions below](#recording).
3. Ensure the descriptions play in the audio spaces with the main video.
4. Provide a caption file of the description. [Example VTT file of audio description](#vtt)

(Ensure the files are integrated with the player on the web page.)

### Video with Space &ndash; Creating a Separate Described Video - If Descriptions Fit in Audio Spaces

This applies if the descriptions do fit in the spaces, as described in [Space in audio above](#space)_. It requires skills and software for audio recording and video editing. Depending on the player that you are using, you might need video software to regenerate the video.

The process to develop a separate audio file is basically:
1. Write out the descriptions. See [Tips for Writing Descriptions below](#writing).
2. Record the descriptions. See [Tips for Recording Descriptions below](#recording).
3. Create a new audio file by combining the original audio and the new description audio. See [Tips for Combining Audio Files below](#combining).
4. Provide the file(s):
* _**If**_ your player uses separate video and audio tracks,<br>you're done.
* _**If**_ your player uses a single video file that includes the audio,<br>generate the new described video with the audio file that you just created.

(Make sure on the web page where the video is available, the Described version uses the correct version that you just created.)

### Video Without Space &ndash; Creating a Separate Described Video - If Descriptions Do _Not_ Fit in Audio Spaces

If all the descriptions do **not** fit in the spaces _(as described in [Space in audio above](#space)_), you'll need to develop a separate audio file and also edit the visual track. This requires skills and software for audio recording, audio editing, and video editing.

The process to develop a separate audio file and edit the visual track is basically:
1. Write out the descriptions. See [Tips for Writing Descriptions below](#writing).
2. Record the descriptions. See [Tips for Recording Descriptions below](#recording).
3. Create a new audio file by combining the original audio and the new description audio. See [Tips for Combining Audio Files below](#combining).
4. Create a new video:
	* _**If**_ you have source video with longer scenes _(as described in Accessible Audio and Video Content, [Time for description section](/media/av/av-content/#time-for-description))_, recut the scenes longer to fill in the visual space where you need to accommodate the time for the description.
	* _**If not or if you're adding to an existing video**_, you will need to leave a static image in the video while the description is playing in the audio. <!-- (For example, this video [@@ need very good example - see GitHub](https://github.com/w3c/wai-media-guide/issues/73) pauses at 00:00 for the audio description.) -->

(Make sure on the web page where the video is available, the Described version uses the correct version that you just created.)

### Other Options
{:.no_toc}

* Extended Description with SMIL &mdash; The only markup-based method for providing extended audio descriptions is to use SMIL 3.0. Support for SMIL is very limited. Implementations would most likely require plug-ins and/or heavily customized approaches.
* Provide functionality for the video to pause for the description &mdash; This is not suggested in most cases because it requires extra coding and provides a less-than-optimum user experience.

{% include_cached excol.html type="start" id="tips" %}

## Tips for Doing Description Yourself

{% include_cached excol.html type="middle" %}

### Tips for Writing Descriptions {#writing}
{:.no_toc}

* Describe the visual elements that are important to understand what the video is communicating. Imagine that you are describing the video to someone who cannot see it &mdash; what do you say? You don't need to describe every detail or things that are apparent from the audio.
* Describe objectively, without interpretation, censorship, or comment.
* Write description in present tense, active voice, and third-person narrative style.

More guidance on writing descriptions is available on the web, for example: [Description Tip Sheet {% include_cached external.html %}](https://dcmp.org/learn/227) and [How to Describe {% include_cached external.html %}](http://www.descriptionkey.org/how_to_describe.html).

### Tips for Recording Descriptions {#recording}
{:.no_toc}

* Use a voice, style, and delivery that is distinguishable from other voices used in the video.
* Use a neutral voice that does not convey emotions.
* When recording a single file with timed descriptions, voice the descriptions at the same time as the visual content, or right before the visual content. Don't put the description after the visual content.
* See [guidance on audio content](/media/av/av-content/#audio).

### Tips for Combining Audio Files {#combining}
{:.no_toc}

* Put descriptions at the same time as the visual content, or right before the visual content. Don't put the description after the visual content.

* Make the description clear above other noises. When mixing the descriptions with the main audio, lower the main audio level when the description plays and raise the description audio level. When the description is finished playing, lower the description audio level and raise the main audio level to its normal setting. Repeat this process (known as "ducking") for every description instance.

{% include_cached excol.html type="end" %}

### VTT File
{:.no_toc}

{::nomarkdown}
{% include box.html type="start" title="Example VTT file of audio description" class="" id="vtt" %}
{:/}

```
WEBVTT

00:00:04.000 --> 00:00:07.980
<v Audio Descriptions>A man sitting at a desk starts watching a video on his computer. 

00:00:17.260 --> 00:00:20.780
<v Audio Descriptions>The video on his computer shows a person speaking to the camera.

00:00:20.780 --> 00:00:23.140
<v Audio Descriptions>It is playing with no audio.

00:00:26.880 --> 00:00:29.620
<v Audio Descriptions>The man watching the video has a hearing aid.
```

{::nomarkdown}
{% include box.html type="end" %}
{:/}