# JAXL assignment

# Setup instruction
<ul>
  <li>install vs code</li>
   <li>install node.js</li>
  <li>install mongodb database</li>
  <li>create an account on mongodb.</li>
  </ul>
  
# Dependency management
<ul>
  <li>npm i express </li>
  <li>npm i body-parser</li>
  <li>npm i mongoose</li>
  </ul>
  
# How to try
<ul>
  <li>first of all registration page will open </li>
<li>In which you have to fill the basic information such as:</li>
<li>name ,email,password,phone no.</li>
<li>After that you have to click on send otp button which will take you to next page and all the given information will be saved in database</li>
<li>Then you have to authenticate the email ,password ,OTP to reach the home page .</li>
  </ul>

# Directory
  <ul>
    <li>dist : for compiled modules that can be used with other systems.</li>
    <li>src : intended for code that needs to be manipulated before it can be used.</li>
    <li>lib : intended for code that can run. </li>
    <li>build : for any scripts or tooling needed to build your project.</li>
    <li>bin : for any executable scripts, or compiled binaries used with, or built from your module.</li>
    <li>test : for all of your project/module's test scripts.</li>
    <li>package</li>
    <li>readme</li>
  </ul>
  
 # dist
  when you want to use your project in other platform should put outputted files in dist directory,like **app.js & index.html**.
  it's better to use this format : (module)-(version).(platform).[min].js .
  
 # modules
 A module is any file or directory in the node_modules directory that can be loaded by the Node.js require() function.
  module must be one of the following :
   * A folder with a package.json file containing a "main" field.
   * A folder with an index.js file in it.
   * A JavaScript file.
  
 # src
  The src directory is home to the actual codebase of the application and the target of our build tools.
  it cnotains **lib,client,server files,app.js
  
  
  ## lib
     The lib directory is home to all code that is used by the client and the server.
     we can treat modules in the lib directory like installed modules.
     This directory can contain **login.js & user.js**.
     
      
   ## app
     Contains the component files in which your application logic and data are defined. See details below.
  
  ## index.html
     The main HTML page that is served when someone visits your site. The CLI automatically adds all JavaScript and CSS files when building your app, so you typically don't need to add any <script> or<link> tags here manually.
     
  # bin
  The bin folder is for any system modules your package will use and/or generate.
  It use for any miscellaneous scripts that may accompany the application,and we have package.json/bin scripts for our module.
  
  
  
  # package
  A package is a file or directory that is described by a package.json file. A package must contain a package.json file in order to be        published to the npm registry.
  
  ## package.json
     we can add a package.json file to our package to make it easy for others to manage and install. Packages published to the registr      must contain a package.json file.

     * A package.json file:

      * lists the packages your project depends on
      * specifies versions of a package that your project can use using semantic versioning rules
      * makes your build reproducible, and therefore easier to share with other developers
    
 # README
 Introductory documentation for the root app.
 README (as the name suggests: "read me") is the first file one should read when starting a new project. It's a set of useful information about a project, and a kind of manual. A README text file appears in many various places .
 
 # conclusion
The structure of javascript project is like this:
<ul>
  <li> dist</li>
  <ul><li> node_modules</li></ul>
<li> src</li>
<ul>
<li>lib</li>
  <li >app.js</li>
  <li> index.html</li>
  </ul>
 
  <li> package.json</li>
  <li>README</li>
 <ul>
  <hr>
