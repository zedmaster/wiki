# Como ripar do Youtube


## Linux


### youtube-dl

```
sudo apt-get install youtube-dl
```

Ripando para mp4 e qualidade low:

```
youtube-dl -f 18  --merge-output-format mp4 https://www.youtube.com/watch?v=sdfsdfsdfsdf
```


## uget


```
sudo add-apt-repository ppa:plushuang-tw/uget-stable
sudo apt-get update
sudo apt-get install uget aria2
```

```
uget-gtk
```
