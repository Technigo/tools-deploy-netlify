# Tools: How to deploy using Netlify

*This is a guide for how to use the tool ```Netlify``` .* 

## What is Netlify
Netlify is a tool that offers hosting for webpages and continuous deployment from Github. Meaning it provides your with a url and hosts your files on a webserver so that you and others can access them online. 

## When to use this tool
When deploying static websites using HTML, CSS and Javascript. When using React and Node.js Netlify will still be your tool but the approach will vary slightly. This will be used for every project submission for this course. 

## How to

### First time usage

✅Go to [Netlify](https://www.netlify.com/) and sign up. 

✅Choose to sign up using your Github account and give Netlify access to your Github. 

### Deploy a project

#### Prepare your project
Before you set up GitHub to deploy your site, make sure that your project is ready:

✅There should be an index.html file - this is what will load when you visit your website!

✅Make sure your stylesheets, images, and scripts use relative paths. Like this for a stylesheet, for example: `<link rel="stylesheet" href="./style.css">`

#### Deploy

✅When logged in to Netlify, click the button ```New site from Git```

✅In the first step you choose ```Github``` under the Continuous Deployment headline. 

✅Choose the repository that you would like to deploy. If you can't find the repository that you are looking for you might have to click the button `Configure Netlify on Github` 

✅Under Deploy settings you can choose which branch you would like to deploy. If you haven't made any specific production branch or similar, just go with ```master```. 

✅Click `Deploy site`. 

Wait a couple of minutes and your site will be deployed. Once fully deployed ***your site's url will show up on the overview page.*** This can for example be: https://infallible-hopper-12a82b.netlify.com. 

Everytime you push to the master branch Netlify will publish for you. This is called continuous deployment.  

## Alternatives

This is the tool that we will use during the bootcamp but there are many alternative services that can be good to know about. Some of the bigger ones for hosting is Github Pages, Amazon AWS, Heruoku, and the most known Swedish alternative is Loopia. 



