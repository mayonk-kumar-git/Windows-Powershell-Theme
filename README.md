# Windows-Powershell-Theme
* Follow this blog to setup posh-git and oh-my-posh : https://dev.to/shahinalam02/customize-your-terminal-using-oh-my-posh-theme-38if
* You can access the oh-my-posh themes at the location : C:\Program Files\WindowsPowerShell\Modules\oh-my-posh\3.153.1\themes
* Now you can copy past this json file to this location in your pc (NOTE: this will only work once you have installed posh-git and oh-my-posh and set it up in your pc)
* To apply this theme use this command in windows powershell : Set-PoshPrompt -Theme monkItUp
* To apply this theme everytime you open your windows terminal add this theme to your profile, to do so use command : notepad $profile (then to that notepad add) Set-PoshPrompt -Theme monkItUp 
