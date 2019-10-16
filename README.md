Personal project for my different .dotfiles
===========================================

## Usage

Clone this to a known location (i.e., `$HOME/dev/projects/mydotfiles`)

Then source mydotfiles in your `.bashrc`:

```
echo -e 'MYDOTFILESDIR="$HOME/dev/projects/mydotfiles"\nif [ -f "$MYDOTFILESDIR/src/mydotfiles" ]; then\n  source "$MYDOTFILESDIR/src/mydotfiles"\nfi' >> ~/.bashrc
```
