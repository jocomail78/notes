# Less 

``
npm install less -g 
npm install -g less-watch-compiler
``
For compiling one single less file:
``
lessc master.less master.css 
``
For watching 
``
less-watch-compiler [options] <source_dir> <destination_dir> [main-file]
``
With basic example: 
``
 root 
 └──src
 │    └── main.less
 │    └── aux.less
 └──dist
      └── main.css
``
The code would be: 
``
less-watch-compiler src dist main.less
``
