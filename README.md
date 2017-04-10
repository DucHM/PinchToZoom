# PinchToZoom
Android's ImageView pinch-to-zoom made easy

## Sample app
<a href='https://play.google.com/store/apps/details?id=com.bogdwellers.pinchtozoom&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' width="223" /></a>

## Overview
PinchToZoom for Android is a simple but feature complete library for adding pinch-to-zoom functionality to an *ImageView*. It has sleek easing animations that make it stand out in quality and ease of use.

### Features
* Pinch-to-zoom
* Double-tap to quickly zoom-in and out
* Drag while zoomed in
* Animated drag & zoom release easing
* Does not extend the *ImageView* class so is usable with custom *ImageView* implementations
* Fully customizable

## Integrate
Adding pinch-to-zoom functionality to your *ImageView* is easy as this:
```java
ImageView imageView = (ImageView) view.findViewById(R.id.image);
imageView.setOnTouchListener(new ImageMatrixTouchHandler(view.getContext()));
```

## Customization
The *ImageMatrixTouchHandler* class has multiple getter/setter methods that allow for changing the behavior and animation settings.
