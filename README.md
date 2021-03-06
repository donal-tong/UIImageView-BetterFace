UIImageView-BetterFace
======================

a UIImageView extension to let the picture-cutting with faces showing better

##Why?

 - Have problems showing the resized image previews? 
 - People in the preview only have chins but not faces?
 - A group photo doesn't look well?

Try UIImageView-BetterFace!

Like this:

![preview](https://raw.github.com/croath/UIImageView-BetterFace/master/doc/preview.png)

##How?

 - 1. drag `UIImageView+BetterFace.h` and `UIImageView+BetterFace.m` to your project
 - 2. import the .h file
 - 3. add `hack_uiimageview_bf();` to your `main` function
 - 4. add this:`[anImageView setNeedsBetterFace:YES];`
 - 5. done
 - 6. still have problems? clone the project and see the demo.

##Known issues

 - it will be slow to render large-size images, and showing the strange animation
 - it may take a lot of memory while reusing the UIImageView
 
##Other

Any issue and pull request is welcome.
