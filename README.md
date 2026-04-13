# Kofik-script
Step1.Change context in dev tools from "top" to "eu.jotform.com" in dropdown list under "elements" tab Step2. Execute kofikscript:  [...document.getElementsByClassName("form-field-hidden")].forEach(elem =>  {elem.style.display = 'block'}); [...document.getElementsByClassName("form-collapse-hidden")].forEach(elem =>  {elem.style.display = 'block'});
