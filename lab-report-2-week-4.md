# Lab Report 2 Bugs
## Bug 1
Test Case:<img width="1222" alt="Screen Shot 2022-04-21 at 9 15 54 PM" src="https://user-images.githubusercontent.com/103221420/164599815-6be42d2f-5291-4e21-86fa-cee0404079c0.png">
[Link to failure-inducing input](https://kekoa-pickett.github.io/markdown-parser/test-file.md) <br>
Symptom:<br>
<img width="722" alt="Screen Shot 2022-04-21 at 3 32 03 PM" src="https://user-images.githubusercontent.com/103221420/164599979-d5785146-c642-49f8-ab61-f8107b489116.png">
The failure inducing input causes an issue because it doesn't have a parenthesis mark at the end of the link. This bug is a syntax error because the syntax of the closed parenthesis messes up the code and causes a symptom. The sympton is a index out of bounds error because the closed parenthesis value goes to -1 because of the syntax error of forgeting closed parenthesis.

## Bug 2
Test Case:<img width="1225" alt="Screen Shot 2022-04-21 at 9 22 39 PM" src="https://user-images.githubusercontent.com/103221420/164601591-f9e00d5d-8b9b-4fbb-b7ec-286e103bbbc3.png">
[Link to failure-inducing input](https://kekoa-pickett.github.io/markdown-parser/test2-file.md)<br>
Symptom :<br>
<img width="576" alt="Screen Shot 2022-04-21 at 9 27 41 PM" src="https://user-images.githubusercontent.com/103221420/164602971-f500d06b-26a7-4bb7-8a43-461a1cbd061c.png">
Here, the relationship is they all reflect or cause the other. The failing inducing input is a link with a empty line after it creates a bug because the code is looking at the line and indexes in it. The bug reflects the symptom because it isn't getting to the last index ever but there is always a extra line which is repeatedly searched and gives you a "heap space" error.


## Bug 3
Test Case:<img width="1223" alt="Screen Shot 2022-04-21 at 9 29 03 PM" src="https://user-images.githubusercontent.com/103221420/164603243-bbd7d032-ada9-4cf4-ac6f-3cf27d7aa3f7.png">
[Link to failure-inducing input](https://kekoa-pickett.github.io/markdown-parser/test3-file.md)<br>
Symptom:<br> <img width="693" alt="Screen Shot 2022-04-21 at 9 31 15 PM" src="https://user-images.githubusercontent.com/103221420/164603460-81d66931-e3a1-41e7-ab52-52dfc75bbbac.png">
This should just create a list with nothing but the symptom is a "index out of bounds" error. This relates to the failure inducing input and bug because the input that has no brackets or parenthesis is being looked for by the program and it returns -1 if it can't find it. This causes the index out of bounds symptom because of the bug that is targeted through the failure induced output.

## Solved Code
Didn't know if this was necessary but here is the solved code that fixes my bugs.
<img width="1230" alt="Screen Shot 2022-04-21 at 9 41 55 PM" src="https://user-images.githubusercontent.com/103221420/164604550-fb2ff10d-c02b-4aa4-8145-0f8eb587f604.png">
