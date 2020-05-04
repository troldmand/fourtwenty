# fourtwenty
A quick imgur-like dropzone for growers, to upload images of plants for easy sharing 

## MVP 
A lot of home-growers upload plant pics on imgur, then share it on forums and asks for advice. On reddit, subreddit moderators are creating reminder-bots, to ask for a long list of details, that they always require to be able to give proper feedback. 

So the _minimal viable product_ is a beautiful drop-zone and uploader, asks the uploader for various details about which soil, what growing medium, what kind of lights (if any), etc. 

A minimalistic way of doing advanced queries should be thought in, and proto-typed in the MVP. 

The _most awesome version_, of course includes auto-detection of common problems like blurple LED-grow-lights obscuring the hue, great nudging towards a general photo /angle /zoom convention, suggested comparable queries and a lot of AI. 

Also on the future wish-list:
- Comment sections on each album and individual image,
- Authentification, especially to develop email journeys, where we ask for progress and 'how did it turn out',
- A collaborative identification and photo-collaging of diseases and symptom identifications,
- A secure and anonymous transaction, where privacy is activaly ensured and not 'hoped for'. 

## milestones for the MVP
__1. Dropzone for images__

1.1 A minimalistic dropzone, triggering upload progress visualization and a 'typeform'-ish questionaire to fill out along the upload experience. 

1.2 A hosting scheme with auto-compression (like tinyjpg.com)

1.3 A db scheme, fit for scaling up to some intense AI shit. Maybe it shouldn't be in the MVP, but we have to think highly of the requirement for the db, to self-regulate, correct and grow, AI-powered-community-super-computer-style. 

___Example of use-case__. [Purple grow light images](https://www.google.com/search?q=purple++grow+light+led+images+of+plants&tbm=isch&ved=2ahUKEwjNtdnY_prpAhWOD-wKHd-2BVwQ2-cCegQIABAA&oq=purple++grow+light+led+images+of+plants&gs_lcp=CgNpbWcQA1CHGljgMmCmOGgDcAB4AIABWIgBvwqSAQIxOZgBAKABAaoBC2d3cy13aXotaW1n&sclient=img&ei=SHOwXs3xI46fsAff7ZbgBQ&bih=843&biw=1680) obscur the color of the plants and makes it really difficult to see nutrient-related problems and general health. So how do we build a database, that is the best foundation for collaborative learning about situations like this? Basically, we want a database (and application writing to the database), that is flexible, experimental and aggregative. A few years from now, someone uploads an image, and instantly, the software detects the purple lights and asks for different images. This is possible, because the database isn't thought in as a dump for files, but as a community-regulated, AI-powered data aggregation and categorization tool._

__2. Query-able user interface__

2.1 A full-screen search with auto-completion and auto-rendering of suggested albums and images. 

2.2 A simple hello-world version of image-search; query the db by snapping an image of your own and get plants of similar size. 

2.3 Advanced search functionality; search through all the parameters and include them in a satisfying UI, making me feel like I'm in some kind of plant-iron man. A plantronman. 

![iron man future](https://www.meme-arsenal.com/memes/623e2472f3bcd1a769c08842b00d4c5a.jpg). 
