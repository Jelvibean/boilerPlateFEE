# BoilerPlate Template to Start off FEE projects
This is a simple setup to start off any front end project. <br>

<strong style="color: blue;">Areas setup in this Project:</strong><br>
  1. It creates a dummy directory structure for your CSS and JS
  2. It creates a grunt.js file to run the important task needed to run a front end project.<br>
      a. Sets your Sass, converts to CSS and then mimifies it.<br>
      b. Sets your JS through Uglify, combines all your js files and mimifies them.<br>
      c. It relaunches your browser any time it detects a change with browserSync<br>
      d. Package.json sets all calls to all the tasks needed to run this project.<br>
      
      
<strong style="color: blue;">Steps to use this project:</strong><br>
1. Create a directory in your computer of where you want to house this project.<br><br>
2. Open Terminal windows -> cmd -> traverse to directory you created.<br><br>
3. Run "NPM Install"<br><br>
4. Run "grunt"<br><br>
        &nbsp;If you get <strong>errors</strong> requesting you to install Ruby you may need to go: http://sass-lang.com/install.<br>
        &nbsp;Follow instruction on how to install ruby and sass.<br>
        &nbsp; Reason for this is you need Ruby and Sass install at the global level to have this run.<br>
5. Magincally your browser should come up at  http://localhost:3000/<br><br>
6. In Browser hit:  http://localhost:3000/index.html.<br><br>
7. Now open your project in your favorite IDE<br><br>
8. Make a small change, save and see them happen on the browser.

     <br>
 Happy Coding!!
