egghead Github Action Lession 1  

1st create file index.js
inside type console.log('hello') and
this to check to see it works properly

2nd make repo on github (optional if u have one | if u dont make one)
on terminal git clone url 

3rd in folder of the url npm init -y
this to generate json based on url u clone url

4th make action.yaml file

5th inside action.yaml follow  the follow formatter

name: "" 
description: ""
author: ""

runs:
  using: "node 18.5.0"
  main: 'source.js'

meaning:
- name _ is for of the project name
- description _  of the project details
- author _  source or contact on owner

- runs _  this is the source attribute
- using _  this a property that tell the environment im using
- main _  is what file im accesing the index.js (or my refence source.js)


6th push to github to use actions




