
  
# How to host a Resume with jekyll theme on GitHub Pages using MacOs.  
  
## Purpose  
  
Get job offers from employers by impressing them with my Resume.  
  
## Prerequisite  
  
-   [GitHub acount](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account)  
      
-   [Gem](https://sourabhbajaj.com/mac-setup/Ruby/RubyGems.html) installed  
      
-   [Homebrew](https://brew.sh/) installed  
      
-   [VSCode](https://formulae.brew.sh/cask/visual-studio-code) installed  
      
-   [Resume written in markdown](https://github.com/shahdipesh/resume/blob/master/README.md#more-resources)  
      
  
    
  
## **Part 1**: Creating resume using a template that uses jekyll theme.  
  
    
  
 **1. Install Ruby using Ruby Version Manager (RVM)**  
           
     
  
 - Open search using Cmd+space.  
 - Type terminal.  
 - Press enter, which will open a new terminal  window.  
 - Type `\curl -sSL https://get.rvm.io | bash -s stable --ruby` in the newly opened terminal.  
 - Press enter.  
     
      
 **2. Install Jekyll**  
    
  
      
  
 - Type `gem install jekyll in the terminal.   
 - Press enter.  
  
      
  **3. Download a Theme**  
 -  Select a theme you’d like to use for your resume by going to [Rubygems'](https://rubygems.org) site, which is a perfect place to find hundreds of themes to use for your markdown file along with some ready to use Projects, which can be modified as per your need.  
      
 -  Search for `Resume Jekyll` via the search box.  
      
  
   > Note: You can modify the words inside the quotes to search for  
   > different themes, but make sure the theme is compatible with Jekyll.  
   > One way to find if the theme is supported is to look for the word  
   > “Jekyll” in the subtext below the name of the theme.  
  
 -  Select any Jekyll theme you like from the result.  
      
 -  Click on the `HomePage` link on the right-side of the webpage.  
      
 -  Scroll down until you see the `“README”` section.   
 - Follow intructions on README to download the template  
 -  Open the project using Visual studio code (VSCode).  
-  Follow  instructions in README section of the project’s github repository to edit the files with details of the resume markdown file you had created.  
-  Save the files   
-  Check webpage to see the changes.  
      
  
**Now you have a digital Resume that is ready to be uploaded in github pages.**  
  
    
  
## Part 2: Uploading your Resume to github pages.  
  
 **1. **Setup GitHub Pages website.****
- Log in to your GitHub account and navigate to the main page.  
- In the top-right corner of the page, click the "+" icon, and then     
 select "New Repository".  
- Give your repository a name, and then click "Create Repository".  
- On the next page, click "Settings".  
- In the "GitHub Pages" section, select "Master Branch" from the     
      "Source" drop-down menu.  
- Click "Save".  
  
      
  
**2.  Edit your project settings so that it can be uploaded in github pages**
      
   - Open the _config.yml file and set url to [your_github_username].github.io  
            
   - Set the baseurl to /[name_of_the_repository] you created.  
      
  
> Note: Do not forget the “/” in the baseurl.  
  
 **3. Upload the project to your github repository**   
- Open a terminal in VSCode. Type `git init`   
- Press enter   
- Type `git remote add origin https://github.com/[your_github_username]/[your_repository_name].git`  
-  Press enter   
- Type `git add .`   
- Press enter.   
- Type `git commit -m “[any_message_you’d_like]”`   
- Press enter.   
- Type `git push -u origin main`   
-  Press enter.  
  
> Your GitHub Pages site will now be live at     
> http://[username].github.io/repositoryname, where "username" is your  
> GitHub username, and "repositoryname" is the name of your repository.  
  
> You may wonder why we use GitHub  to host our Resume. `Andrew Etter`, who is an expert in Technical Writing field suggests a few tips on how to write a good documentation in his book "Modern Technical Writing". Some of the tips are as follows:
> - **Use light Markup**
	There are many reasons to use markup to write documentation. First, markup can make your documentation more readable by adding structure to it. This structure can be used to automatically generate a table of contents, or to allow readers to quickly jump to the section they are interested in.  Second, markup can make your documentation more maintainable. If your documentation is stored in a markup format, then it is easy to automatically generate different versions of it (for example, a PDF version or a HTML version). This can save you a lot of time when you need to update your documentation.  Lastly, markup can make your documentation more accessible. If your documentation is written in a markup language, then it can be read by software that can help people with disabilities access it.
>- **Use Distributed Version Control**
	> There are many reasons to use version control, but the most important reason is that it allows multiple people to work on the same file simultaneously without having to worry about overwriting each other's changes.Similarly, Version control also makes it easy to roll back changes if something goes wrong.
>- **Make Static Webpage**
> There are many reasons to make a static web page. One reason is that static web pages load faster than dynamic pages. Static pages also require less server resources, which can save you money. Static pages are also more secure because they are not generated from a database.

> If you would like to know more details on writing a good documentation, you can find the book [here](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).
    
  
## More Resources  
  
-   [https://www.markdowntutorial.com](https://www.markdowntutorial.com) - Tutorial on how to create a markdown document.  
      
-   https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS  
  
-   at least one other resource  
      
  
## Authors and Acknowledgements  
  
-   [RyanxLoi](https://github.com/RyanxLoi)  
      
-   P1  
      
-   P2  
      
-   p3  
      
  
    
    
  
**FAQs**  
  
 - As we know Markdown is eventually converted to HTML so why not use  
   HTML directly?  
  
   -   The main aim of using markdown is to abstract away the complexity of formatting text in web documents so that author can focus on the content instead. HTML can perfectly format the contents of the webpage but it has a steep learning curve. Markdown is very easy to learn and hence anyone with just little effort can write content for the web.  
      
  
 - How do I know if a theme is compatible with Jekyll?  
  
      
  
   -   A simple trick is to read the subtext under the theme’s name on the webpage and look for any word that says “Jekyll”.  
      
  
-   I am getting an error when installing Ruby. What should I do?  
      
  
   -   There are different other ways to install Ruby on your mac and one way is by using homebrew. You can refer the instruction in this [page](https://jekyllrb.com/docs/installation/macos/) for further instruction.  
      
  
-   Clicking on homepage of the theme does not take me to github.  
      
     
   -   In such case, instructions on how to install and configure the project can usually be found in the homepage of the template itself.
