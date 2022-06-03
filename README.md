![изображение](https://user-images.githubusercontent.com/37213906/171910667-26869de9-3a05-4219-8fb1-d5b4a823d2f8.png)

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

Use terminal:
```
sudo chmod +x CVESCAN_GUI
```

Double click or use terminal:

```
sudo ./CVESCAN_GUI
```


#### The scan result is saved in pdf format in the /var/log/cvescan/ directory


### Example:

![изображение](https://user-images.githubusercontent.com/37213906/171044652-25efb263-d5d6-459d-9d7c-40b13ac23551.png)
