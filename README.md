# Facebook-Automated-Image-Tags
A Chrome Extension that displays the automated image tags that Facebook has generated for every images.

Since April 2016, Facebook has been [automatically adding `alt` tags](https://code.facebook.com/posts/457605107772545/under-the-hood-building-accessibility-tools-for-the-visually-impaired-on-facebook/) to images
you upload that are populated with keywords representing the content of every images.

They are labeling your images using a Deep ConvNet built by Facebook's
[FAIR team](https://research.fb.com/category/facebook-ai-research-fair/).

On one hand, this is really great. It improves accessibility for blind users
who depend on screen readers which are only capable of processing text.

But I think a lot of internet users don't realize the amount of information that is now routinely extracted from photographs. Facebook (and Google, Apple, Amazon, etc) can easily tell from your photographs if you have a pet dog, if you collect cameras, if you play golf, if you have children, or if you are just really into sunglasses. There's nothing stopping them from using this information to show you relevant ads just based on photos of you - even if another user uploaded the photo and didn't even directly tag you!

This is a very simple Chrome Extension that I hacked together in a few hours to make it easy to see the tags that Facebook is automatically applying to you and your friends' photos. Once you install it, all the photos you see on your Facebook timeline will automatically be overlaid with their tags.

The goal is simply to make everyone aware of the kind of information that is routinely extracted from your own images today.

### Objects in your photos
It's possible to tell what kinds of objects are in your photos and identify your interests based on that.

### Activities you are doing
Whether you are eating, running, or playing, it's possible for an algorithm to tell what you are doing in your photographs.

### When and where a photo was taken
Identifies if a photo was taken inside or outside, what the time of day was, what physical landmarks (mountains, trees, water, etc) were around, and so on.

### Events you are attending
It's even possible to tell which kind of sporting event you are attending.


# Installing this Chrome Extension
From Source
1. Clone this repo so you have a copy in a folder locally.
1. Open `chrome://extensions` in the location or go to `Tools` > `Extensions`
1. Enable `Developer mode` by checking the checkbox in the upper-right corner.
1. Click on the button labelled `Load unpacked extension...`.
1. Select the directory where you cloned this repo to.
1. Visit Facebook!
