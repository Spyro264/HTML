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