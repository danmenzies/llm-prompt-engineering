# YouTube Long SEO Description

This prompt helps generate SEO-optimised descriptions for YouTube videos. This was created with a **lot** of experimenting,
and trial and error. This seems to score well in VidIQ and TubeBuddy, and is a good starting point for your own.

Before running this prompt, you will need:

* The transcript or voiceover script for your video
* The list of tags you intend adding to your video (up to around 400 characters)
* A list of additional keyword phrases you'd like to include in your description
* A list of keywords you want to avoid
* A list of hashtags you'd like to include in your description

### Step 1: Priming the model

> The following is the voiceover script for a YouTube video:<br>
> `{paste your script here}`
>
> Once you have read this, please say only "I understand".

### Step 2: Generating the description

> Please think like an expert in YouTube SEO and Engagement. Please write a very long essay style description for this video.
>
> Please include the following keyword phrases exactly twice each:<br>
> `{paste your 3 most relevant tags here}`
>
> Please include the following keyword phrases exactly three times each:<br>
> `{paste your additional tags here}`
>
> Please avoid the following keyword phrases:<br>
> `{paste your avoid keywords here}`
>
> Please include the following hashtags exactly once each:<br>
> `{paste your hashtags here}`
>
> Please scatter relevant hashtags throughout the body of your response. Please be verbose. Please use clear, essay style writing. Do NOT add "tag cloud" at the end of your response; do NOT create paragraphs less than 5 words long.

### Step 3 (Optional): Generating a Description Introduction

If the previous step generated a description that is a little short, you can use this prompt to generate a short 
introduction. This will generate a one-paragraph introduction that can be placed at the start of the video
description; and **may** increase the SEO score of your video.

> Please think like an expert in YouTube SEO and Engagement. Please write a two sentence introduction for the YouTube description of this video.
>
> Please include the following keyword phrases exactly once each:<br>
> `{paste your 3 most relevant tags here}`
>
> Please avoid the following keyword phrases:<br>
> `{paste your avoid keywords here}`
>
> Please include the following hashtags exactly once each:<br>
> `{paste your hashtags here}`

### Step 4 (Optional): Generating a Compound Title

If you're struggling with titles, this can also help:

> This video has a working title of `{working video title}`; but I think it could be better.
> 
> Please think like an expert in YouTube SEO and Engagement. Please create a succinct, catchy, clickable title, for this video.
> 
> Please use at exactly 3 of these keyword phrases in the title:
> `
> {paste your 3 most relevant tags here}
> {paste your avoid keywords here}
> `
> 
> You may also compound keyword phrases to make your title. For example, if the phrases 'stock market', 'stock market news', 'us stock market' were in the list, you could use 'The latest US Stock Market News' to capture all three keyword phrases
> 
> Please be extremely succinct. Please stay under 55 characters. Please ensure the subject matter of `{working video title}` is accounted for in the title. Please make use of camel casing where appropriate. 
