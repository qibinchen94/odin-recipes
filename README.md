# odin-recipes
HTML recipes


# About
This is a project for the HTML Foundations: a basic recipe website

# Skills needed
 - ### Git workflow
    - Create repository on Github
    - Clone to local machine
        ```shell
        git clone git@github.com:user-name/repository-name.git 
        ```
    - Display URL of repository
        ```shell
        git remote –v 
        ```
    - Display status
        ```shell
        git status 
        ```
    - Add file to staging area
        ```shell
        git add file.txt
        ```
    - Commit
        ```shell
        git commit -m "commit message" 
        ```
    - Display log
        ```shell
        git log
        ```
    - Push
        ```shell
        git push origin main 
        ```
- ### HTML Foundations
    - Elements and tags
    - HTML Boilerplate
    - Paragraphs (`<p>`), Headings (`<h1>` to `<h6>`), Bold (`<strong>`), Italic (`<em>`), Comment(`<!--Comment here-->`)
    - List, including [unordered](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul) (`<ul>`) and [ordered](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol) (`<ol>`)
    - Links (`<a>`)
        - Absolute link
            ```html
            <a href="url">Link</a> 
            ```
        - Relative link
            ```html
            <a href="./subfolder/document.html">Link to a document in a subfolder</a>
            ```
            ```html
            <a href="../parentfolder/document.html">Link to a document in a parent folder</a>
            ```
    - images (`<img>`)
        ```html
        <img src="url-or-documents" alt="text shown in case image cannot be loaded">
        ```
