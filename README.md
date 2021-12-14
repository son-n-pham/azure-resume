# build-resume-in-azure
Follow video project from ACG

Diagram

![image](https://user-images.githubusercontent.com/79841341/145048139-687b4225-4c28-468d-95ff-a25801bdb6ce.png)

Prerequisites:

![image](https://user-images.githubusercontent.com/79841341/145048214-75ff8a23-1341-40d3-a69f-acfc764778e1.png)

## Section 1: Building Frontend

![image](https://user-images.githubusercontent.com/79841341/145063042-0d6ff26e-eba9-48d9-b6b1-b5c1eff44c0b.png)

I used ssh git clone to clone this repo to my local machine. For cloning, I need to add ssh keys to GitHub account. Here is the steps that I follow.

https://www.inmotionhosting.com/support/server/ssh/how-to-add-ssh-keys-to-your-github-account/

After cloning my GitHub repo, I cloned the azure resume resouces from ACG repo from the below link.

https://github.com/ACloudGuru-Resources/acg-project-azure-resume-starter

Then I went to the local machine's VS code to modify index.html to update the resume, then create main.js for counting the visit. Finally, git add, git commit then git push to update all the changes in the local device to this GitHub repo.

- front-end folder contains the website
- main.js contains visitor counter code

## Section 2: Building Backend

![image](https://user-images.githubusercontent.com/79841341/145063159-4d97ca3b-5cb0-4e28-80ea-94fde3fe3f98.png)

When setting Cosmos DB resources, we selected the capacity mode of serverless because it can save cost and we do not need it to be on all the time.

![image](https://user-images.githubusercontent.com/79841341/145064876-12af2c85-3108-4c42-8796-879303f9b61e.png)
