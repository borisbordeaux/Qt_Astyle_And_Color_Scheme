# Qt_Astyle_And_Color_Scheme
C++ Astyle beautifier style file and color scheme for Qt

## How to use the beautifier

### Install Astyle
First install astyle with `sudo apt install astyle` in Linux  

### Configure Astyle in Qt
Then in Qt, install the plugin beautifier `Help -> About plugins...`  
Now go in the options to define the settings for the Artistic Style beautifier  
`Tools -> options... -> Beautifer -> Artistic Style`  
For simplicity, place the `.astylerc` file in your home directory  
Then check the checkbox `Use the file .astylerc or astylerc in /home/user`  
More over you can set a keyboard shortcut to format the current file in the editor  
`Tools -> Options... -> Environment -> Keyboard -> ArtisticStyle -> FormatFile`

## How to use the color scheme
You just need to import the xml file and use it  
`Tools -> Options... -> Text Editor -> Font & Colors`

## Results
![The results applying these config](./result/result.png)
