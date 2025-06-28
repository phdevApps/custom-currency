# You Can Clone the repo and Copy the files to your project as well 
    - Files 
        - custom_currency.sfd 
            - the fontforg project file if you need to edit anything
        - custom_currency.woff
            - the webfont file that you have to load in the head of the document
        - index.html
            - the example html file
        - style.css
            - the example css file


# For United Arab Emirates Derham use this unicode in the html document 

Unicode: `&#xFFFFD;`
# Example

`CSS:-`
- loading the web font face

    `@font-face {
    font-family: "cutom-currency";
    src: url(./custom_currency.woff);
}`

- Setting the font-family for the webfont

    `.custom_currency {
    font-family: "cutom-currency" !important;
}
`

`HTML:-`
- Setting the class
    `<div class="custom_currency">&#xFFFFD;129</div>`


# For Kingdom of Saudi Arabian Riyal use this unicode in the html document 

Unicode: `&#xFFFFC;`
# Example

`CSS:-`
- loading the web font face

    `@font-face {
    font-family: "cutom-currency";
    src: url(./custom_currency.woff);
}`

- Setting the font-family for the webfont

    `.custom_currency {
    font-family: "cutom-currency" !important;
}
`

`HTML:-`
- Setting the class
    `<div class="custom_currency">&#xFFFFC;129</div>`
