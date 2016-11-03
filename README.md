# GIFImageView

> Simple way to show GIF images on to UIImageView. 

This is a obj-c porting project based on https://github.com/Flipboard/FLAnimatedImage.

### Usage

```
var data = NSData.FromUrl(NSUrl.FromString("https://media.giphy.com/media/sC8wSpmcVazMk/giphy.gif"));
AnimatedImage image = AnimatedImage.AnimatedImageWithGIFData(data);
AnimatedImageView imageView = new AnimatedImageView();
imageView.AnimatedImage = image;
imageView.Frame = new CGRect(10, 70, this.View.Frame.Width - 20, 200);
this.View.AddSubview(imageView);
```

### Output

![](https://github.com/guntidheerajkumar/GIFImageView/blob/master/output.gif)
