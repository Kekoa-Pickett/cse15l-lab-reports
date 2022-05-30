# Lab Report 4
## My Repository Link [here](https://github.com/Kekoa-Pickett/markdown-parser)
## Reviewed Repository Link [here](https://github.com/ryankosta/good-markdown-parser)
## Expected Outputs
### Snippet 1 below
<img width="833" alt="Screen Shot 2022-05-29 at 9 41 18 PM" src="https://user-images.githubusercontent.com/103221420/170918408-7a19b24c-b5c1-449e-8fca-2ed408012b1e.png">
The snippet input is on the left with the expected result on the right. 

### Snippet 2 below
<img width="1145" alt="Screen Shot 2022-05-29 at 9 36 57 PM" src="https://user-images.githubusercontent.com/103221420/170918007-e523bb5a-d76e-4715-b192-ce06b9aaa164.png">
The snippet input is on the left with the expected result on the right.

### Snippet 3 below
The expected result is on the left with the snippet input on the right.
<img width="1096" alt="Screen Shot 2022-05-29 at 9 13 28 PM" src="https://user-images.githubusercontent.com/103221420/170915859-f342ecdc-5287-4ef0-b024-0ba41fb8d48d.png">
The expected result is on the left with the snippet input on the right.

## Reviewed Repository's MarkdownParseTest's
<img width="922" alt="Screen Shot 2022-05-26 at 10 29 42 PM" src="https://user-images.githubusercontent.com/103221420/170635657-e237fd57-56dc-4cfc-ada0-d86a670ab35f.png">
Using snippet 1-3, I created tests for each input to compare against the expected output.

## My Outputs
<img width="1017" alt="Screen Shot 2022-05-26 at 10 42 09 PM" src="https://user-images.githubusercontent.com/103221420/170637459-45cd1ece-1572-4422-9783-5978b8ef64e2.png">
My Markdown Parse failed all 3 tests by a lot.

## Reviewed Repository Outputs
<img width="1120" alt="Screen Shot 2022-05-26 at 10 04 39 PM" src="https://user-images.githubusercontent.com/103221420/170632943-c0a552b6-1b1c-4ec8-bdd9-a740ea08abde.png">
As you can see, their markdown parser failed all 3 tests.

## Are these easy fixes. (The number refers to the snippet #)
1. I think it is fixable with a few lines of code. I would just have to add a line that comments things out that are in between the backticks.
2. No, this would require more work because the code is told to stop at the first end parenthese but you would have to look for. The other issue is we can't look into the next link while searching for the last parenthese.
3. No, I need a lot of work for this one. I got the entire code which means I would have to go in and detail everything to switch what the code is looking for before it stops. This will definetly take more than 10 lines. 
