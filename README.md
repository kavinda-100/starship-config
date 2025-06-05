# StarShip - Cross-Shell-Prompt

## This is the reference configuration file of the [starship](https://starship.rs/) prompt

### The minimal, blazing-fast, and infinitely customizable prompt for any shell

---

1. Install Latest Version
   With Shell:

   ```bash
   curl -sS https://starship.rs/install.sh | sh
   ```

    Or with Homebrew:

    ```bash
    brew install starship
    ```

    Or with Winget:

    ```bash
    winget install starship
    ```

    Or with Chocolatey:

    ```bash
    choco install starship
    ```

2. Add the following line to your shell configuration file:

   **Bash** - Add the following to the end of ~/.bashrc:

    ```bash
     # ~/.bashrc
     eval "$(starship init bash)"
    ```

    **Zsh** - Add the following to the end of ~/.zshrc:

     ```bash
      # ~/.zshrc
      eval "$(starship init zsh)"
     ```

     **Powershell** - Add the following to the end of Microsoft.PowerShell_profile.ps1. You can check the location of this file by querying the $PROFILE variable in PowerShell. Typically the path is ~\Documents\PowerShell\Microsoft.PowerShell_profile.ps1 or ~/.config/powershell/Microsoft.PowerShell_profile.ps1 on -Nix.

     ```powershell
      Invoke-Expression (&starship init powershell)
     ```

> [!IMPORTANT]
> for most up-to-date details, please refer to the [starship documentation](https://starship.rs/guide/)

---

> [!IMPORTANT]
> After installing, you can customize the prompt by creating a configuration file at `~/.config/starship.toml`. The default my configuration file is available in this repository as `starship.toml`.

```bash
mkdir -p ~/.config && touch ~/.config/starship.toml
```

---

>[!Tip]
> In Windows, the configuration file is typically located >at `C:\Users\<YourUsername>\.config\starship.toml`
>If you don't have `starship.toml` file, you can create it manually or copy the default configuration file from this repository.

---

>[!Tip]
>Or You can get preset configuration files from the [starship presets](https://starship.rs/presets/).
