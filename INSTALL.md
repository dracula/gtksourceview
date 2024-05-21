### [GtkSourceView](https://wiki.gnome.org/Projects/GtkSourceView)

[GtkSourceView](https://wiki.gnome.org/Projects/GtkSourceView) is a GNOME library that provides syntax highlighting for [GNOME Builder](https://apps.gnome.org/Builder/) and [GNOME Text Editor](https://apps.gnome.org/TextEditor/).

#### Install using Git

 1. Clone the [`gtksourceview` repository](https://github.com/dracula/gtk):

    ```bash
    git clone https://github.com/dracula/gtksourceview.git
    ```

 2. Move into the cloned repository:

    ```bash
    cd ./gtksourceview
    ```

 3. Create the directory `gtksourceview-5/styles` if it does not exist in `$HOME/.local/share`:

    ```bash
    mkdir -p $HOME/.local/share/gtksourceview-5/styles
    ```

 4. Finally, create a symbolic link from the local repository to [GtkSourceView](https://wiki.gnome.org/Projects/GtkSourceView)’s styles folder:

    ```bash
    ln -s $PWD/dracula.xml $HOME/.local/share/gtksourceview-5/styles
    ```

#### Install manually

 1. Download the [`gtksourceview` archive](https://github.com/dracula/gtksourceview/archive/main.zip) and extract it.

 2. Create the directory `gtksourceview-5/styles` if it does not exist in `$HOME/.local/share`.

 3. Move the `dracula.xml` file from the extracted archive to [GtkSourceView](https://wiki.gnome.org/Projects/GtkSourceView)’s style folder `$HOME/.local/share/gtksourceview-5/styles`

#### Activating theme

1. Navigate to `GNOME Builder -> Preferences -> Appearance`, or `GNOME Text Editor -> Preferences -> Appearance`.
2. Select `Dracula` as the application theme.

If you do not see the `Dracula` in the theme overview, make sure that you have activated dark style in the application or in GNOME Shell.
