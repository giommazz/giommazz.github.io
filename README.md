# giommazz.github.io
My [personal website](https://giommazz.github.io/), built with the Minimal Mistakes theme for Jekyll.

# HOW TO

## Git clone and initial setup
1) First, use this link [https://github.com/mmistakes/minimal-mistakes/fork](https://github.com/mmistakes/minimal-mistakes/fork) to fork the Minimal Mistakes theme

2) Now the name of the GitHub repo you forked is something like `https://github.com/<GITHUB_USERNAME>/minimal-mistakes/`

3) go to `Settings` and rename the repo to `<GITHUB_USERNAME>.github.io`
   
4) Clone the repository:
   ```sh
   git clone git@github.com:<GITHUB_USERNAME>/GITHUB_USERNAME.github.io.git website
   ```

5) If you forked or downloaded the `minimal-mistakes-jekyll` repo, you can safely remove the following folders and files:
   * .editorconfig
   * .gitattributes
   * .github
   * /docs
   * /test
   * CHANGELOG.md
   * minimal-mistakes-jekyll.gemspec
   * README.md
   * screenshot-layouts.png
   * screenshot.png

6) Now let's push to git:
   ```sh
   git add _config.yml
   git commit -m "commit message"
   git push
   ```
7) Finally, let's go online: go back to the `Settings` page of your GitHub repo `https://github.com/<GITHUB_USERNAME>/<GITHUB_USERNAME>.github.io.`: change the repository name to `<GITHUB_USERNAME>.github.io`. `GITHUB_USERNAME` has to exactly match your GitHub username.


## Website structure and how to add/edit content
Now, all of the actual content of your site is contained in `.md` (Markdown) files. Most of these files live in the `_pages` directory. 

Useful info:
* The **landing page** can be changed by editing the `_pages/about.md` file
* **sidebar information** and **general info** are determined in the `_config.yml` file.
  Important keywords in `_config.yml`:
  * `title`: your website title
  * `name`: your name
  * `url`: `https://<GITHUB_USERNAME>.github.io`
  * `baseurl`: ""
  * `repository`: `"<GITHUB_USERNAME>/<GITHUB_USERNAME>.github.io"`
* To **add sections** to the website, add `.md` files to the `_pages` directory. Also, every time you add a section, make sure to add it to `_data/navigation.yml`, which contains the **backbone of your website**
* To **override css info** (font, font size, etc.), edit `assets/css/main.css`

## TODOs
* add hyperlinks in the "About" section
* Search engine optimization

# RESOURCES
Webpages that I used to create my website, plan to use to improve it, and inspired me to put together the above guidelines:
   *	[https://jayrobwilliams.com/posts/2020/06/academic-website/](https://jayrobwilliams.com/posts/2020/06/academic-website/)
   *	[https://jayrobwilliams.com/posts/2020/08/website-content/](https://jayrobwilliams.com/posts/2020/08/website-content/)
   *	[https://jayrobwilliams.com/posts/2020/07/customizing-website/](https://jayrobwilliams.com/posts/2020/07/customizing-website/)
   *	[https://github.com/jayrobwilliams/jayrobwilliams.github.io/tree/master](https://github.com/jayrobwilliams/jayrobwilliams.github.io/tree/master)
   *	[https://www.cross-validated.com/Personal-website-with-Minimal-Mistakes-Jekyll-Theme-HOWTO-Part-II/](https://www.cross-validated.com/Personal-website-with-Minimal-Mistakes-Jekyll-Theme-HOWTO-Part-II/)
   *	[https://medium.com/@tienduy/build-your-personal-website-without-spending-any-money-30e6b2264e08](https://medium.com/@tienduy/build-your-personal-website-without-spending-any-money-30e6b2264e08)
   *	[https://naiyanjones.com/technology/optimising-website-images-with-python/](https://naiyanjones.com/technology/optimising-website-images-with-python/) for image optimization
