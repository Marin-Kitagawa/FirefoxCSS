# FirefoxCSS

`userChrome.css` is a mixture of configs from [OneJaredNewman](https://github.com/OneJaredNewman/firefoxcss/blob/main/userChrome.css) and from [r/vdyn](https://www.reddit.com/r/FirefoxCSS/comments/uldl0q/a_minimal_ui_w_autohiding_tree_style_tabs/) via [pastebin_userChrome.css](https://pastebin.com/raw/hAS9ThW2)

`Tree Style Tab` css is taken from config of `u/vdyn` via [pastebin_tree_style_tab.css](https://pastebin.com/raw/12gq6RGV)

They both contain my own modifications.

The background is specific for Dark theme in Firefox

Also, I use IBM Plex Sans (installed locally) for the tab labels. Using the below one for the same font changes the indent. I changed the indent so that the children hides from the minimum sidebar width view.

```css
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap');
```

The design will look like the image below. 
Note: Profile picture is present. I didn't use CSS to hide the profile picture.

## On hover
![image](https://github.com/Marin-Kitagawa/FirefoxCSS/assets/49131888/8385aa2f-78cd-4a4a-823b-bd1ef334f37f)

## When collapsed (mouse not on the sidebar)
![image](https://github.com/Marin-Kitagawa/FirefoxCSS/assets/49131888/f69cc143-8719-4b78-9ac4-69c3e527f2e0)
