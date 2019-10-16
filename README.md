Personal project for my different .dotfiles
===========================================

source .mydotfiles in your `.bashrc`:

```
echo -e '\nif [ -f "$HOME/.mydotfiles" ]; then\n  source "~/$HOME/.mydotfiles"\nfi' >> ~/.bashrc
```
