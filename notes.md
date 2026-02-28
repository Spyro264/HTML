# What is Defer ?

- defer is the attribute which we use in script tag that tells the browser to download this script file but dont execute it until the html has finished loading.

# What is Async ?

- async is an attribute used in script tag .
- when we use asyn attribute i script tag the browser downloads the script in the background while continue to parse HTML.
- as soon as script finishes downloading . the browser pauses the html parsing to execute it.

# Difference between asyn and defer attribute ?

- with async attrubute browser downloads the script in the background while continue parse html .
- once the script finished downloadig broweser pauses html parsing to executes it immediately.
- with defer attribute browser downloads the script in the background while continue parse html.
- but wait until html to complete its parsing then executes the script.

# What is <script> tag ?

- the script tag is used to enbed or reference js code in your webpage.
- in simpler words it tells the browser that here some js code to execute.
- tow ways to use script tag 1. inline and extrernal js

# What are semantic elements ?

- semantic elements are the html tags that clearly describes the the purpose of the content that thay contian to both developers and browsers.
- simple definition : a semantic element =  meaningful html tag.
- Ex: <p> , <header> , <section> , <article> , <aside> , <footer>.
- by using semantic elements code readabilioty will improve , search engines understands your page better . very important for SEO 
- screen readers can interpret content correctly for visually impared people .

# What is the difference between id , class and data-* ?

- id is an attribute , it is an unique indentifier which we can use with html tags , id must me uniqiue.
- class is an attribute , it is used to group elements so they can share the same style or behaviour.
- data-* is an custom attribute which is used to store custom data directly inside the html elements. `<button data-user-id="123" data-role="admin">Click</button>`


# A page layout is breaking in Safari but working in Chrome How will you debug it.

- 


# What is the use of <DOCTYPE> ?

- <!DOCTYPE html> is a declaration that tells the browser which version of HTML page is using so it can render that page accordingly