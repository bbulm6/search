# Search Engine README
This is the repository of search engine website I did for senior design class. Due to the confidential nature of the website, I chose to share only HTML and CSS files.

## HTML templates
In honor of DRY (Don't Repeat Yourself) principle in software engineering, every HTML page of the website is created from a template. This makes updating code easier, since I could easily update the header and footer of the website without copying and pasting in multiple places.

Since the website uses the Go programming language (formerly PHP) as a backend, I chose to use the HTML template parser (https://golang.org/pkg/html/template/) from the standard library.

## CSS Styling
To simplify development, I used SASS (http://sass-lang.com/) to generate minified CSS files.
