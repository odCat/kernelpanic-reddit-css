# Introduction
First task on the KernelPanicPodcast: Create a style sheet for the subreddit

# jQuery command to load the CSS file:
Important: Change the href attribute with the latest value; see RawGit below.
```
$("head").append('<link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/odCat/kernelpanic-reddit-css/eac8c283/kernelpanic-reddit.css" />');
```
# RawGit: https://rawgit.com/
RawGit serves raw files directly from GitHub with proper Content-Type headers.
It can be used to generate the href value passed to the jQuery command mentioned above

# Command to load jQuery if/when neccessary:
```
$("head").append('<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>');
```

# Picture INFO
The picture used is free under the Pexels License. Click [here](https://www.pexels.com/photo/interior-of-office-building-325229/) for the link.
Author: [Manuel Geissinger](https://www.pexels.com/@artunchained)

# TODO
Find a way to improve the quality of the inverted image.
