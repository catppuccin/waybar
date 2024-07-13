<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/Alexays/Waybar">Waybar</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/waybar/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/waybar?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/waybar/issues"><img src="https://img.shields.io/github/issues/catppuccin/waybar?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/waybar/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/waybar?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
  <img src="assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha.webp"/>
</details>

## Usage

1. Download the file with your desired flavor e.g. `mocha.css` (to be found in the [release](https://github.com/catppuccin/waybar/releases/latest) or after cloning the repository)
2. Copy it into your waybar config e.g. `~/.config/waybar/`
3. Include the file at the top of your `style.css`
   ```css 
   @import "<flavor>.css";
   ```
4. Use the colors in your Waybar `style.css`. Waybar uses [GTK3 CSS](https://docs.gtk.org/gtk3/css-overview.html#colors).
   ```css
   * {
     /* reference the color by using @color-name */
     color: @text;
   }
  
   window#waybar {
     /* you can also GTK3 CSS functions! */
     background-color: shade(@base, 0.9);
     border: 2px solid alpha(@crust, 0.3);
   }
   ```

## 🙋 FAQ

-	Q: **_"Waybar doesn't work with the colors"_**\
	A: Make sure you included the file in the right place and you are using `@COLOR`
- Q: **_"How can I make the bar look like the preview image?"_**\
  A: Here's [the waybar config](https://github.com/rubyowo/dotfiles/tree/f925cf8e3461420a21b6dc8b8ad1190107b0cc56/config/waybar) for the preview image.
## 💝 Thanks to

- [rubyowo](https://github.com/rubyowo)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
