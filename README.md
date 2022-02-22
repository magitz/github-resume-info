# GitHub For your Job Search

 > Using GitHub.com to host your résumé and profile for free!

![UFIT 2022 Tech Fair header image](images/TechFair2022.png)

This site has been created to provide information on hosting your résumé online for free using [GitHub.com](https://github.com/) and [GitHub Pages](https://pages.github.com/) using free résumé templates. Especially if you use GitHub to share code, I also cover setting up your [GitHub profile](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/about-your-profile).

----

## What is GitHub?
[Github.com](https://github.com/) is the leading site for building, delivering, and maintaining code. Using the industry standard [git](https://git-scm.com/) technology, GitHub.com provides an online resource for version control and hosting your portfolios. GitHub also provides GitHub Pages as a way of hosting free websites! 

## GitHub Profile Page

Your profile page is what is displayed when someone navigates to your username on github.com. For example, here's mine: https://github.com/magitz

To create your profile page, create a git repository with the same name as your username. The README.md file in that repository is your profile page. Use Markdown to add content and format the page.

Checkout the [GitHub Documentation on Profile pages](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/about-your-profile).

> Note: If you want to have both a profile page and a website at your username.github.io, just publish your web content from the gh-pages branch of your repository!

----

## GitHub Pages: ✨Free🌟 website hosting!

Any GitHub repositroy can have an associated website. This can either be on the main branch, or a branch dedicated to the web content.

## Guides to creating your GitHub Pages site

* [Host your resume on Github pages](https://dev.to/joojodontoh/host-your-resume-on-github-pages-514g) by Joojo Dontoh
  * Has a good walkthrough and links to some nice Bootstrap-based themes.
* [Creating a digital CV in Markdown on GitHub](https://workwithcarolyn.com/blog/digital-cv-guide) by Carolyn Stransky
  * A clear step-by-step buid using the built-in Minimal theme.

## Sites with GitHub résumé templates

Site | Framework (see [below](#Frameworks-for-hosting-on-GitHub)) | Sample
-----|--------------|--------
[sproogen/modern-resume-theme](https://github.com/sproogen/modern-resume-theme) | Jekyll and YAML | [![Link ot image of Modern Resume Theme example](https://github.com/sproogen/modern-resume-theme/raw/master/screenshot.png)](https://sproogen.github.io/modern-resume-theme/)
[Postcards](https://github.com/seankross/postcards) | R and R-Markdown | Several formats available <br>[![Link to image of Trestles resume example](https://github.com/seankross/postcards/raw/main/man/figures/trestles-preview.png)](https://seankross.com/postcards-templates/trestles/)
[jglovier/resume-template](https://github.com/jglovier/resume-template) | Jekyll and HTML | [![Link to image of resume template example](https://github.com/jglovier/resume-template/raw/gh-pages/images/screenshot.png)](http://resume-template.joelglovier.com/)
[Simple Resume](https://themes.gohugo.io/themes/simple-resume/) | Hugo | [![Link to Simple Resume example](https://d33wubrfki0l68.cloudfront.net/3cc53bd01ca9a31241b4722c51ae7c796802b718/b32a9/themes/simple-resume/screenshot_hu845549e4047127913d9ef4f2c6784c78_110624_750x500_fill_catmullrom_top_3.png)](https://focused-varahamihira-bdb0c9.netlify.app/) (example hosted using [Netlify](https://www.netlify.com/), another option)
[Vitae](https://github.com/mitchelloharawild/vitae) | R and R Markdown | Many options available, here's one <br> [![Link to one of many Vitae examples](https://github.com/mitchelloharawild/vitae/raw/master/man/figures/preview-awesomecv.png)](https://pkg.mitchelloharawild.com/vitae/reference/awesomecv.html) 
The [Jekyll Themes site has a résumé tag](https://jekyllthemes.dev/tag/resume/) | Jekyll | Many options


## Frameworks for hosting on GitHub

GitHub Pages essentially uses static HTML to serve your site and most any [static site generator](https://www.google.com/search?q=static+site+generator) will likely work. I'm listing a few options, for your résumé, keep it simple, but if you want to explore other options for GitHub Pages, know that there are many!
* [Jekyll](https://jekyllrb.com/) is the "official" GitHub framework and is the best documented/most common option
  * [Setup guide for GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)
* [Hugo](https://gohugo.io/) is also popular
  * [Setup guide for GitHub](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
* R and RStudio using R Markdown is popular for R users
  * [Setup guide for GitHub](https://resources.github.com/whitepapers/github-and-rstudio/)
