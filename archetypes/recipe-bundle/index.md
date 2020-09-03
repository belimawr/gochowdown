---
layout: recipe
date: {{ .Date }}
draft: true    
title:  "{{ replace .Name "-" " " | humanize | title }}" # The title of your awesome recipe
image: awesome-recipe-image.jpg # Name of image in recipe bundle
imagecredit: https://placekitten.com/600/800 # URL to image source page, website, or creator
category: # The type of meal or course your recipe is about. For example: "dinner", "entree", or "dessert".
cuisine: # The region associated with your recipe. For example, "French", Mediterranean", or "American".
tags: # You don't have to have 3, feel free to have 10, 1, or none
  - tag1
  - tag2
  - tag3 
yield: 8
prepTime: 15
cookTime: 45

ingredients:
- 1g of goodie

directions:
- do the thing
---