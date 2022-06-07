# Lab Report 5

I found my 2 bugs through using ```vimdiff``` on the results like suggested in the lab report. I compared both of them side by side and found two different bugs that had pretty big contrasts in answers and would be a big change. Then I looked at the md files to see if either implementation was correct.

## Part 1 (Test 488)
One different results test was test 488 which the .md file is [here](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/488.md) and the .html file is [here](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/488.html.test)

My implementation was correct because it included the correct link in the results whereas the cse one didn't have a link.
### Outputs
<img width="1113" alt="Screen Shot 2022-06-06 at 5 51 46 PM" src="https://user-images.githubusercontent.com/103221420/172272843-16d9dda4-f182-420b-8c12-b40c325e59f3.png">
### Listed Out Expected Output Links
```</my-uri>```
### As listed By Preview in VScode
<img width="777" alt="Screen Shot 2022-06-06 at 5 58 43 PM" src="https://user-images.githubusercontent.com/103221420/172273509-3e400b92-5ac2-47a4-9ccf-d71614c66fee.png">
### Incorrect Codes Bug
<img width="680" alt="Screen Shot 2022-06-06 at 6 40 53 PM" src="https://user-images.githubusercontent.com/103221420/172277609-ac4eea00-0c68-47ef-b9ce-8390a8425954.png">
The bug is where it checks for the index of a space. Since the link has a space between the ```my``` and ```url```, the highlighted part catches it and stops the link from being added. Taking this part out would fix it for this one test but I'm sure it would cause a lot more challenges.

## Part 2 (Test 567)
The other test with different results was test 567 which the .md test file is [here](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/567.md) and the .html file is [here](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/567.html.test).

Neither of the codes were correct. I added a link that was clearly not a link whereas cse15l code didn't add the correct link.
### Outputs
<img width="1119" alt="Screen Shot 2022-06-06 at 6 01 10 PM" src="https://user-images.githubusercontent.com/103221420/172273757-c8118cc0-abe3-4829-a560-a4880e910023.png">
### Listed Out Expected Output Links
``` /url1 ```
### As Found By VScode Preview
<img width="825" alt="Screen Shot 2022-06-06 at 7 03 55 PM" src="https://user-images.githubusercontent.com/103221420/172279952-eaaf4748-ba33-459b-8ff4-9837e62522f7.png">
### Incorrect Code Bug (CSE15L Parser)
<img width="665" alt="Screen Shot 2022-06-06 at 7 05 29 PM" src="https://user-images.githubusercontent.com/103221420/172280425-ff973d8a-eb03-49db-813b-d520752d0657.png">
Here, there code is looking for parenthesis when the link doesn't include any for the link to be added. So the if statement runs and ends the code without adding the not parenthesized link. This would be a hard fix because this is a new case that would mean a whole new checkpoint to create the loop.
### Incorrect Code Bug (My Parser)
<img width="627" alt="Screen Shot 2022-06-06 at 7 12 01 PM" src="https://user-images.githubusercontent.com/103221420/172281062-9050b49f-1982-465a-b039-38aa6a4555df.png">
For the same reason as the CSE15l parser I didn't add the new case because there were no parenthesis. As for the the added link is there because I didn't trim my code. As seen by what I highlighted, I added the link without checking for spaces that could make it a fake link.
