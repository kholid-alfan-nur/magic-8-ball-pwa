# magic-8-ball-pwa
Magic 8 ball progressive web app - from scartch

This is a PWA web app below is the step by step tutorial:

- clone https://github.com/rhildred/progressive-web-start.git
- follow instructions on https://dzone.com/articles/a-step-by-step-tutorial-for-developing-a-progressi (start from step 6, we did 1-5 on friday)
- on CLI in VSCode:
npm install
npm run start (this will run the web app in localhost)

-go to index.html and paste <link rel="apple-touch-icon" href="%PUBLIC_URL%/Icon_Bird_512x512.png" sizes="512x512" />
  this enables the icon on apple devices
- go to  https://firebase.google.com/  and create a firebase account with your google login
-on CLI in VSCode:
$npm install -g firebase-tools
--enter yes in the options that appears--
$firebase login
$firebase init
--enter yes--
--select Hosting in the options--
--create a new project--
--build--
--yes--
$firebase use --add
--alias is "production"--
$firebase deploy
