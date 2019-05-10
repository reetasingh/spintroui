# spintroui

Excercise 1:

Clone the GitHub repo https://github.com/armory-training/spintroui
Create and push a new branch to the repo called “dev-${username}”
Create a pipeline in your ${username}UI application
- Pipeline should be called “Bake and Deploy”
- Add a GitHub trigger for your branch of the spintroui repo
Add a Wait stage to your pipeline
Add a Manual Judgement stage to your pipeline
● Provide the user with a custom prompt
Update the Readme with your username in your branch and git push;
Don’t forget to click Save!


Excercise 2:

Edit your original pipeline and add a “Deploy (Manifest)” to the end
● Use account “eks-ps-dev”
● For the text, copy this gist:
https://go.armory.io/training-gist-01
● Change “<USERNAME>” to your username
● Save your changes
● Trigger your pipeline by making another commit to your branch
