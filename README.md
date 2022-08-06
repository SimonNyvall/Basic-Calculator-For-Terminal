# Basic-Calculator-For-Terminal [![Codacy Security Scan](https://github.com/SimonNyvall/Basic-Calculator-For-Turminal/actions/workflows/codacy.yml/badge.svg)](https://github.com/SimonNyvall/Basic-Calculator-For-Turminal/actions/workflows/codacy.yml)

A very basic calculator for the terminal that is using the bc ( basic calculator ) in the /bin directory. A quicker way to access a calculator while working in a terminal window.

## Useage
![Screenshot from 2022-08-06 10-54-48](https://user-images.githubusercontent.com/50596493/183242203-dd57187b-ba79-4d95-be7d-99c8020f9a3d.png)

You can of course just pipe the bc command to a string in the terminal directly, but this is more fun. :)
```
echo "2+2" | bc
```
## Install
Clone the repo and use the **mv** or **cp** command to move the file to the /bin directory. Be sure to remove the .sh at the end of the file.
```
sudo mv ~/.../Basic-Calculator-For-Terminal/c.sh /bin
```
