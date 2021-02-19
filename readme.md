### Docker Ligth Image Demo

How to use this Docker image of Go Message?
```docker run -it --rm --name ligthdocker tonnytg/lightdocker```
<br />

### Make yourself? 
First clone this repo:
```git clone https://github.com/tonnytg/ligthdocker.git```

Edit main.go file
```vim main.go```

Build your image:
```docker build -t my/image .```

Run your app
```docker run -it --rm --name ligthdocker my/image```

