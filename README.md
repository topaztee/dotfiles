# dotfiles

 > run ./dotfiles_setup.sh to set up dotfiles on new machine.
 
 As a convention, dotfiles are usually stored in the home directory. The script creates a softlink between $HOME and the the dotfiles directory.
 Change directory to $HOME and run ls -la $HOME, you will be able to visually see all the created references to $dir.
 In the $HOME directory, the dotfile references will be shown with an arrow pointing to the original copy.