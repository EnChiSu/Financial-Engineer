# HW1 Lesson Learn:

1. "accumulation" can't be added up by accumulation itself.
The obstacle I faced is during the **step 5** (see **Section 2**) I try to compute the third column *(本金利息累計(元))* through adding up accumulation itself from the first period. However, the accumulation should be calculated by adding up each period's "total" return, not each period's "accumulative" return. To solve the problem I create a new variable to record each period's "total" return. Using that variable I can add up from the first period to calculate the "accumulative" return for each period.<br>
(我遇到的問題是，我在做第二個表格的第三欄*(本金利息累計(元))*時(參見**Section 2**的**Step 5**)，原本試圖透過該欄位每一期從第一期加總到該期，但這個邏輯是有問題的，因為累積應該是每期"總額"的加總，而非每期"累積"的加總(如果是用每期"累積"的加總這樣算，前面期數的總額會被重複加很多次)，所以後來我另外設一個變項紀錄每期還的"總額"，也就是該期的應還本金加上應還利息，再依期數疊加上去就可以得到每期以還的累積總額)
<br>

2. There are multiple ways you can input image into Jupyter Markdown.
For the image store in your local laptop, you can use (the image should be in the same file directory as your ipynb file):<br>
````<img src="YOUR_IMAGE_NAME.png"> ````<br>
However, when I upload the ipynb file to the Github, the image disappear. The solution I found is to create a file openning to the public in your Google Drive. Put the image into that file. Right click the image, and select "get sharable link".You will get a URL with id=YOUR_IMAGE_ID at last. Copy and paste that ID to the last part of this URL https://drive.google.com/uc?export=view&id=YOUR_IMAGE_ID. Then, use the code below:<br>
```` ![](https://drive.google.com/uc?export=view&id=YOUR_IMAGE_ID) ````<br>
(For more detail you can  read: https://elfsight.com/blog/2018/02/how-to-upload-images-for-direct-url-in-google-drive/ or https://stackoverflow.com/questions/52063556/add-image-to-github-readme-md-from-google-drive)

