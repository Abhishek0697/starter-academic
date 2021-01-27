---
title: Photometric Stereo
summary: Python, NumPy, Matplotlib, Scikit-image
tags:
- Computer Vision
date: "2020-05-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: normals_enforced
  focal_point: Smart
  preview_only: true

links:
# - icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/imad0697
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""



gallery_item:
- album: <Photometric Stereo>
  image: albedoIm.png
  caption: Albedo Image, visualized with colormap 'gray'

- album: <Photometric Stereo>
  image: normalIm.png
  caption: Normal Image, visualized with colormap 'rainbow'
  
- album: <Photometric Stereo>
  image: depthmapuncalibone.png
  caption: Depthmap View 1, visualized with Axes3D object in Matplotlib

- album: <Photometric Stereo>
  image: depthmapuncalibtwo.png
  caption: Depthmap View 2, visualized with Axes3D object in Matplotlib 

- album: <Photometric Stereo>
  image: depthmapuncalibthree.png
  caption: Depthmap View 3, visualized with Axes3D object in Matplotlib

- album: <Photometric Stereo>
  image: depthmapuncalibfour.png
  caption: Depthmap View 4, visualized with Axes3D object in Matplotlib

---
#### What we did
- Estimated Pseudonormals, and visualized the Albedo, Normal images and Shape of the face  
- Understanding and Rendering of n-dot-l Lighting

<br>

### Image gallery
{{< gallery album="<Photometric Stereo>" >}}

<br>
<br>

#### Rendering n-dot-l lighting for a uniform fully reflective Lambertian sphere
{{< figure src="ndotl.png" title="Rendered images for 3 different light sources" >}}  


<br>
<br>
Acknowledgements - This project is done as a part of the course curriculum in 16-720:Computer Vision @ Carnegie Mellon University

