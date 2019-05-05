* [4 Help Center by Jekyll](#4)

* [4.1 Use a theme](#4.1)

* [4.2 Modify the configuration](#4.2)

* [4.3 Change header, left tree, footer](#4.3)

* [4.4 Add files](#4.4)

  

  ##  <h2 id="4">Help Center by Jekyll</h2>

  Build a static website  `help center` by Jekyll.

  <h3 id="4.1">Use a theme</h3>

  - Download a theme.

  For a help center , download the `Less Or More` theme from http://jekyllthemes.org/

  ![1556972713607](C:\Users\goodluck\AppData\Roaming\Typora\typora-user-images\1556972713607.png)

  

  - Install Jekyll:

  [Install Jekyll on Mac](https://idratherbewriting.com/documentation-theme-jekyll/mydoc_install_jekyll_on_mac.html)

  [Install Jekyll on Windows](https://idratherbewriting.com/documentation-theme-jekyll/mydoc_install_jekyll_on_windows.html)

  

  - install Bundler

  ```
  gem install bundler
  ```

  

  - Run jekyll serve 

  ```
  jekyll serve
  ```

  You can see the result in browser URL`http://127.0.0.1:4000/`.

  ![1556976873233](C:\Users\goodluck\AppData\Roaming\Typora\typora-user-images\1556977861439.png)

  

  <h3 id="4.2">Modify the configuration</h3>

   Change  following parts in`_config.yml`，open it with  text editor like `WordPad` or visual code.

``` bash
name: 
email: 
author: 
url: 
# baseurl should be the project name. If project is'username.github.io' like 'Jane.github.io',baseurl should be empty.
baseurl: "/LessOrMore" 

github: 
github_username: 

```

>  Note the configuration of *baseurl*  should be empty if it's a *username.github.io* project. Or static resource like JS, CSS would be not found.

Codes of `_config.yml` are like this:

![1556973202572](C:\Users\goodluck\AppData\Roaming\Typora\typora-user-images\1556973202572.png)

Refresh the website.

![1556978117307](C:\Users\goodluck\AppData\Roaming\Typora\typora-user-images\1556978117307.png)



<h3 id="4.3">Change header, left tree, footer</h3>

Codes of header and left tree are like this:

![1556975830448](C:\Users\goodluck\AppData\Roaming\Typora\typora-user-images\1556975830448.png)

![1556975881769](C:\Users\goodluck\AppData\Roaming\Typora\typora-user-images\1556975881769.png)

Refresh the website.

![1556975989581](C:\Users\goodluck\AppData\Roaming\Typora\typora-user-images\1556975989581.png)

Codes of footer are like this:

![1556975750855](C:\Users\goodluck\AppData\Roaming\Typora\typora-user-images\1556975792005.png)

Refresh the website.

![1556976090610](C:\Users\goodluck\AppData\Roaming\Typora\typora-user-images\1556976090610.png)



<h3 id="4.4">Add files</h3>

 Add files under the ` LessOrMore / _posts ` directory . Paste the following information,  modify  ` titile `, ` date `, ` categories `, ` tag ` information, and add ` * content {: toc} ` for directory information.

``` bash
---
layout: # like "page"

title:  # like Alerts

date:  #like 2016-08-27 01:08:00 +0800

categories: # like document
 
tag: #like formatting
---

* content
{:toc} # Two blank lines are between the body and the content.


This is the body part.# Body part uses Markdown syntax.
```

> Files should be saved like `2014-11-17-welcome-to-jekyll.md`

Codes of new file named `2018-05-04-origin-documents` are like this:

![1556973984895](C:\Users\goodluck\AppData\Roaming\Typora\typora-user-images\1556974058592.png)



You can see final result in browser URL`http://localhost:4000/`.

![1556974189741](C:\Users\goodluck\AppData\Roaming\Typora\typora-user-images\1556974189741.png)

![1556974313451](C:\Users\goodluck\AppData\Roaming\Typora\typora-user-images\1556974313451.png)

