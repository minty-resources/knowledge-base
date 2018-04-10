* **How-to: make terminal tab-completion case-insensitive**  
  `echo set completion-ignore-case on | sudo tee -a /etc/inputrc`

* **How-to: add launcher for application to Main Menu in GNOME-compliant desktop environments**
  Add a desktop entry by creating a file named `application_name.desktop` in `~/.local/share/applications` with the following content:
  ```
    [Desktop Entry]
    Type=Application
    Name=application_name
    Icon=application_icon_path
    Exec=executable_path
  ```  
