# Host Your First Resume Online
Follow alongside this readme if you want to host your resume online using Github Pages! We will be going over the practical steps needed to host a beautiful looking resume using a Jekyll template.

## Purpose
Applying Andrew Etter's Modern Technical Writing principles to host a resume online using GitHub Pages, Jekyll, Markdown & Visual Studio Code.
![Animated Resume Demo](https://github.com/sbinkader/sbinkader.github.io/blob/main/Resume%20Demo.gif)
[View Demo Resume](https://sbinkader.github.io/)
## Prerequisites
You will need these steps figured out before you can start following the rest of this guide:
* A GitHub Account
* If you do not have an account with Github already, head over to [GitHub](https://github.com/) to create one.
* Github Desktop Software
   * To work with the resume template, you will need Git version control system installed on your computer. Head over to [Github Desktop](https://desktop.github.com/) to download Github desktop for your specific operating system.
    * If you are having trouble getting started, this [documentation](https://docs.github.com/en/desktop/overview/getting-started-with-github-desktop) offers a great introduction to using Github Desktop.
* A Code Editor
    * While any basic code editor would do, we will be using Visual Studio Code. Go to their [website](https://code.visualstudio.com/download) to download the editor for your operating system.
    * If you having trouble installing VS Code, follow this [documentation](https://code.visualstudio.com/docs) for more information.
* A resume using Markdown
    * Even though we will be following a template, certain inputs will support markdown syntax if you want to add some additional information. Refer to [more resources](#moreResources) for a markdown tutorial.

## Step 1: Setting up your repository.
As Andrew Etter so eloquently explained in his book, everyone should be striving towards publishing their content to a website instead of creating content that are locally stored. Locally stored content are easy to forget about, and are often not updated or kept in sync. By only having an URL to your hosted site, anyone can view your most up-to-date resume unlike a PDF file that keeps getting out of date. For our purposes, we will be using Github pages to host your website.
To get started,
1.	Go to [GitHub](https://github.com/) and login to your account.
2.	Click on this [link](https://github.com/sbinkader/sbinkader.github.io/fork) to create a fork that is based on this repository.
    - This will automatically import all the files from the repository that we will be using as a template to build your own.
3.	Fill out Repository name in the following format: your Github username + .github.io. So for example, if your Github username is abc, then write ```abc.github.io``` as the repository name.
4.	Click on **Create fork** to complete your repository create process.
5.	You will be greeted with a page that looks like this:

![Repository Page](https://drive.google.com/uc?id=1p57N3kM4KVbcx7xJSvNqhbypZg2ephMB)

6.	Click on the **settings** button at the top middle of the page, and then select **Pages** from the left sidebar.
7.	Under the Build and deployment section, choose ```main``` for Branch and make sure that ```Deploy from a branch``` is selected for source.
8.	Press on **save**.
At this point you will have your repository fully set-up with automated build and deployment by Github pages with the template that you have forked.

## Step 2: Editing Resume Template using VS Code.
When it comes writing any document that needs to be maintained or have a decent lifespan, Andrew Etter recommends using a lightweight markup language like markdown. This is because lightweight markup languages makes content easier to read, write and maintain. Instead of restricting contributions by being difficult to access or learn, a lightweight markup language is very easy to learn, and is available everywhere. Even this Readme was written in markdown, and Github can automatically preview your markdown content. So to start editing our resume:

1.	Open Github Desktop and sign in to Github.
2.	Click on **File** in the top left corner and select **clone repository**.
3.	Select your repository that you have created earlier with your github username and the local path to your computer where you want to store the files.
4.	Click on the **clone** button and wait for the process to finish.
5.	Open the repository by pressing **Open in Visual Studio Code** from the main page.
    - Remember to not close GitHub Desktop yet, we will be using it later to publish our changes.
6.	From the left side bar of VS Code, open the ```_config.yml``` file.
    - At this point your visual studio code should look like the picture below

![Visual Studio Code Editor](https://drive.google.com/uc?id=1PrWAawkOORzCQUce6ImXxLB6i6D8iZAv)


7.	Now read through the file, and fill it out with your own resume contents.
	- Copy your profile picture into the images folder, and fill out ``` about_profile_image: images/yourimagefilename.jpg ``` to insert your photo.
	- Make sure that you are maintaining the indentation exactly as it is.
	- Sections that start with the **‘|’** symbol supports markdown syntax, so you can easily add in bullet lists and other components from your original resume created in markdown.
	- Most of your resume will go in the content section. Here, you can add or remove entire layout sections to add or remove entires as needed.

9.	Save the file by going to **File** on the top left corner and pressing **save**.

Your resume is now ready to be deployed in Github.

## Step 3: Publishing your resume online to Github.
At this stage, we will be publishing the resume online to Github, where it will be automatically built and deployed. In cases like these where you will be maintaining your hosted resume for long periods of time, keeping track of the changes through a distributed version control system becomes paramount. This is why Andrew Etter also recommended using these tools to maintain documentation workflows in his book. And since we are also hosting using Github too, changing and maintaining your resume is much easier. For these last few steps:

1.	Open GitHub Desktop
2.	Type a short description to the right of your user icon. For example, you could type "_Created Resume from Template_".
3.	Press **Commit to main** and wait for the process to finish.
4.	Finally, press the **Push Origin** button.

And that is it! You resume should be built and deployed in Github after a few minutes now. When the process has finished, you will be able to see your resume online at [yourusername.github.io]().


## <a name="moreResources"></a> More Resources
* Andrew Etter's book [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) to learn more about technical communication.
* A very good [Markdown tutorial](https://www.markdowntutorial.com/).
* Step by step [tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/) on how to build locally or create a site from scratch using Jekyll.
* Other [Jekyll Themes](http://jekyllthemes.org/) to discover what's possible with static site generators.

## Authors and Acknowledgements
* Author James grant for his [Moderm Resume Theme](https://github.com/sproogen/modern-resume-theme)
* AJ Manigque and Rizaldi Wijaya for peer reviewing this readme and resume.

## Frequently Asked Questions
### Can I setup custom domain names with GitHub Pages?
Yes, you can setup custom domain names for your sites hosted with Github Pages. The detailed process on how to do it can be found [here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).
### How do I change my template?
You can visit Jekyll's theme [website](http://jekyllthemes.org/) to browse existing collections, and then if you open a template that you like, you can press **Home** to get to the GitHub repository for that template. The README section of the repository will guide you on the exact process to changing your template. 

