# Web Page Meta Tags

The following prompt uses tree-of-thought to generate meta tags for a web page. This is a work in progress, and is not 
yet complete; but generates very reasonable results.

### Option 1: Pre-launch website

Use this version of the prompt if you are creating a new website, and want to generate meta tags before the website is
live, or if `robots.txt` is blocking access to the website.

```textmate
Here is the contents of a web page:
{past your copy here, wrapped in backticks}

There are 3 subject matter experts in a room:
* Website content expert
* SEO Expert
* Online Marketing Expert

They are discussing the best way to drive engagement on on the current web page, without changing the front-facing content on the page. They have decided the best approach is to update the:
* Focus keyword phrase
* SEO Title
* SEO Meta Description
* Open Graph Description

Please document their discussion as they find the best keyword phrase for this page, and the precise wording for the title and each of the meta tags. Please show the conversation as a markdown table where each column represents a subject matter expert's input.

Once the discussion has concluded, please show the final decision as a markdown table with the columns `tag` and `content`
```

### Option 2: Indexable website

```textmate
Please review the contents of this  web page:
{fully qualified URL, wrapped in backticks}

There are 3 subject matter experts in a room:
* Website content expert
* SEO Expert
* Online Marketing Expert

They are discussing the best way to drive engagement on on the current web page, without changing the front-facing content on the page. They have decided the best approach is to update the:
* Focus keyword phrase
* SEO Title
* SEO Meta Description
* Open Graph Description

Please document their discussion as they find the best keyword phrase for this page, and the precise wording for the title and each of the meta tags. Please show the conversation as a markdown table where each column represents a subject matter expert's input.

Once the discussion has concluded, please show the final decision as a markdown table with the columns `tag` and `content`
```