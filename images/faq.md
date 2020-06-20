# Frequently Asked Questions
# Most Important!
  - [How to ask and get your question answered - A MUST READ!](#q-how-to-ask-and-get-your-question-answered-a-must-read)
# Computer and Environment Setup
  - [What is a terminal and how do I open it?] 
  (#q-what-is-a-terminal-and-how-do-i-open-it)
  - [What is a command prompt? ] (#q-what-is-a-command-prompt)
  - [Why does `ls` not work in the terminal?] (#q-why-does-ls-not-work-in-the-terminal)
  - [What is meant by a ‘path’?] 
  (#q-what-is-meant-by-a-path)
  - [The terminal is saying that it cannot find the path I supplied, what is going on?] (#q-the-terminal-is-saying-that-it-cannot-find-the-path-i-supplied-what-is-going-on)
   - [I followed the instructions to setup my computer as presented in the video, but I am still having problems.  What could be wrong?] (#q-i-followed-the-instructions-to-setup-my-computer-as-presented-in-the-video-but-i-am-still-having-problems--what-could-be-wrong)
## Sublime Text, browser-sync, and Other Course Tools
  - [I am unable to install browser-sync] 
  (#q-i-am-unable-to-install-browser-sync)
  - [How do I use the Sublime Text HTML shortcuts demonstrated in the lecture videos?] (#q-how-do-i-use-the-sublime-text-html-shortcuts-demonstrated-in-the-lecture-videos)
  - [Sublime text is not auto-completing after I hit `ctrl+space`] (#q-sublime-text-is-not-auto-completing-after-i-press-ctrlspace)
  - [How do I edit multiple lines at the same time in Sublime Text?] (#q-how-do-i-edit-multiple-lines-at-the-same-time-in-sublime-text)
  - [What Sublime Text packages or extensions or plugins does Yaakov use in the Lecture videos?] (#q-what-sublime-text-packages-or-extensions-or-plugins-does-yaakov-use-in-the-lecture-videos)
  - [I’m making changes to my CSS and JavaScript and also running browser-sync, why aren’t my  changes showing up in the browser?] (#q-im-making-changes-to-my-css-and-javascript-and-also-running-browser-sync-why-arent-my-changes-showing-up-in-the-browser)
## Git
  - [I am unable to clone the github repo or upload my assignment] (#q-i-am-unable-to-clone-the-github-repo-or-upload-my-assignment)
  - [While typing in my password during an attempt to push files to GitHub, nothing is showing up while I type.  What is going on?] (#q-while-typing-in-my-password-during-an-attempt-to-push-files-to-github-nothing-is-showing-up-while-i-type--what-is-going-on)
  - [Why am I seeing “Please tell me who you are” when trying to commit to git?] (#q-why-am-i-seeing-please-tell-me-who-you-are-when-trying-to-commit-to-git)
   - [What GitHub URL do I use to access my site?] (#q-what-github-url-do-i-use-to-access-my-site)
  - [Where is the link to clone the repository on GitHub? The page looks different than what is shown in the video.] (#q-where-is-the-link-to-clone-the-repository-on-github-the-page-looks-different-than-what-is-shown-in-the-video)
  - [Where is the “Launch automatic page generator” button? The page looks different than what is shown in the video.] (#q-where-is-the-launch-automatic-page-generator-button-the-page-looks-different-than-what-is-shown-in-the-video)

## HTML, CSS, and JavaScript
  - [My CSS is not loading for my web page, what is wrong?] (#q--my-css-is-not-loading-for-my-web-page-what-is-wrong)
 Use the commands that the error message suggests to set this up one time. For ex
    [Bob@Coursera ~]$ git config --global user.name "Bob Sponge"
    [Bob@Coursera ~]$ git config --global user.email "bob.sponge@email.com"

#### **Q: What GitHub URL do I use to access my site?**
A: Before you can view your site on GitHub, your code (HTML, CSS, and JS files) as well as any supporting assets (images) need to be committed to the `gh-pages` branch in GitHub.  Once all resources are checked in, and assuming there are no errors on your page, you can visit your site by accessing a URL formatted as such:

http://yourgihubid.github.io/repository-name/module2-solution.

Be sure to replace 'yourgithubid' with your unique GitHub ID, and the repository-name with the one you chose to use for the project.  Similarly, module2-solution needs to be replaced with the folder in which your solution has been placed.


**NOTE:** If you commit to the master branch, your website will not be displayed and will get a "404 Page Not Found" error instead.

#### **Q: Where is the link to clone the repository on GitHub? The page looks different than what is shown in the video.**
A: Yes, GitHub has slightly changed their user interface since the video was recorded. Here is where you find that link now:
![GitHub clone link location] (images/GitHubCloneOrDownloadButton.png)

Click that green button and you'll have a choice to either download all of the code as a zip file or copy the link for cloning with git:
![Select cope of clone location] (images/GitHubCopyCloneLink.png)

#### **Q: Where is the “Launch automatic page generator” button? The page looks different than what is shown in the video.**
A: Yes, GitHub has changed the way how GitHub Pages are created. They now removed the "Launch automatic page generator" button. Instead, they allow you to host your pages in the branch of your choice.

This is what you will see when you go to the Settings page of your repo.
![GitHub Pages Settings] (images/GitHubPagesSettings.png)

To make things easier, you can host your code in the `master` branch, as opposed to the `gh-pages` branch used in the lecture video. To do this, use the **Select source** drop-down menu to select **master branch** as your GitHub Pages publishing source. Don't forget to click on the **Save** button.
![GitHub Pages Branch] (images/GitHubPagesMasterBranch.png)

Note that because GitHub now doesn't generate a template site for you, if you go to

http://yourgihubid.github.io/repository-name/ (replace 'yourgithubid' with your unique GitHub ID and 'repository-name' with the one you chose to use for the project)

you will get a 404 not-found error.

However, you can continue to follow the lecture to create a **site** folder (or whatever you wish to call it: **module2-solution**, **module3-solution**, etc.) inside your repo and place your code files in that folder. Then, you can access your repo using this URL:

http://yourgihubid.github.io/repository-name/site .

----------


### **HTML, CSS, and JavaScript**
#### **Q:  My CSS is not loading for my web page, what is wrong?**
A:  Be sure you have uploaded your .css files to your GitHub gh-pages branch and have placed them in the proper location.  The following example line in an HTML file will tell the browser where it can find the styles.css file.  In this case, it is saying that the styles.css file exists in the stylesheets folder.
    <link rel="stylesheet" type="text/css" href="stylesheets/styles.css">
So, in the location of your HTML files you must also have a stylesheets folder, and, inside of it, a styles.css file, in order for your browser to successfully load it.
#### **Q: I am using a responsive framework, but when I add the margins to the `div` elements, they flow beneath each other upon resizing the page. What am I doing wrong?**
A: One way to take care of this problem is to ensure the margins do not fight with the width.  To do this, create a dedicated `div` to hold the other `div` elements that make up your sections.  That is, be sure this dedicated `div` is not one of the the same `div` elements used for your sections. Essentially, this dedicated `div` will be responsible for controlling responsiveness while containing the `div`s for the sections within it.
Below is an example of some code, organized as explained above:
    <div class="row">
       <div class="col-lg-4 col-md-6">
          <div class="section">
             <h2 class="chicken">Chicken</h2>
             <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam, molestias, cumque! Odio illum quisquam sint porro exercitationem natus in consectetur blanditiis sunt, dolor aliquam magnam necessitatibus nobis mollitia quo obcaecati!</p>
          </div>
       </div>
    </div>
Notice how the `<div class="section">...</div>` are wrapped within the `<div class="col-lg-4 col-md-6">`, to which reactive columns and widths are applied.
At this point, be sure your CSS styles are applied to the correct divs to be sure you are styling the sections properly.
#### **Q: When viewing my page in tablet mode (narrower screen width), my 'nav' button does not work.  What is wrong?**
A: Be sure that you have included two necessary files in your HTML file BEFORE the inclusion of the Bootstrap JavaScript file.  The two files needed are jquery.js and jquery-ui.js, and Bootstrap depends upon functions defined inside of them, for it to work properly.
#### **Q: My hamburger button does not show up in the mobile view. Even though it shows up, when I click on it, the drop-down menu does not appear. What is wrong?**
A: There are a couple reasons for this.
First, make sure that you have included jQuery.js and bootstrap.js (or bootstrap.min.js) in your HTML file, *in order*. Also, make sure you actually have these two JavaScript files in your js directory and they are referenced correctly.
Second, jQuery 3.0+ is known as buggy when used with the bootstrap version we use in the lectures. You are advised to use the same jQuery version as that is used in the class (jquery-1.11.3.min.js or jquery-2.1.4.min.js). You can get a copy from any of the latter example code folders in the course repo. For example,
https://github.com/jhu-ep-coursera/fullstack-course4/tree/master/examples/Lecture29/after/js
Lastly, you have to use the `navbar-toggle` class right! This includes setting up `data-toggle` and `data-target` correctly. Refer to the related lectures for more info.
----------
### **Lectures and Course Content**
#### **Q: How do I upgrade to receive a certificate or specialization upon completion?**
A: In the menu on left-hand side of the course's Coursera page, [HTML, CSS, and Javascript for Web Developers](https://www.coursera.org/learn/html-css-javascript-for-web-developers/home/welcome) select "Course Info".  At the top right portion of the "Course Info" page, click the "Upgrade" button.  This will give the option to purchase the specialization track or this course's certificate track.
#### **Q: Where can I download the source code and lecture notes for the class?**
A: All course content can be retrieved from the course's git repository.  Run the following command at the command line:
`git clone https://github.com/jhu-ep-coursera/fullstack-course4.git`
#### **Q: In the lecture videos, Yaakov downloads and installs git version 2.6.3, do I need that exact version?**
A: We recommend any version of git equal to or greater than that which Yaakov uses.
So, git version 2.6.4 is fine (as well as anything newer).
#### **Q: Why are the lecture videos streaming in low quality?**
A: All course videos were recorded in HD (high definition) quality.
If you are experiencing poor video quality it is likely due to the limitations in speed of your internet provider or a slow network due to congestion.  Often, servers that host video content, like Coursera, will reduce the quality of the stream if a limited speed is detected.  This is to ensure that the video can still be watched while not making the viewer wait for large amounts of data to load on a slower connection.
You can try manually adjusting the quality yourself by clicking on the gear icon attached to the control panel of the video.  Further, videos can be downloaded and watched later, so you do not have to wait for a stream.
#### **Q: My quiz is not graded correctly! or Graded quiz shows wrong answer as correct answer!**
A: Since at this point all the quizzes in the course have been taken by thousands of students, it's unlikely that there is actually something wrong with the quiz in question. It's much more likely that you either didn't answer the questions correctly. EVEN MORE likely is that you misunderstood the way Coursera presents correct answers to you. This happens all the the time and is due to the confusing way Coursera marks answers as correct or incorrect.
For example, if there is a multiple choice question, Coursera will mark an unchecked answer CORRECT RESPONSE if that answer was NOT supposed to be chosen:
![Correct Quiz Response Screenshot](images/CorrectQuizResponse.png)
Note how Coursera marked the first answer, which was NOT selected by the student. It was marked CORRECT RESPONSE. What it means to communicate is that your LACK OF RESPONSE was correct on that answer.
On the other hand, if you don't select an answer that's supposed to be selected, it will mark it as INCORRECT RESPONSE, i.e., your LACK OF RESPONSE on that answer was incorrect. For example:
![Incorrect Quiz Response Screenshot](images/IncorrectQuizResponse.png)
Lastly, **if you still think that's something is wrong with the quiz** or you don't understand why it's failing you, please try to take a screenshot of the your GRADED quiz and post it to the corresponding Week forum, asking your fellow students for help.
#### **Q: I am getting `XMLHttpRequest cannot load file:///somepath` error. What am I doing wrong?
A: `XMLHttpRequest` signifies an Ajax request that your code is attempting to make through the browser. Most, if not all, browsers do **not** support Ajax requests made through the `file` protocol, which is what `file:///somepath` specifies. Instead, the browser expects an HTTP protocol, which looks like `http://somepath`.
In order for your Ajax request to work you need to serve your web site to the browser through a server. You can deploy it on GitHub as explained in Module 1 to solve the issue. However, the **easiest** way of having a server while your are developing is to get a local one on your machine. This is why we are pretty much always using Browser Sync.
Browser Sync, among other things, provides a local server option. So, simply navigate to the root directory of your web site on your machine (either through terminal program on Mac/Linux or through CMD program on Windows) and execute the following command:
    browser-sync start --server --directory --files "**/*"
Of course, this assumes you installed browser-sync as was instructed in Module 1.