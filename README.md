# Image-Gallery
This is an Image gallery built using the Pixaby API in React.js and Tailwind 
In this project we understand how tailwind css, which is a CSS library works with React.
An API is used to pull images and videos with a few descriptive lines.
For following along with tailwinf and installing dependencies follow https://www.smashingmagazine.com/2020/02/tailwindcss-react-project/

Follow along the below lines if any error shows up:

npx create-react-app img-gallery
  cd img-gallery
  npm start

  npm start
    Starts the development server.

  npm run build
    Bundles the app into static files for production.

  npm test
    Starts the test runner.

  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!


 touch postcss.config.js
>>
touch : The term 'touch' is not recognized as the name of a cmdlet, function, 
script file, or operable program. Check the spelling of the name, or if a path 
was included, verify that the path is correct and try again.
At line:1 char:1
+ touch postcss.config.js
+ ~~~~~
    + CategoryInfo          : ObjectNotFound: (touch:String) [], CommandNotFoundE 
   xception
    + FullyQualifiedErrorId : CommandNotFoundException
   
   TO FIX THIS ERROR COPY THE BELOW CODE:
 
 npm install touch-cli -g

+ touch postcss.config.js
+ ~~~~~
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess
PS C:\Users\user\Desktop\Image-Gallery\img-gallery> PS C:\> Set-ExecutionPolicy RemoteSigned
Get-Process : A positional parameter cannot be found that accepts argument 
'Set-ExecutionPolicy'.
 Type this to fix:
 Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted
 npm start





























































































































































































