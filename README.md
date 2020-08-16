# Windows Practices 


## Windows terminal install and configure 


1. Install it 

    Open `microsoft Store`, Search `windows Terminal ` and download it  

2. Configure it 

    Open `Terminal` and click `setting` , and you will got `setting.json`. It's used for configure `Terminal` `keybind`, `colorscheme`, or others

```json


  "profiles":
    {
        "defaults":
        {
            // Put settings here that you want to apply to all profiles.
        },
        "list":
        [
            {
                // Make changes here to the cmd.exe profile.
                "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
                "name": "Command Prompt",
	"colorScheme": "Solarized Light",
                "commandline": "cmd.exe",
                "hidden": false
            },
            {
                "guid": "{58ad8b0c-3ef8-5f4d-bc6f-13e4c00f2530}",
                "hidden": false,
                "name": "Debian",
	"colorScheme": "Solarized Light",
                "source": "Windows.Terminal.Wsl"
            },
            {
                "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
                "hidden": false,
                "name": "Azure Cloud Shell",
	"colorScheme": "Solarized Light",
                "source": "Windows.Terminal.Azure"
            }
        ]
    },
```

