# Facebook-Automated-Image-Tags
A Chrome Extension that displays the automated image tags that Facebook has generated for every images.

<img width="524" src="https://drive.google.com/open?id=0BxNDg7WiUi0fZ0plZTFfcFZyZlU">

Since April 2016, Facebook has been [automatically adding `alt` tags](https://code.facebook.com/posts/457605107772545/under-the-hood-building-accessibility-tools-for-the-visually-impaired-on-facebook/) to images
you upload that are populated with keywords representing the content of your images:

```html
<img csrc="https://facebook.com/some-url.jpg"
alt="Image may contain: golf, grass, outdoor and nature"
width="316" height="237">
```
They are labeling your images using a Deep ConvNet built by Facebook's
[FAIR team](https://research.fb.com/category/facebook-ai-research-fair/).

On one hand, this is really great. It improves accessibility for blind users
who depend on screen readers which are only capable of processing text.

But I think a lot of internet users don't realize the amount of information that is now routinely extracted from photographs. Facebook (and Google, Apple, Amazon, etc) can easily tell from your photographs if you have a pet dog, if you collect cameras, if you play golf, if you have children, or if you are just really into sunglasses. There's nothing stopping them from using this information to show you relevant ads just based on photos of you - even if another user uploaded the photo and didn't even directly tag you!

This is a very simple Chrome Extension that I hacked together in a few minutes to make it easy to see the tags that Facebook is automatically applying to you and your friends' photos. Once you install it, all the photos you see on your Facebook timeline will automatically be overlaid with their tags, like this:

<img width="524" src="https://drive.google.com/open?id=0BxNDg7WiUi0fZ0plZTFfcFZyZlU">
