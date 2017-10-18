# Shopify Snippet - Video Thumbnail Generator

Works with YouTube and Vimeo.

### Usage

**Short**

```liquid
{% include 'video_thumbnail' with section.video %}
```

**Extended**

```liquid
{% include 'video_thumbnail' video: section.video, size: 'full' %}
```

### Arguments

**video**

Video object from section, block or theme settings.

**size**

```
default: thumbnail
options: thumbnail / small / medium / high / full
```


**link**

Add link with URL for iframe or direct to video page.

```
default: none
options: none / iframe / video
```
