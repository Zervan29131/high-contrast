<h1 align='center'>high-contrast Theme For Typora</h1>

<p align="center">
    <a href="https://github.com/Zervan29131/high-contrast/blob/main/Readme.md
    ">简体中文</a>
    |
    English
</p>
<p align="center">
  <img src="https://img.shields.io/github/downloads/Zervan29131/high-contrast/total?labelColor=grey&color=blue" alt="Downloads">
  <img src="https://img.shields.io/github/v/release/Zervan29131/high-contrast?labelColor=grey&color=red" alt="Release">
  <img src="https://img.shields.io/github/license/Zervan29131/high-contrast" alt="License">
  <img src="https://img.shields.io/github/stars/Zervan29131/high-contrast" alt="Stars">
  <img src="https://img.shields.io/github/issues/Zervan29131/high-contrast?label=Issues" alt="Issues">
  <img src="https://img.shields.io/github/last-commit/Zervan29131/high-contrast?label=Last%20Commit" alt="Last Commit">
</p>


## **1. Overview**


> [!tip]
> **Here are two articles using the high-contrast theme, click to see detailed theme effect demonstrations**
>
> 1. **[high-contrast](https://bin-sites.pages.dev/high-contrast)**
> 2. **[Computer Networks](https://bin-sites.pages.dev/net)**

---

![image-20250108140354139](https://s2.loli.net/2025/01/08/fNQF1ZCOgGydEUL.png)

![image-20250108140529374](https://s2.loli.net/2025/01/08/aMkKwdmVuTCtW4G.png)

![image-20250119102419998](https://s2.loli.net/2025/01/19/4jotBCzeDdlAwfF.png)

<details><summary><kbd>Expand to see more screenshots</kbd></summary>
  <img src="https://s2.loli.net/2025/01/08/Ir1mgZCto4YS6lj.png"></br>
  <img src="https://s2.loli.net/2025/03/04/YzmsQOAFJ2UkpC7.png"></br>
  <img src="https://s2.loli.net/2025/01/08/cAgBOqFoCMYE8S6.png"></br>
	Integrated menu interface
  <img src="https://s2.loli.net/2025/01/08/QF2UA9zPOW5X6ji.png"></br>
</details>

---

## 2. How to Use

### 2.1 Download Files

> 1. Download the [theme file package](https://github.com/Zervan29131/high-contrast/releases)
> 2. In Typora, select File → Preferences → Appearance → Open Theme Folder
> 3. Extract the downloaded package, paste the **CSS files** and **folders** into Typora's theme folder (themes)
> 4. Restart Typora and switch the theme in the menu bar, and you're done
>
> The advantage of this method is that you download fewer files, containing only the necessary theme files. The disadvantage is that it's more complicated, and if you want to update later, you'll need to download and replace the files again.

### 2.2 Clone

> [!caution]
>
> 1. Find Typora's theme folder (themes) as mentioned above, and open a terminal in this folder
>
> 2. **To avoid cloning irrelevant files from other branches, please make sure to use the command below!! Otherwise, you'll have to download for a long time** (The project is forked from the official repository, and the commit history includes records from the gh-pages branch)
>
>    ```shell
>    git clone --single-branch https://github.com/Zervan29131/high-contrast.git
>    ```
>
> The advantage of this method is that it's more convenient. For future updates, you only need to use the `git pull` command to get the latest commits. The disadvantage is that cloning will download all the project files, including some unnecessary md files, etc.

---

## 3. About Customization

If you want to add your own styles, it's not recommended to modify the `high-contrast.css` file directly.

You can create a new `high-contrast.user.css` file in the same directory as `high-contrast.css`, and put your styles in this file. It has higher priority, and when you update later, you only need to update `high-contrast.css` without overriding your styles.

If `high-contrast.user.css` doesn't work, you may need to add `!important` to increase priority.

## **4. About Fonts**

Default fonts are set at the beginning of the `high-contrast.css` file, which you can modify as needed. Font files are in the [fonts](https://github.com/Zervan29131/high-contrast/tree/high-contrast/high-contrast/fonts) folder.
![](https://github.com/user-attachments/assets/ab75260f-cff0-43b7-b8e5-dfea38e8525c)

---

## **5. Background Image**

> [!important]
>
> Background images are in the `high-contrast/img` folder. There are several prepared images in the folder, and you can also add your own images (preferably with transparent backgrounds). Then search for `background-image` in the CSS file to find the code below and replace the image path:
>
> ```css
> content {
>      background-color: transparent;
>      /* You can replace the image here, or comment out this entire section if you don't want to display it */
>      background-image: url('./high-contrast/img/bg.gif');
>      background-position: 100% 100%;
>      background-repeat: no-repeat;
>      background-size: 100px auto; /* Adjust the image display size */
>      transition: background-image .5s ease-in-out, background-size .5s ease-in-out
> }
> ```
>
> <img src="https://s2.loli.net/2025/03/05/7Ds8SCmvWnkwraM.png" style="zoom: 50%;" />

---

## 6. Other

<img align='right' src="https://s2.loli.net/2025/01/04/zt7O3daMLDC5EHW.png" alt="Like" />⭐ If you like this theme, please give it a star, thank you! 🙏

✅ The theme works best in integrated mode ✨

❓ If you have any questions, you can ask in [Issues](https://github.com/Zervan29131/high-contrast/issues). All kinds of feedback are welcome.

📄 The [docs](https://github.com/Zervan29131/high-contrast/tree/high-contrast/docs) folder contains markdown files of sample articles 📄

🖼️ The [img](https://github.com/Zervan29131/high-contrast/tree/high-contrast/high-contrast/img) folder contains background images for the theme. If you don't need them, you can delete them directly.

[translated by AI]