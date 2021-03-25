
# Nice Tricks for GFM

These are short snippets for improving Readmes on GitHub.


### Clickable Summary
Markdown does not work inside the summary but inside the details tag.

```
<details>
<summary>Example **Summary** (👆 click)

Markdown works only after **two** lines
</summary>

Example Details *with* Markdown
</details>
```

<details>
<summary>Example **Summary** (👆 click)

Markdown works only after **two** lines
</summary>

Example Details *with* Markdown
</details>


### Right Aligned Figures
<img align="right" src="https://cloud.githubusercontent.com/assets/532272/21507867/3376e9fe-cc4a-11e6-9350-7ec4f680da36.gif">This Text appears on the left and floats around the image on the right.




### Warning / Info Boxes
<!-- 🔔📢🔌💡🔎📌🔑⚠⛔‼❌✔ℹ -->
```
> ⚠ **Warning** 
> Do not fly without enough fuel. 

> 🔔 **Attention** 
> This is important. 
```

It is important to have two spaces after the first line. Without two spaces, the blockquote will continue in the same line.

> ⚠ **Warning**  
> Do not fly without enough fuel. 

> 🔔 **Attention**  
> This is important. 


### Math Equations
There are Web-APIs that produce SVG images from TeX input.

```html
<img height="64" src="https://latex.codecogs.com/svg.latex?f_X(x)=\frac{1}{\sqrt{2\pi\sigma^2}}e^{-\frac{(x-\mu)^2}{2\sigma^2}}">

<img height="32" src="https://latex.codecogs.com/gif.latex?\dpi{200}\int\frac{1}{x}dx=\ln\left|x\right|+C">
```
The normal distribution can be expressed as

<img height="64" src="https://latex.codecogs.com/svg.latex?f_X(x)=\frac{1}{\sqrt{2\pi\sigma^2}}e^{-\frac{(x-\mu)^2}{2\sigma^2}}">


For inline euations, use `\textstyle` like in 
<img height="24" src="https://latex.codecogs.com/gif.latex?\dpi{200}\textstyle\int\frac{1}{x}dx=\ln\left|x\right|+C">



