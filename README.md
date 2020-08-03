# Android-ImageResizer
Class allowing to reduce a high-resolution image or drawable for a smaller resolution component without quality loss.

## How to use

```
ImageView.setImageBitmap(ImageResizer.decodeSampledBitmapFromResource(Resources res, int resId, int reqWidth, int reqHeight))
```
