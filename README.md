# Scene-Text-Editing

For my major project in my undergrad, I worked on building a deep learning network to edit texts in images. I got the inspiration for this project after I came across the STEFANN paper published in CVPR 2020. In my project, I worked on improving the style transfer model of STEFANN for the generated characters by performing image disentanglement. The original method mentioned in the paper worked only when the textual characters had a solid color pattern. By performing image disentanglement, I separated the character structure and colour features and used the colour features encoding for the newly generated character to maintain the original texture.

The details of the project are available [here](https://docs.google.com/presentation/d/1gOAya4HCmZUjAnMbdzHYI1wSVkv8dRazeDqnUcPMvkY/edit?usp=sharing)

## Original Architechture
![](https://github.com/TanmayKhot/Scene-Text-Editing/blob/main/images/STEFANN_architechture.png)

## Proposed Architechture
![](https://github.com/TanmayKhot/Scene-Text-Editing/blob/main/images/Image_disentanglement.png)
![](https://github.com/TanmayKhot/Scene-Text-Editing/blob/main/images/style_transfer.png)

## Output
![](https://github.com/TanmayKhot/Scene-Text-Editing/blob/main/images/output1.png)
<br><br><br>
![](https://github.com/TanmayKhot/Scene-Text-Editing/blob/main/images/output2.png)
<br><br><br>
![](https://github.com/TanmayKhot/Scene-Text-Editing/blob/main/images/output3.png)
