# nautilus-pyextensions
Automatically exported from code.google.com/p/giuspen-nautilus-pyextensions

## manual install

in order to manually install a python extension to nemo (or caja or nautilus):

1) install the package “nemo-python” (or “python-caja”or “python-nautilus”)

terminal sudo apt install nemo-python

2) enter in the home directory, press ctrl+h to see the hidden files, enter in the folder “.local/share” and then create a folder named “nemo-python” (ctrl+shift+n, “caja-python” for caja, “nautilus-python” for nautilus) then in nemo-python create a folder “extensions”

3) download the python file (“.py”) and put it in the directory “~/.local/share/nemo-python/extensions” just created

4) put the following in the terminal (to restart nemo)

terminal killall nemo
