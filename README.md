# Continuous Deployment

_In this assignment you will use GitHub Actions to implement a continuous deployment pipeline._

## Name three components of your solution

1. **SSH** - An important component was the proper application of the SSH key. It is important to put the SSH key in SECRET otherwise you are vulnerable. With the help of Github Secrets, this was easy to do.
2. **Github Actions** - With Github Actions, you can automate the entire workflow. Because there is already an example/template of what an .yml file should look like, the further writing of code was a bit easier to understand.
3. **Deploy script** - This script executes the commands, creates a secure login and takes care of the checkout of the repository. Everything is in one file so that it is all clear.

## Discuss three problems that you encountered along the way and how you solved them

1. Figuring out how all of this works. In my humble opinion there was very little documentation on how to do this.
2. In VS Code the Python version is by default 3.10.1. I had to change it to 3.9.6 otherwise Flask would not work. I also entered 3.9.6 in the requirements but this did not work. After changing it to 3.9 everything worked properly.
3. I had some difficulties with the SSH verification. I finally found the solution in Appleboy.

## Something of interest you would like to share about the process of solving this assignment.

It was a difficult assignment where finding the right solution wasn't always easy. I think this assignment could have been a lot better and more fun with just a bit more guidelines.
