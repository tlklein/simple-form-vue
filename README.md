# VUEJS Exercises


This code is a simple form app in Vue, HTML, and JS. It is a form app that can calculate the total of facilities
based on the button the user clicks. 

![screenshot](stock-1.png)

## Requirements
```
- Items displayed by loop.
- Items can be tooggled.
- Items can calculate total based on buttons.
- Currency is formatted to USD.
- Final commit with message saying "Finished Part1". 
- Remove Node Modules.
- No hello world or vue welcome components.
- Github link is submitted.
- No errors thrown. 
- Final commit with message saying "Finished Part2". 
```

## Structure  
```
simple-form-vue
├─ .gitignore  
├─ jsconfig.json  
├─ package-lock.json
├─ package.json
├─ vite.config.js
├─ readme.md
└─ public
   ├─ favicon.ico
└─ simpleform
   ├─ part1-form-app.html
└─ src
   ├─ app.vue
   ├─ main.js
   ├─ assets
   |   └─ base.css
   |   └─ logo.svg
   ├─components
   |   ├─ icons
   |   |  └─ iconcommunity.vue
   |   |  └─ icondocumentation
   |   |  └─ iconecosystem.vue
   |   |  └─ iconsupport.vue
   |   |  └─ icontooling.vue
   |   └─ form.vue
```

## Timeline
```
3/8/2024 - start development
- updates form.vue using claude 
- changed html & formatting
- remove hello world and welcome code

3/9/2024 - 3/15/2024
- updated readme with req
- updated css
- cleaned & format code
- create a new json file to resolve a false positive error
- create comments in edited files
- transfered part1-form-app.html functionality to form.vue

4/7/2024-4/9/2024
- clone to simple-form-vue on github
```

## References & Citations
```
1. Claude 3 Opus
- Prompt: complete the html file with the appropriate changes and the part1-form-app.html file was attached.
- Follow-Up Questions: change the html file to meet the requirements set by this file
- Revised: Changed some style and css errors and cleaned up unnessesary code. 
- Outcome: I found the code to properly implement the css and formatting without having to majorly rehaul the structure of the code. 
- Link: https://claude.ai/
- Prompt: migrate the html file and implement the changes into a file called form.vue.
- Follow-Up Questions: none this time, as this was a separte prompt from the one above. 
- Revised: Cleaned up some unessesary code, and added a jsconfig file to solve an error. 
- Outcome: I migrated the code in the part1-form-app.html to a form.vue file. 
- Link: https://claude.ai/
2. False positive errors at end-of-file
- Link: https://github.com/vuejs/language-tools/issues/3942 
3. Vuepress Vue Tip and Folder Structure
- Link: https://stackoverflow.com/questions/68737750/vuepress-vue-tip-and-folder-structure
4. Print Directory & File Structure with icons for representation in Markdown 
- Link: https://stackoverflow.com/questions/19699059/print-directory-file-structure-with-icons-for-representation-in-markdown 
5. How to add images to README.md on GitHub?
- Link: https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github 
```