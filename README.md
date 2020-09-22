# Snip Artwork for OBS Browser


	
![image](https://user-images.githubusercontent.com/11992915/93876166-5163fc80-fd11-11ea-9606-e2c16cd8be53.png)

## Requirements
Snip: https://github.com/dlrudie/Snip

## How to setup
1. Launch `Snip.exe`
1. Enable Save `Snip_Artwork.jpg` <br> ![image](https://user-images.githubusercontent.com/11992915/93876265-87a17c00-fd11-11ea-9035-b318e5e85785.png)
1. Copy `snip_artwork.html` to `Snip_Artwork.jpg` dir
1. Add a `Browser` source to your scene.
1. Choose `snip_artwork.html` <br> ![image](https://user-images.githubusercontent.com/11992915/93851587-5dd55e80-fceb-11ea-85d6-d81eda89abe3.png)

## Tips

### Opacity
You can set an opacity from `Filters` -> `Color Collection`.

![image](https://user-images.githubusercontent.com/11992915/93851806-c15f8c00-fceb-11ea-8bd7-113728089dd5.png)

### Spin artworks

```css
body { background-color: rgba(0, 0, 0, 0); overflow: hidden; }
img { border-radius: 100%; animation: spin 10s linear infinite; }
@keyframes spin {
	0% {transform: rotate(0deg);}
	100% {transform: rotate(360deg);}
}
```
