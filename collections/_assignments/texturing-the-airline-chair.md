---
title: Texturing the Airline Chair
layout: blocks-assignment-view
date-assigned: 2020-08-31T04:00:00.000+00:00
date-due: 2020-09-08T03:59:00.000+00:00
page_sections:
- template: assignment-description
  block: assignment-a-description
  title: Description
  content: In this exercise, you will practice unwrapping UVs, exporting a UV map,
    and creating textures in 2D image editing software like Photoshop. You will then
    apply your textures to a polygonal model of the 1927 Kem Weber Airline Chair.
- template: assignment-learningobjectives
  block: assignment-b-learningobjectives
  title: Learning Objectives
  numbered-items-list:
  - Become familiarized with 3D software interface and terminology.
  - Use texturing workflows to add color and texture to your polygonal models.
  - Perform fundamental UV unwrapping operations including UV unwrap, mark seams,
    and project from view.
  list-item: []
- template: assignment-demo
  block: assignment-a-demo
  title: Demonstration Videos
  content: In this five part video demonstration seres, I show a basic texturing workflow
    to add color and detail to the Kem Weber Airline Chair using Blender 2.8.
  video:
  - title: Texturing the Airline Chair Video Playlist
    custom: <iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PL-V2nChTadrUGw6OioaTkVBSCP12C9mjq"
      frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
  - title: Live demo for alternate model workflow
    vimeo_url: https://vimeo.com/454111709
- template: assignment-supportingmaterial
  block: assignment-c-supportingmaterial
  title: UV Mapping Tutorials
  content: To get a deeper understanding of how Blender's texturing tools work, have
    a look these tutorials
  material:
  - readings:
    - _readings/beginner-lesson-1-reading.md
  readings: []
  video:
  - title: Blender Beginner UV Unwrapping Tutorial
    youtube_url: https://www.youtube.com/watch?v=XeBUfMKKZDo
    custom: ''
  - title: Blender Foundation 2.8 Videos (16-19)
    custom: <iframe width="100%" height="100%" src="https://www.youtube-nocookie.com/embed/videoseries?list=PLa1F2ddGya_-UvuAqHAksYnB0qL9yWDO6"
      frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope;
      picture-in-picture" allowfullscreen></iframe>
  links: []
- template: assignment-supportingmaterial
  block: assignment-c-supportingmaterial
  title: Airline Chair Model Download
  links:
  - title: Airline Chair Base Model
    link_style: new tab
    url: https://drive.google.com/file/d/1BRJ8TtAyufkt4GIMuo6ivUOTHrSVsZCO/view
  content: If you had trouble with your model's mesh, you can complete the assignment
    by texturing this simplified model.
- template: assignment-referencedmaterial
  block: assignment-d-referencedmaterial
  links:
  - title: CC0 Textures
    url: https://cc0textures.com/
    link_style: new tab
  - title: Textures.com
    link_style: new tab
    url: https://www.textures.com/
  title: Texture resources
  content: 'Use these websites to find textures to apply to your model. '
- template: assignment-referencedmaterial
  block: assignment-d-referencedmaterial
  title: Image References
  content: Download the following images and include them in your project folder.
  links:
  - title: '3/4 view of Kem Weber Airline Chair '
    url: https://images.collection.cooperhewitt.org/244141_743985d156708c43_b.jpg
    link_style: " download"
  - title: 'Side view of Kem Weber Airline Chair '
    url: https://images.collection.cooperhewitt.org/244191_5cd7e8666b5a9bfe_b.jpg
    link_style: " download"
  headline: Airline Chair Reference Images
- template: assignment-supportingmaterial
  block: assignment-c-supportingmaterial
  title: Extras
  image-gallery: []
  links:
  - title: Blender Hotkey Poster
    link_style: " download"
    file_download: "/uploads/blender-infographic-lowres-preview-giudansky.jpg"
    url: https://www.giudansky.com/illustration/infographics/blender-map
- template: assignment-rubric
  block: assignment-f-rubric
  title: Rubric
  content: ''
  rubric_criteria:
  - criteria_title: Attention to Detail
    criteria_description: This criteria looks at if the assignment was submitted on
      time, if each step was completed to a high degree of accuracy, and if file naming
      conventions were followed.
    criteria_weight: 5 pts
  - criteria_title: Learning by doing (Completed all steps)
    criteria_description: This criteria assess whether you completed the assignment's
      given set of instructions. This indirectly infers how well you acquired foundational
      skills and theory.
    criteria_weight: 5 pts
topics_covered:
- uvs
- " texturing"
- " seams"
- unwrapping
- uv projection
prerequisites: []
difficulty_level: " beginner"
header_image: "/uploads/airline-chair-header-compressed.jpg"
header:
  image_fullwidth: "/uploads/airline-chair-texturing-header.jpg"
accordion_mode: true

---
## Instructions

 1. Watch linked tutorials in Learning Resources from Blender Foundation and others to get acquainted with texturing tools.
 2. Duplicate the modeling folder on your computer. **This will be your project folder.** Save all files to this folder.
    * If you were unable to produce a polygonal model, you can download the Airline Chair Model, and use it to complete the assignment.
 3. Follow the video demonstration to create UV maps to texture the [Kem Weber Airline Chair](https://collection.cooperhewitt.org/objects/404536651/images/).
 4. Apply the scale transform to reset each polygonal object.
 5. Unwrap the chair’s parts’ UVs using the various methods and tools described in the tutorials.
 6. Export a UV map for each part and save it in the project folder as **_uv-arm.jpg_**, **_uv-cushion.jpg_**_,_ etc.
 7. Import the UV maps into Photoshop and create textures to match the Airline Chair as closely as possible.
 8. Save the textures as **_arm_color.jpg_**, **_cushion1_color.jpg_**, etc. in the project folder. Name the files in an organized in a logical way.
 9. In Blender, set up the chair’s textures so they are visible on the model.
10. Save the 3D scene file as **_LASTNAME_-texturing-chair** in the project folder.
11. Compress the project folder once you’ve completed the tutorial and rename it **_LASTNAME_-texturing-chair.zip.**
12. Upload the .zip file to the assignment dropbox.
13. Double check that you've included all files and that your .zip file can be downloaded and opened.