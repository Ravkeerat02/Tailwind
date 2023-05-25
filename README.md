Courses 
- [TailWind Crash Course](https://www.youtube.com/watch?v=UBOj6rqRUME)

### Notes 

<!-- IN MY UNDERSTANDING AS OF NOW ITS LIKE WRITING STYLE IN YOUR LANAGUEG. BUT IN A PROGRAMMING FORM -->
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

Theme Config 
- Used for defining color palette , type scale , fonts , breakpoints

Theme Structure 
- Includes screens , colors , spacings
- Screen - customize breakpoints 
- Colors - customize gloval color palette
- Spacing - customize global spacing

Coding example 
`<div class="border border-gray-300 rounded-md p-4 flex items-center">
  <img class="shrink-0 h-10 w-10 rounded-full h-16 w-16 object-cover" src="https://images.unsplash.com/photo-1580489944761-15a19d654956?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1361&q=80" alt="" />
  <div class="ltr-ml-3 rtl-mr-3">
    <p class="text-sm font-medium text-gray-700 group-hover:text-gray-900">
      <a href="#">Jane Doe</a>
    </p>
    <p class="text-xs font-medium text-gray-500 group-hover:text-gray-700">
      <a href="#">Unemployed</a>
    </p> 
  </div>
</div>
`
Explanation
- border: Sets a border around the box.
- border-gray-300: Specifies the color of the border (in this case, a light gray shade).
- rounded-md: Rounds the corners of the box.
- p-4: Adds padding of 4 units to create some spacing between the content and the box edges.


