API used: 28 (Min API: 26)
AVD tested on: Pixel API28


Toolbar: LoadBtn ClearBtn FilterRatingBar ResetFilterBtn("X“)
- LoadBtn: load images from url, will clear old images if old images exist, will reset FilterRatingBar to 0
- ClearBtn: clear images, will reset FilterRatingBar to 0
- FilterRatingBar: filter images by rating, only show images with rating >= the value of FilterRatingBar
(When changing the rating of an image with filter applied, if new rating >= filterVal, image still shows. If new rating < filterVal, image will disappear.)
- ResetFilterBtn: reset FilterRatingBar to 0

Image: ImageView ImageRatingBar ResetRatingBtn("X“)
- Clicking on ImageView will pop a window showing enlarged image, clicking again at popWindow will return to image gallery
- ImageRatingBar shows the rating of the image, click stars to change
- Clicking on ResetRatingBtn will clear the image rating

Layout:
- With horizontal orientation, it will show 2 images in 1 row
- With vertical orientation, it will show 1 image in 1 row


 