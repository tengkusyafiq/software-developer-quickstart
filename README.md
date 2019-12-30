---


---

<h1 id="software-developer-quickstart">Software Developer Quickstart</h1>
<h2 id="workspace-setup">Workspace Setup</h2>
<p>As an app developer here, things that needs to be set up are explained below.</p>
<h3 id="slack-and-telegram--collaboration-hubs">Slack and Telegram : Collaboration hubs</h3>
<p>Software team are usually changing information using Slack app most of the time.<br>
You can install Slack here: <a href="http://slack.com/downloads/windows">slack.com/downloads/windows</a><br>
After registering with your email, go to your team’s workspace. Slack is a paid service (free service has limited features), so the alternative is might be Telegram.</p>
<p>Download and install Telegram: <a href="https://desktop.telegram.org/">desktop.telegram.org/</a></p>
<h3 id="postman--api-testing">Postman : API Testing</h3>
<p>As an app developer, firstly you should learn what is API, how it works, and how to use it.</p>
<p>In short, API is what connect the front-end to the back-end. For example, front-end(mobile app for example) ask for a user details data via an API request from the back-end(contains all users database). The back-end then response with a JSON format of data about the specific user asked before.</p>
<p>You can learn more with your own research.</p>
<p>Download and install Postman: <a href="https://www.getpostman.com/downloads/">https://www.getpostman.com/downloads/</a><br>
Postman is used to test the API that we will use when developing our project.<br>
In app development, both front-end and back-end developers need to work with each other.<br>
After back-end developer creates an API, he will test the API with Postman to make sure it responses a right result. If everything is okay, he will pass the API endpoint for front-end developer to use. He also does the same thing with Postman to see what kind of data structure needs to be extracted from the API to be displayed in the front-end.</p>
<p>Learn more:<br>
<a href="https://dev.to/loopdelicious/using-jwt-to-authenticate-and-authorize-requests-in-postman-3a5h">https://dev.to/loopdelicious/using-jwt-to-authenticate-and-authorize-requests-in-postman-3a5h</a></p>
<h3 id="vscode--source-code-editor">VSCode : Source-code editor</h3>
<p>Note that you can always use other source-code or text editor if you want.<br>
We will be using this editor so that we can use Git efficiently later.</p>
<h4 id="installation">Installation</h4>
<p><a href="https://code.visualstudio.com/download">https://code.visualstudio.com/download</a></p>
<h4 id="setup-coding-environment">Setup coding environment</h4>
<p>General extensions to install in VSCode for increasing efficiency as a developer are listed below. Please search the identifier below in the extension tab, READ what does it do, and install.</p>
<ul>
<li>formulahendry.auto-rename-tag<br>
auto-rename html tag</li>
<li>alefragnani.bookmarks<br>
Some file type such as Elm file can’t use built-in bookmarker. With this extension, <code>&lt;ctrl&gt;&lt;alt&gt;&lt;K&gt;</code> to bookmark/unbookmark. <code>&lt;ctrl&gt;&lt;alt&gt;&lt;J&gt;</code>or <code>&lt;ctrl&gt;&lt;alt&gt;&lt;L&gt;</code>to jump to another bookmark.</li>
<li>coenraads.bracket-pair-colorizer</li>
<li>streetsidesoftware.code-spell-checker</li>
<li>naumovs.color-highlight</li>
<li>pranaygp.vscode-css-peek</li>
<li>msjsdiag.debugger-for-chrome</li>
<li>sbrink.elm</li>
<li>dsznajder.es7-react-js-snippets</li>
<li>dbaeumer.vscode-eslint</li>
<li>donjayamanne.githistory<br>
to see the git history and branches visually.</li>
<li>eamodio.gitlens<br>
to do more with git, such as see all of the differences visually between two branches.</li>
<li>xabikos.javascriptsnippets</li>
<li>esbenp.prettier-vscode</li>
<li>msjsdiag.vscode-react-native</li>
<li>shan.code-settings-sync<br>
if you want to sync all of vscode setting, including extensions across multiple devices.</li>
<li>burkeholland.simple-react-snippets</li>
<li>wayou.vscode-todo-highlight</li>
<li>visualstudioexptteam.vscodeintellicode</li>
<li>lihui.vs-color-picker</li>
</ul>
<h4 id="vscode-most-used-tips-and-tricks-as-a-developer">VSCode most used tips and tricks as a developer</h4>
<p><code>&lt;ctrl&gt;&lt;K&gt;</code>+<code>&lt;C&gt;</code> : comment<br>
<code>&lt;ctrl&gt;&lt;K&gt;</code>+<code>&lt;U&gt;</code> : uncomment<br>
<code>&lt;ctrl&gt;&lt;D&gt;</code>multiple times to find and edit same words.<br>
<code>&lt;ctrl&gt;&lt;shift&gt;&lt;F&gt;</code> : global search<br>
<code>&lt;ctrl&gt;&lt;P&gt;</code> : search filename and open<br>
<code>&lt;ctrl&gt;&lt;`&gt;</code> : open terminal</p>
<ul>
<li>Use Git History extension (top right area, git history icon) to explore all of the commit historically.</li>
<li>Use GitLens to compare lot of things.</li>
<li>Use Source Control tab or <code>&lt;ctrl&gt;&lt;shift&gt;&lt;G&gt;</code> to pull, commit, push, checkout etc.</li>
</ul>
<h3 id="git--version-control">Git : Version control</h3>
<p>We use git when developing our code, so that we can save a ‘snapshot’ of all of the files in our project, at once, in a certain time. By doing this, we can refer back to the snapshot any time.</p>
<p>Learn more here:<br>
<a href="https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2019/05/API-2-768x262.png">https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2019/05/API-2-768x262.png</a></p>
<p>Download and install: <a href="https://git-scm.com/downloads">git-scm.com/downloads</a></p>
<ul>
<li>Git is a version control system.</li>
<li>You can work locally, but can also use remotely via internet.</li>
<li>Commit: works like taking a ‘screenshot’ of your files.</li>
<li>You can always revert back to the previous version if you need to.</li>
</ul>
<h4 id="setting-up-gitlab-key-on-a-new-computer">Setting up Gitlab key on a new computer</h4>
<p>This needs to be done so that every time you use Git on a new computer, so you will be recognized on a new computer.</p>
<ul>
<li>Open Git bash</li>
<li><code>ssh-keygen -t ed25519 -C "&lt;your gitlab email&gt;"</code></li>
<li>Press enter until finished.</li>
<li>Find the generated .pub file, open it.</li>
<li>In <a href="http://gitlab.com">gitlab.com</a> &gt; setting &gt; ssh &gt; paste your public key in key field(without email).</li>
<li><code>ssh -T git@gitlab.com</code> &gt; if it says welcome, then ok!</li>
<li>Now you can clone push pull etc. as yourself in the new computer.</li>
</ul>
<h4 id="commonly-used-commands">Commonly used commands</h4>
<ul>
<li>git init: initialize local git repository. you do this in a folder that you want to make as a git repo, that’s your project folder.</li>
<li>git add : add file to the index</li>
<li>git status: check status of working tree</li>
<li>git commit: to commit changes in index</li>
<li>git push: to push to remote repo, in internet, you need an authorization</li>
<li>git pull: pull latest from remote repo</li>
<li>git clone: download repo</li>
</ul>
<h4 id="how-to-make-a-new-repository">How to make a new repository</h4>
<ul>
<li>open cmd or git bash in the working folder</li>
<li><code>git init</code></li>
<li><code>git config --global user.name '&lt;your name&gt;'</code></li>
<li><code>git config --global user.email '&lt;your email&gt;'</code></li>
<li><code>git add &lt;file name you want to add to the repo, with extension too&gt;</code></li>
<li>to add all files at once, use: <code>git add .</code></li>
<li>to ignore files or folder in the folder, files that you dont wanna put in the repo:<br>
make a new file named .gitignore in the working folder<br>
list the filename.extension or /folder in the .gitignore file</li>
<li><code>git status</code> to see the status of the repo</li>
</ul>
<h4 id="how-to-commit-the-changes">How to commit the changes</h4>
<p><code>git add .</code><br>
<code>git commit -m '&lt;your comment about this commit&gt;'</code></p>
<h4 id="good-habit">Good habit</h4>
<p>You don’t want to commit everything in master branch(see the branch name in <code>git status</code>).<br>
instead, create new branch to commit every important changes before finalize into master branch:</p>
<ul>
<li><code>git branch &lt;branch name&gt;</code><br>
then to go into another branch:</li>
<li><code>git checkout &lt;name of branch you want to get into&gt;</code><br>
now, note that if you’re working in develop branch for example, you don’t change anything from the master branch.<br>
so, if you’re ready to merge the develop into master branch:</li>
<li><code>git merge &lt;branch you wanna merge into master&gt;</code><br>
it will open a text editor in terminal, press ‘i’ to type then type the commit message to save, press and type: <code>&lt;esc&gt;:wq&lt;enter&gt;</code></li>
</ul>
<h4 id="working-with-remote-repository">Working with remote repository</h4>
<p>to see the remote repo of the current local repo:</p>
<ul>
<li><code>git remote</code><br>
it will show you the git link if it has one.</li>
</ul>
<h4 id="push-to-remote-repository">Push to remote repository</h4>
<ul>
<li>Let say you make new files, changes, and commit etc, now you want to ‘update’ the remote repo:</li>
<li><code>git push</code></li>
<li>and the remote repo will be the same as local repo</li>
<li>IF no, know the url (bla3.git) of the remote repo.  or you can create a new one on github.</li>
<li>then on the local repo, set the remote repo location: <code>git remote add origin &lt;remote git link eg: https://github.com/........./asfsafa.git&gt;</code></li>
<li>push for the first time will upload local repo into the remote repo to master branch: <code>git push -u origin master</code></li>
<li>or to push all of them: <code>git push origin --all</code></li>
<li>when login page popup, login.</li>
<li>now everythings is uploaded.</li>
</ul>
<h3 id="freshrelease--agile-project-management-software">Freshrelease : Agile project management software</h3>
<p>We use this to help us use scrum in our project.</p>
<p>Register a freshrelease account and ask anyone to have permission into project you will be assign into.<br>
Later, we will go through how to use this management tool when working on a project, in project management framework topic.</p>
<h3 id="zoom--video-meeting">Zoom : Video meeting</h3>
<p>Download and install: <a href="https://zoom.us/download">zoom.us/download</a><br>
We can use this software whenever we have meetings remotely.</p>
<h2 id="our-agile-project-management-framework">Our agile project management framework</h2>
<h3 id="scrum-introduction">Scrum introduction</h3>
<p>Scrum is one of the popular agile project management framework. By using scrum, we could see and track the project progress clearly. We can also inspect all developers’ tasks regularly. We can adapt our workflow whenever we need to.</p>
<ul>
<li>Product owner: Identifying product features (epics), translating these into a prioritized list, deciding which should be at the top of the list for the next sprint and continually re-prioritizing and refining the list. In the beginning of the project, product owner will put all of the major features into Freshrelease.</li>
<li>Scrum master: Make sure the scrum practices work smoothly, such as daily stand-up meeting and sprint review.</li>
<li>Development Team: Build the product. Each team members decides how many items to build in a sprint.</li>
</ul>
<p>References:<br>
<a href="https://www.visual-paradigm.com/scrum/what-are-the-three-scrum-roles/">https://www.visual-paradigm.com/scrum/what-are-the-three-scrum-roles/</a></p>
<h3 id="the-way-we-use-scrum">The way we use scrum</h3>
<h4 id="for-starting-a-project">For starting a project</h4>
<ol>
<li>Product owner gets all of the epics from clients.</li>
<li>Product owner writes Product Requirement as a single source of truth.</li>
<li>Product owner breaks down all of the major features into Epics(Major features), Stories(sub-features), Task/Sub-Task(tasks that make up features) and put it into Freshrelease.</li>
<li>The stories need to be written with details in the <code>info</code> form like below:<br>
<code>As a &lt;end-user or any party&gt;, I need to have &lt;feature&gt; so that &lt;the result&gt;</code></li>
<li>For breaking down Sub-task (down to back-end, mobile app, or web app parts), Product Owner needs to discuss with the development team. By doing this, each developers can identify what the story need in back-end, mobile app, and web app parts.</li>
<li>Now that the backlog is ready to be used. The backlog later will be maintained together (originally it’s Product Owner responsibility) whenever there is a new features, bugs or tasks. To avoid duplicate tasks, it’s better to assign the new task to someone immediately after it’s being created. With this, assigned developer will know if he’s assigned with the same tasks.</li>
</ol>
<h4 id="for-ongoing-project">For ongoing project</h4>
<h5 id="daily-stand-up-meeting">Daily stand-up meeting</h5>
<p>Everyday before 10:00 AM, you need to update these 3 things in the stand-up channel in Slack:</p>
<ol>
<li>What did you do previously?</li>
<li>What will you do today?</li>
<li>Anything blocking your progress?</li>
</ol>
<h5 id="meeting">Meeting</h5>
<p>We do this whenever we have some update to the team about the project, such as explanation of any features. These meetings are <strong>critical</strong> to be held, to make sure all of the team members receive new information and are on the same page, <strong>whenever</strong> there are misunderstanding of a feature, or there is a new feature.</p>
<h5 id="code-review">Code review</h5>
<p>Once a week, you should set a date and time to do a code review with the person who is responsible to review your code. Commonly, most of the developers set the review presentation on Friday before sprint review and meeting, but you can set on any other day if it’s busy.<br>
During the code review, you may use the projector to show the codes you have written so far on your laptop. Show the demo of what you have done. For mobile app, you can show the demo on your smartphone. Use iProjection app or any compatible app for android, to show the app on the projector.<br>
Make sure everything is ready for review. Make sure you take note of all of the comments given. At the end of the review, usually you will get new additional tasks. If the review is okay, you can drag the reviewed task from Pending Review to Done. Don’t forget  to put the new additional tasks into the Freshrelease backlog to be done in the next sprint.</p>
<h5 id="sprint-review-and-sprint-planning">Sprint review and sprint planning</h5>
<p>Since our sprint period is usually one week, both of this usually are held every Friday, one after another.</p>
<h6 id="sprint-review">Sprint review</h6>
<p>You tell the team briefly what you have done, and not done throughout the sprint. Product owner complete the sprint and start a new one.</p>
<h6 id="sprint-planning">Sprint planning</h6>
<p>We discuss the next sprint goals, re-highlight what to prioritize, and the due.<br>
Everyone assigns new tasks (or unfinished tasks from previous sprint) and put the time estimation (points) to complete each tasks like below. In Freshrelease, use <code>Effort in days</code> form.<br>
Time points:</p>
<ul>
<li><strong>1</strong>: 1-2 hours</li>
<li><strong>2</strong>: Half day</li>
<li><strong>3</strong>: One day + half, if needed</li>
<li><strong>5</strong>: 2-3 days</li>
<li><strong>6</strong>: 5 working days</li>
<li><strong>8</strong>: 9 working days</li>
<li><strong>11</strong>: Too long, need to be broken into smaller tasks</li>
</ul>
<p>New stories need to be written with details in the <code>info</code> form like below:<br>
<code>As a &lt;end-user or any party&gt;, I need to have &lt;feature&gt; so that &lt;the result&gt;</code>. For writing new technical tasks or bugs, you also need to write it in details.</p>
<h3 id="common-situations-you-might-face">Common situations you might face</h3>
<h4 id="stuck-on-a-problem-for-too-long">Stuck on a problem for too long</h4>
<p>In case of you stuck in a task for more than time allocated, you have to notify the team so that everyone can help. Highlight the problem in stand-up meeting in the Slack channel. You also can ask team members in the project’s main channel in Slack. If there is no other way, skip to the next task.</p>
<h4 id="dont-understand-a-feature-well">Don’t understand a feature well</h4>
<p>In case of you don’t understand how a feature works, you can re-read the Product Requirement document of the project. If there is nothing explained about it, you should ask the team members about it. This is to reduce misunderstanding of the project between each other. A meeting should be held immediately if the Product Requirement did not cover the feature well.</p>
<h4 id="task-is-blocked-by-other-developers-task">Task is blocked by other developer’s task</h4>
<p>Sometimes your task needs other task to be done first. For example, as a front-end developer, you can’t make sure whether your code is working or not since the task about the API needed is not finished yet.<br>
Drag your task into Pending Review &gt; Blocked in Freshrelease, and inform other developers in the channel.</p>
<h3 id="retrospective">Retrospective</h3>
<p>To make sure we can improve our current project management framework and dev-ops continuously, we have #retrospective channel in Slack for anyone to raise problem or issues that slows down our productivity. From that, we can confirm and vote for a solution.</p>
<h2 id="catching-up-with-ongoing-projects">Catching up with ongoing projects</h2>
<ol>
<li>Get briefing with the Product Owner.</li>
<li>Read the Product Requirement. Know every features, what the clients want. See the UI design.</li>
<li>Clone the repository, read the README, run it. If the language is new to you, see the <strong>language quickstart topic</strong> (Elm, React Native etc.). Spend some time reading and doing the quickstart of the new language.</li>
<li>Understand the code. Please use Git History to understand better. Try change some codes and see what changes; this way, you know which part of codes affects which part of the app. Also, use global search in VSCode to explore a feature. For example, search <code>login</code> to find codes about login feature.</li>
<li>Get into the Freshrelease. Know which part of the tasks are assigned to you.</li>
</ol>
<h2 id="wrapping-up--a-day-as-a-software-engineer">Wrapping up : A day as a software engineer</h2>
<p>You start your day at 9:00 AM with a cup of coffee in front of your work desk.<br>
You read all unread messages in Slack and Telegram to make sure you did not miss anything.<br>
You open the backlog and sprint board in Freshrelease to see things you need to do left in the current sprint. Then you plan things to do for the day.<br>
In Slack channel, before 10AM, you open the daily stand-up channel for the project, #standups and write things like below:</p>
<p><strong>What did you do previously?</strong><br>
<strong>What will you do today?</strong><br>
<strong>Anything blocking your progress?</strong></p>
<p>You see other team members’ stand-up post for the day to make sure there are no problem between each others’ tasks.</p>
<p>You then start working on a task, after dragging the task in Freshrelease sprint board, from Todo to In Progress. After finishing the task and making sure it’s working, you drag it into Pending Review. In the meantime, you can start working on the next task. After being reviewed, you drag it into Done.</p>
<p>At the end of the day, tidy up your desk and turn off any appliances. You say goodbye to other team members.</p>
<h1 id="elm-language--quickstart">Elm language : Quickstart</h1>
<p>In Javascript, you have a lot of library or things to install and use, like npm, webpack, react, redux, flow, immutable.js. But in Elm, everything above are included in the language architecture itself (not a built-in library, but the language itself).</p>
<h2 id="why-we-want-to-use-elm">Why we want to use elm</h2>
<p>Please don’t skip this topic even though it has nothing to do with the elm language learning.</p>
<ul>
<li>Better user experience (faster page load time, no errors and more<br>
responsive UI!)</li>
<li>Better developer experience (friendly compiler warnings, faster<br>
compilation and clear upgrade instructions!) and thus lead to a better bottom line for the company using Elm!</li>
<li>Total Cost of Ownership for the lifetime of the project is considerably lower than other frameworks because maintenance (the majority of the life of an application) is much easier due to compiler warnings which prevent changes to your app that don’t compile.</li>
<li>No Run-time Errors - zero chance of an Elm program throwing an error which “breaks” the UI!</li>
<li>Enforced Semantic Versioning! Means that if something changes in a package that you depend on (a “dependency”) the author of that dependency is forced to update the version number which means you will receive a warning that it is no longer compatible with your App, i.e. impossible to “break” production!!</li>
<li>The speed is seriously much much faster that react etc.</li>
<li>Progressive Web Apps, you can just make one, and generate web, android and ios app with the same code.</li>
<li>Apps built with Elm are much more lightweight than other front-end frameworks and most cases will load in under a second on a mobile connection. We often see cases of Mobile Web Apps built with other web frameworks that have a 1mb+ “bundle” which takes 10 seconds to load on 3G!!</li>
<li>Because you can so heavily depend on the Elm compiler, updating and refactoring pieces of code is an absolute breeze. The compiler will complain for quite a bit of time, but the moment it stops from doing so, you are good to go. No need to test anything, simply follow the compiler guidance about each error he finds and your code will all start working again once you have done so. This experience really gives you a good confidence level in your software even after destroying it apart and rebuilding it. (Which normally, you would be unsure if you have missed something somewhere)</li>
</ul>
<p>References:</p>
<ol>
<li><a href="https://www.youtube.com/watch?v=RFrKffrKCeU">https://www.youtube.com/watch?v=RFrKffrKCeU</a></li>
<li><a href="https://github.com/dwyl/learn-elm/issues/129">https://github.com/dwyl/learn-elm/issues/129</a></li>
<li><a href="https://www.codementor.io/lb0/how-i-learned-elm-erls5ij7c">https://www.codementor.io/lb0/how-i-learned-elm-erls5ij7c</a></li>
<li><a href="https://www.reddit.com/r/elm/comments/9cl8tq/mobile_apps_with_elm/">https://www.reddit.com/r/elm/comments/9cl8tq/mobile_apps_with_elm/</a></li>
<li><a href="https://itnext.io/from-javascript-to-typescript-to-elm-5c36fca70b4a">https://itnext.io/from-javascript-to-typescript-to-elm-5c36fca70b4a</a></li>
</ol>
<h2 id="how-to-learn-elm">How to learn Elm</h2>
<p>Elm is a functional language that basically compiles to JavaScript. So, instead of we directly write a potentially buggy JavaScript, we write it in Elm until it is fail proof. However, learning Elm could be challenging since this might be your first functional language. With the new Elm version comes out (0.19.1 at the moment of writing), most of the tutorial out there is outdated, so we can’t use the tutorial right away. However, there are some good sources that you can use to learn Elm on the next topic.</p>
<h2 id="setting-up">Setting up</h2>
<p>Install elm according to your maching OS:<br>
<a href="https://guide.elm-lang.org/install/elm.html">https://guide.elm-lang.org/install/elm.html</a></p>
<p>In VSCode install this extension and read what it does:<br>
elmtooling.elm-ls-vscode</p>
<h2 id="how-to-learn-elm-1">How to learn Elm</h2>
<p>First, you can start by watching this: <a href="https://www.youtube.com/watch?v=kEitFAY7Gc8">https://www.youtube.com/watch?v=kEitFAY7Gc8</a><br>
You will be briefed about how the Elm language works compared to JavaScript.</p>
<p>After you know what Elm is, you can start learning the basics using the links below:</p>
<ul>
<li>
<p><a href="https://elmprogramming.com">https://elmprogramming.com</a><br>
It is encouraged to <strong>write notes</strong> and <strong>write the code</strong> when learning. You can see the notes example here: <a href="https://github.com/tengkusyafiq/elm-me-gusta">https://github.com/tengkusyafiq/elm-me-gusta</a></p>
</li>
<li>
<p><a href="https://github.com/bryanjenningz/25-elm-examples">https://github.com/bryanjenningz/25-elm-examples</a><br>
Here are some tips to learn from the example above:</p>
<ol>
<li>Open your visual studio code, and every online compilers of the example code on Google Chrome.</li>
<li>Take out a pen/pencil, and a notebook, write the date of today, this is your question log book.</li>
<li>Read every single line of the example code (make sure the command line too, they teach you important stuff)</li>
<li>If you encounter the line you don’t understand, write it down in the notebook, and open a new google Chrome to search for the content.</li>
<li>Keep your time while reading the content, don’t use too much of time, can try asking people around instead of just Google.</li>
<li>After you have understand, jot down the rough idea on the notebook, don’t write too long.</li>
<li>Repeat 3, until you finished, hide the compiler Google Chrome, and then code inside your visual studio code. (I have tried all the codes by this Github, they all works on Elm 0.19)</li>
<li>If you forget, don’t look at the browser and copy, cover the visual studio and read again the code form Chrome.</li>
<li>If the code run, comment the code, and use git to commit the changes of your code inside your own repository.</li>
<li>Repeat 3 for next file, until you reach the 25th file.</li>
</ol>
</li>
</ul>
<p>When learning Elm, you sure have questions about something, or stuck in any tutorials. If searching for answer on the internet doesn’t help, you can use the Slack to ask the Elm community in <a href="http://elmlang.slack.com">elmlang.slack.com</a> about it in #beginner channel. Trust me, they’re really helpful to guide you into learning Elm. You also can ask them for help whenever you stuck with a problem when doing an Elm project.</p>
<h3 id="how-to-expand-your-elm-knowledge-from-the-basic">How to expand your elm knowledge from the basic</h3>
<p>Now that you know most of the Elm basics, you have to know how to apply them in a project. For example, listed below is most common things an app has:</p>
<ul>
<li>Navigation throughout screens/pages</li>
<li>Login system</li>
<li>Getting data from API and displaying it on the screen</li>
<li>Getting data from user and sending it over an API</li>
<li>Push notification<br>
Mostly, you can learn all of these by looking at our Elm projects as an example.</li>
</ul>
<p>There are also additional features that are commonly used in our projects:</p>
<ul>
<li>Location tracking on a map view</li>
<li>Bluetooth feature</li>
</ul>
<p>Since Elm packages are not as wide as React Native in term of package varieties, we can use JavaScript to build additional features if Elm doesn’t have any package to build the features with yet. We then can use Elm and JavaScript side by side. That means, you also need to know how to use React/React Native and Elm together in one project. Links below are some references about this:<br>
<a href="https://youtu.be/uQjivmLan0E?t=1134">https://youtu.be/uQjivmLan0E?t=1134</a><br>
<a href="https://elm-lang.org/news/how-to-use-elm-at-work">https://elm-lang.org/news/how-to-use-elm-at-work</a><br>
<a href="https://github.com/cultureamp/react-elm-components">https://github.com/cultureamp/react-elm-components</a><br>
<a href="https://codeburst.io/using-elm-in-react-from-the-ground-up-e3866bb0369d">https://codeburst.io/using-elm-in-react-from-the-ground-up-e3866bb0369d</a></p>
<p>Finally, if you want to read more about Elm:<br>
<a href="https://github.com/tengkusyafiq/elm-me-gusta/blob/master/programming-elm-maintainable-front-end-applications.pdf">github.com/tengkusyafiq/elm-me-gusta/blob/master/programming-elm-maintainable-front-end-applications.pdf</a></p>
<h2 id="catching-up-with-our-elm-projects">Catching up with our Elm projects</h2>
<p>This topic only covers how to get used to the codes, not the project. See “Catching up with ongoing projects” topic.</p>
<p>Here’s how:<br>
Read README to run the code.<br>
Use Git History to understand codes historically.</p>
<h2 id="miscellaneous">Miscellaneous</h2>
<h3 id="how-to-deploy-elm-app-into-firebase-hosting">How to deploy Elm app into firebase hosting</h3>
<h3 id="great-tutorials-about-ports-in-elm">Great tutorials about ports in elm</h3>
<p><a href="https://hackernoon.com/how-elm-ports-work-with-a-picture-just-one-25144ba43cdd">https://hackernoon.com/how-elm-ports-work-with-a-picture-just-one-25144ba43cdd</a><br>
<a href="https://thoughtbot.com/blog/bridging-elm-and-javascript-with-ports">https://thoughtbot.com/blog/bridging-elm-and-javascript-with-ports</a></p>
<h3 id="great-explanation-about-task-in-elm">Great explanation about task in elm</h3>
<p>What is it, how to use it etc:<br>
<a href="https://ohanhi.com/tasks-in-modern-elm.html">https://ohanhi.com/tasks-in-modern-elm.html</a><br>
More complex about Task:<br>
<a href="https://korban.net/posts/elm/2019-02-15-combining-http-requests-with-task-in-elm/">https://korban.net/posts/elm/2019-02-15-combining-http-requests-with-task-in-elm/</a></p>
<h1 id="react-native--quickstart">React Native : Quickstart</h1>
<h2 id="why-we-use-react-native">Why we use React Native</h2>
<p>Lots of support, libraries, and tutorials. Unlike Elm, you can find a lot of supports and references on the internet.</p>
<h2 id="setting-up-1">Setting up</h2>
<p>They have a lot of tutorials, Google it, or see the reference below.<br>
<a href="https://shift.infinite.red/getting-started-with-react-native-development-on-windows-90d85a72ae65">https://shift.infinite.red/getting-started-with-react-native-development-on-windows-90d85a72ae65</a></p>
<p>Additional info:<br>
If you use android emulator, make sure you run the emulator first, and wait until the google home menu appear and it is ready to use like any android device.</p>
<p>If you don’t wanna use emulator (for example, your PC is slow) and wanna use android device for faster process, <a href="https://facebook.github.io/react-native/docs/running-on-device">https://facebook.github.io/react-native/docs/running-on-device</a></p>
<p>If you want to re-run the code or another app, please make sure you close the node terminal. else, you’ll get error.</p>
<p>At this point, your computer should be ready to run react native code. You can re-confirm it by trying to run this react native example project below:<br>
<a href="https://github.com/mariodev12/react-native-netflix">https://github.com/mariodev12/react-native-netflix</a><br>
, or any example you can find online.</p>
<h2 id="how-to-learn-react-native">How to learn React Native</h2>
<p>Use Udemy course named “React Native - The Practical Guide” by Maximilian.<br>
When learning, you can see the notes below for better understanding.<br>
<a href="https://github.com/tengkusyafiq/Udemy---React---The-Complete-Guide-by-Maximilian---Lecture-Notes">https://github.com/tengkusyafiq/Udemy---React---The-Complete-Guide-by-Maximilian---Lecture-Notes</a></p>
<p>To start applying what you have learn into a project, please find any good scaffold for you to get used to.</p>
<h1 id="backend--quickstart">Backend : Quickstart</h1>
<h2 id="how-to-access-a-server">How to access a server</h2>
<p>You can use WinSCP to explore the files and folders in the server.<br>
Install WinSCP: <a href="https://winscp.net/eng/download.php">https://winscp.net/eng/download.php</a></p>
<p>You can use Putty to send command line to the server.<br>
Install Putty:<br>
<a href="https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html">https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html</a></p>
<h2 id="how-to-catch-up-with-backend-projects">How to catch up with backend projects</h2>
<p>For Django project:</p>
<ul>
<li>The main file to run is <a href="http://manage.py">manage.py</a>, where in the code below, it shows that the file calls gpsf/setting.<br>
<code>os.environ.setdefault('DJANGO_SETTINGS_MODULE', 'gpsf.settings')</code></li>
<li>In gpsf/urls.py, it lists all next endpoint, for example:</li>
</ul>
<pre><code>urlpatterns = [
path('admin/', admin.site.urls),
path('data/', include('data_module.urls')),
path('auth/', include('login.urls')),
path('api/', include('external_api.urls')),
path('account/', include('accounts.urls')),

...
]
</code></pre>
<ul>
<li>Let’s take ‘account/’ endpoint for example, go to accounts folder to see what it does.</li>
<li><a href="http://Urls.py">Urls.py</a> is the next-next endpoint.</li>
<li><a href="http://Views.py">Views.py</a> has the logics and functions</li>
<li><a href="http://Models.py">Models.py</a> is where you declare the database field etc. you see this in admin panel.</li>
</ul>
<h1 id="miscellaneous-topics">Miscellaneous topics</h1>
<h2 id="how-to-face-clients-as-a-technical-person-engineerdeveloper-etc.">How to face clients as a technical person (engineer/developer etc.)</h2>
<ul>
<li>Tell them what feature is already there, and what’s not there.</li>
<li>Talk about feature, time, bug(risk). Avoid talking technical things.</li>
<li>If client ask, ‘can you do this or that?’, we need to refer our team. Do not accept the request right away.</li>
<li>Don’t tell client about other project.</li>
</ul>

