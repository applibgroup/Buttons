# Neumorphism_Buttons

# Installation :

Install using npm inside pages directory

```npm init -y```

```npm i hmos-neumorphism ```

# Note :

Add this css snippet when passing input or button through slot .

```css
button, input{
    width: 100%;
    height: 100%;
    background-color:transparent;
    text-color: black;
}
```

# Button

<img src="sample_images/button.png" width="" height="">

Import:
```html
<element name='neubutton' src='../node_modules/hmos-neumorphism/button/button.hml'></element>
```

Usage:
```html
<neubutton icon="common/icons/heart.png" width="250px" height="60px" border="50px" onclick="buttonClick">
  <text>Button</text>
</neubutton>
```

# Buttons

<img src="sample_images/buttons.png" width="" height="">

Import:
```html
<element name='neubuttons' src='../node_modules/hmos-neumorphism/buttons/buttons.hml'></element>
```

Usage:
```html
<neubuttons  width="250px" height="60px" border="50px">
  <button slot="first">Left</button>
  <button slot="second">Right</button>
</neubuttons>
```

# Reference:

<a href="https://neumorphism.io/">neumorphism.io</a>

<a href="https://ismail9k.github.io/neomorphism/">ismail9k.github.io/neomorphism</a>
