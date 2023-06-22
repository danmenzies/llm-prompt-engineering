# Social Media Posts about Videos

This prompt helps generate engagiong social media posts about your YouTube videos. This was created with a **lot** 
of experimenting, and trial and error; and seems to do reasonably well in terms of engagement.

Before running this prompt, you will need:

* The transcript or voiceover script for your video
* A list of hashtags you'd like to include in your description

### Step 1: Priming the model

```textmate
The following is the voiceover script for a YouTube video:
{paste your script here}

Once you have read this, please say only "I understand".
```

### Step 2: Generating a Tiktok post

```textmate
Please think like an expert in TikTok SEO and Social Media Engagement. Please write a very long caption for a TikTok post containing this video. Please be extremely verbose. Please avoid line breaks. Please use emojis, but do not add emojis to the first sentence.

Please include the following hashtags exactly once each:
{paste your hashtags here}

Please include any other hashtags you think are relevant. Please place hashtags throughout the body of the description, and not just at the end.
```

Note, with this prompt, you may need to edit the generated text to remove line breaks, and to remove any hashtags that
are not relevant to your video.

### Step 3: Generating a Facebook post

```textmate
Please think like an expert in Facebook SEO and Social Media Engagement. Please write a very long caption for a Facebook post linking to this video. Please be extremely verbose. Please avoid line breaks. Please use emojis, but do not add emojis to the first sentence.

Please include the following hashtags exactly once each:
{paste your hashtags here}

Please include any other hashtags you think are relevant. Please place hashtags throughout the body of the description, and not just at the end.
```
### Step 4: Generating a Twitter post

```textmate
Please think like an expert in Twitter SEO and Social Media Engagement. Please write Twitter post linking to this video. Please avoid line breaks. Please use emojis, but do not add emojis to the first sentence. Please be succinct.

Please include the following hashtags exactly once each:
{paste your hashtags here}

Please include any other hashtags you think are relevant. Please place hashtags throughout the body of the description, and not just at the end.
```