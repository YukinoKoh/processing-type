![Processing image](img/sample.png)

# Structure
- processing 
  - `sketch\_[letter].pde`: Processing code of each letter  
- js 
  - `processing_min.js`: Sister project of Processing designed for the web via [Processing.js](http://processingjs.org/)
- `index.html`: Type animation sample page 
- css
  - `style.css': css for `index.html`
- img
  - `sample.png`: image for README.md
- `LICENSE`
- `README.md`

# Usage
### To embed  
1. Put `sketch\_[letter].pde` under your directory

2. Add `processing\_min.js` in head of your html
```html
<script  type="text/javascript" src="js/processing_min.js"></script>
```

3. Add canvas object with *data-processing-sources* attribute where you want 
to embed in your html 
```html
<canvas 
    data-processing-sources="[path to sketch\_[letter].pde]">
</canvas>
```

#License
[MIT License](https://choosealicense.com/licenses/mit/) © [Yukino Kohmoto](http://yukinokoh.github.io/portfolio/)
