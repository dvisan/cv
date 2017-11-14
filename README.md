# cv

A clean HTML resume created using [resume-cli](https://github.com/jsonresume/resume-cli/blob/master/README.md)

1.Select your theme, fill out and download you .JSON resume using this [tool](http://registry.jsonresume.org)

2. `npm install -g resume-cli`

3. npm install the resume theme you used to generate the resume

4. `resume export yourjsonfile --format html --theme yourchosentheme`

5. Ignore the warnings and push the exported html as an `index.html` file in a new repository

6. In the repository's settings, assign the master branch as the one used for github pages

7. Now preview your resume at `yourname.github.io/yourrepository/` and update it whenever you feel like doing so

My [example](https://dvisan.github.io/resume/). It needs some side tinkering, but it can print out or be exported as a PDF too. Resume-CLI's PDF feature is not properly working the design yet.
