# Danish ANSI Keyboard Layout for Windows
Adds support for &lt;> and \ on the Danish ANSI layout
Made using The Microsoft Keyboard Layout Creator

Last year (2021 as of writing) I switched from a Nordic ISO layout to a UK ANSI keyboard. This of course caused some issues, since I prefer, and am just used to, the Danish keyboard, due to me having used it my entire life, and because I also code. At first I decided to just use the UK/US ISO layout while coding, but it was very tedious, since most keys were not in the place I was used to.

I therefore decided to see if I could find any keyboard layouts or programs, just anything, that could resolve this issue.
I found some, but they weren't to my personal liking. I ended up finding Microsofts Keyboard Layout Creator tool, which was just up my alley and I am so glad they made it.

I have used this layout for a little over a year now and it has become second nature and feels very natural to me, which is why I have decided to share it with the public.

In good spirit of me just having used the program to create this layout, I will be including the original file as the source element.

# Installation
1. Download the latest release from [here](https://github.com/Anderzenn/danish-ansi-windows/releases/latest) or the latest release in the sidebar
2. Extract to a place of your choosing
3. Run "Setup.exe"
4. Follow the prompts
5. **Restart your PC**
6. Select the layout from the language shelf
7. ???
8. Profit

(**note**: in some cases you have to go in and manually add the layout to the language shelf, the layout should be called `Dansk - ANSI <>\`)

# Uninstallation
If you have decided you want to uninstall the layout, then just simply remove it from any language in your language shelf, run the setup.exe again and it should ask if you wish to uninstall or repair. Choose uninstall and voilà, you have uninstalled it.

Step-by-step guide:
1. Remove the layout from all languages that might be using it as default (primary layout)
2. Run "Setup.exe"
3. Choose "Remove the keyboard layout."
4. Restart your pc
5. ???
6. Profit

# Updating
If I release an update, you will have to uninstall the layout first and then reinstall it following the installation steps.

# Usage
The main change is the location of <> and \, this is because when compared to ISO, ANSI is missing the key that on the Danish/Nordic layout features the <>\ key.

&lt; = 
`ctrl + alt + ,`

\> = 
`ctrl + alt + .`

\\ = 
`ctrl + alt + -`

# Layout
(Note: The pictures show the default <>\ key next to left shift, but on an actual ANSI keyboard it will not be there.)

Default
![image](https://user-images.githubusercontent.com/12025450/167323812-e926ee3a-3626-4920-bb1a-984dca2e1337.png)

AltGr (Ctrl + Alt)
![image](https://user-images.githubusercontent.com/12025450/167323841-c5fafb6a-79fe-4ec6-b049-a67b5e181e0b.png)

# Problem Solving
If you are having issues with the installation process, then make sure you do not have another language installed with the same name (dk_ansi), and also that you have .NET framework installed.

# Credits
All credit goes to Microsoft for creating their tool "The Microsoft Keyboard Layout Creator", which can be found [here](https://support.microsoft.com/en-us/topic/906c31e4-d5ea-7988-cb39-7b688880d7cb). Without this tool I would not have been able to create this keyboard layout.
