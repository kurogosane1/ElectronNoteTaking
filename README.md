# Note Taking Markdown App
 ![](https://i.imgur.com/1NyVyUm.png)
 

This app was made with the purpose of seeing if React and ElectronJS was possible to work with. 
This was simply a personal practice to see the things that were possible with ReactJS and ElectronJS. 

__This is still under development and so may be buggy__

__Final Design is still under works__

For those that need to use this. 
Simply run 
`yarn build`

in some cases you may need to use `sudo` to run as administrator. 
If you've downloaded this code and run `yarn build` it shall build itself according to the operating system you are using and would create a `dist` folder where the app would be located. So in my case I was using Ubuntu Budgie Linux OS. If you want to run it on a MacOS then run the command on a mac computer and it shall build a MacOS version and vice versa for Windows. 

You need install `Electron-icon-builder` inorder for you to have icons that would work with this app however, I learnt that it doesn't work on linux and works on the other two OS for some reason. Thats why I was unable to add the icons however you can add them later on yourself under asset icon. 

### *Development **purpose***

Those that need to use it for such case. 
You may need to modify the package.json `script` section while in development. The package.json right now is already ready for production.
After Modifying run `npm install` to install the modules and then run either `npm start` or `yarn start`. This would run the create-react-app from what it was originally made. However, you may see some issues on the webpage version. In a seperate tab of the termainal or another terminal run `yarn electron`. This shall open the actual electron app and you shall see it running perfectly fine while the web app won't.

if you need to use the console of electron then after running electron simply press `Ctrl+Shift+I` or for mac `Cmd+Shift+I`

### So enjoy!!! ###
# ElectronNoteTaking
