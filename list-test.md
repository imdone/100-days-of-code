---
computed:
  date: (new Date()).toDateString()
  time: (new Date()).toLocaleTimeString()
  timestamp: (new Date()).toISOString()
template: | # This is the template for new cards that are created in imdone
  
  <!-- created:${timestamp} -->
  <!--[ Created: {{(new Date(created)).toLocaleString()}} ]-->
links:
  - pack: fab # Can be fab or fas https://fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use
    icon: fa-twitter # The font-awesome icon to use
    title: Tweet this card
    href: https://twitter.com/intent/tweet?text=${encodedText}%0ATweeted%20with%20@imdoneio
---

# [list test](#DOING:10)
a
b
c
   1. one
      1. a
2. b
3. two
   1. three   
   2. four
----
four
<!-- created:2020-04-11T03:38:46.183Z -->
<!--[ Created: {{(new Date(created)).toLocaleString()}} ]-->

