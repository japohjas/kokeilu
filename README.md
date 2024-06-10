## flatpak vscode (NixOS)

### To make the Integrated Terminal automatically use the host system's shell, you can add this to the settings:
### ~/.var/app/com.visualstudio.code/config/Code/User/settings.json

```console
{
  "terminal.integrated.defaultProfile.linux": "bash",
  "terminal.integrated.profiles.linux": {
    "bash": {
      "path": "host-spawn",
      "args": ["bash"]
    }
  }
}
```

### Setting Git Username and Email:
### ~/gitconfig

```console
[user]
	email = "youremail@yourdomain.com"
	name = "Your Name"
```
