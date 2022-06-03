# cvescan
### Network vulnerability scanner

1. Install requirements:

v.1.0.7
```
sudo apt update && sudo apt install make nmap docker.io wkhtmltopdf python3 -y
```
v.1.0.8 GUI
```
sudo apt update && sudo apt install make nmap docker.io wkhtmltopdf python3 zenity shc -y
```

2. Usage:

v.1.0.7

Use terminal:
```
sudo chmod +x cvescan
```
```
sudo ./cvescan
```
v.1.0.8 GUI

```
sudo chmod +x CVESCAN_GUI
```

Double click or use terminal:

```
sudo ./CVESCAN_GUI
```


#### The scan result is saved in the directory /var/log/cvescan/


### Example:

![alt text](https://user-images.githubusercontent.com/37213906/171044652-25efb263-d5d6-459d-9d7c-40b13ac23551.png)
