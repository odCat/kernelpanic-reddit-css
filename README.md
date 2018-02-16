# kernelpanic-reddit-css
First task on the KernelPanicPodcast: Create a style sheet for the subreddit

# jQuery to load the CSS file
#  works on Chrome
$("head").append("<link>");
var css = $("head").children(":last");
css.attr({
      rel:  "stylesheet",
      type: "text/css",
      href: "https://cdn.rawgit.com/odCat/kernelpanic-reddit-css/9309def4/kernelpanic-reddit.css"
});
