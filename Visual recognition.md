# Visual recognition API

## Useful links 
- Download Batch Image Chrome Extension. [Link here](https://chrome.google.com/webstore/detail/batch-image-downloadfull/ahajhopfbfpekcljjjppolcmapaidldc?hl=en)
- AutoML Vision - Trainging imagine classifier. [Link here](https://www.youtube.com/watch?v=3342PeX1aNY)
- IBM Watson Studio - Training and testing models. [Link here](https://www.youtube.com/watch?v=KIw_iac56Hc)


## Reflection  

**Google Vision API**
- Pre-trained database is useful for recognising single item in a picture
- When trying on multiple items, it’s not as accurate as we expected. It shows as ‘food’ ‘package item’ ‘item’
- 50% accuracy for testing multiple items. It's not the tool we need for the app

**Google AutoML Vision**

- AutoML is another tool for training models based on the pictures we upload
- It takes longer time to train models compared to IBM Watson
- It works for single item recognition with high accuracy, but not for multiple items
- Free package limits: 40 node hours. We can only train up to 5-6 models for free 

**IBM Watson**
- We realised that what we need is training our own models to upload more real-life photos as database (different angles of an item/in slightly different package)
- 3 stage experiments:

| Experiments | Results |
| ------------ | ------- |
| Train 2 items | Turns out the accuracy isn’t that great. It recognises tomato but not really garlic |
| Train 5 items | Added 3 more items on the first trial. The accuracy is surprisingly great. It knows almost all the items in the clear-background images. It even recognises garlic (which was not working well on the previous experiment) |
| Train other 5 items | We wanted to test other items and see if it works for the photos we took. This time it didn’t work well when testing the pics from us. <see below> It recognised apple as orange, cannot recognise banana. The training models work well with the images from google(clear, clean background) only |

- Then we hit the free usage limit. What we’ll do next is to add more pictures for each categories including real life ones, so it recognises the objects as what we input. 

## Factors affecting recognition performance
- Pixel/Resolution
- The amount of images: It needs at least 100 pics for each category 
