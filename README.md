# Snip Artwork for OBS Browser

![image](https://user-images.githubusercontent.com/11992915/93876166-5163fc80-fd11-11ea-9606-e2c16cd8be53.png)

## Requirements
Snip: https://github.com/dlrudie/Snip

## First..
1. Launch `Snip.exe`

## Add title and artist
2. Click `Set Output Format` <br> ![image](https://user-images.githubusercontent.com/11992915/93877080-d4d21d80-fd12-11ea-8257-9c27cd566e5f.png)
1. Write Format <br> ![image](https://user-images.githubusercontent.com/11992915/93877089-d7347780-fd12-11ea-8efb-86c516ec18e6.png)
1. Add `Text (GDI+)` source to your OBS scene.
1. Enable `Read from file` and choose `Snip.txt` <br> ![image](https://user-images.githubusercontent.com/11992915/93876705-3b0a7080-fd12-11ea-9ffa-9a9b81d0911c.png)

## Add artwork
6. Enable Save `Snip_Artwork.jpg` <br> ![image](https://user-images.githubusercontent.com/11992915/93876265-87a17c00-fd11-11ea-9035-b318e5e85785.png)
1. Copy `snip_artwork.html` to `Snip_Artwork.jpg` dir
1. Add a `Browser` source to your scene.
1. Choose `snip_artwork.html` <br> ![image](https://user-images.githubusercontent.com/11992915/93876905-8c1a6480-fd12-11ea-97c2-412fc316699d.png)


```css
body { background-color: rgba(0, 0, 0, 0); overflow: hidden; }
img { border-radius: 100%; animation: spin 10s linear infinite; }
@keyframes spin {
	0% {transform: rotate(0deg);}
	100% {transform: rotate(360deg);}
}
```

## Tips

### Opacity
You can set an opacity from `Filters` -> `Color Collection`.

![image](https://user-images.githubusercontent.com/11992915/93851806-c15f8c00-fceb-11ea-8bd7-113728089dd5.png)

