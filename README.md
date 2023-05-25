Courses 
- [TailWind Crash Course](https://www.youtube.com/watch?v=UBOj6rqRUME)

### Notes 

TypeScript - JS with type checking , code completion , refactoring and new features - perfect for medium to large projects 

Benefits 
- Static Typing 
- Code completion 
- Refactoring
- Shorthand notation
- Can directly do in components


Drawback
- Compilation 
    -  Transpilation 
        - .ts -> compiler -> .js   
- Need to be clean in writing the code 

Build option
- CLI
- Using Post CSS
- Frameworks
- Play CDN 


Notes 
- tsc : helps in compiling the ts code . Converst the file into js which makes it easier to run 
- Tailwind runs as a postcss(plugin) and autoprefixer(old version).
- when using cdn `style ` has to be used in the code
- OnTime Compiler - can create on your own custom style if needed


Preflight - resets all the css - can be turned off by setting - setting it off resets the current styles 
`tailwind.config = {
    corePlugin: {
        preflight: false
} `

- Margins removed 
- Unstyled heading 
- List unstyled- no padding , style(bullet)
- Block iMAGES 
- Boredrs reset 

Utility First 
- No unclear names 
- Clear intent 
- No override 
- In simple words its similar to using css styling 
Ex - p6(padding 6 ) mxauto(automatically centre) rounded xl(rounded edges - sizes)

Color classes
- Bg class (bg-COL-STR)
- Text(text-COL-STR)
- Ranges between 50-900


