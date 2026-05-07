
Website: https://jaavid134.github.io/maxiplast/
2. Upload your photos

Click into the images/ folder
Click Add file → Upload files
Drag all your product photos in
Name them simply, no spaces — e.g:

  cuchillo.jpg
  cuchara.jpg
  tenedor.jpg
  bowl-ensalada.jpg
  bandeja-b2.jpg

Click Commit changes

3. Edit index.html to use the photos

Go back to your repo root, click index.html
Click the pencil icon (Edit)
Find a product card — you'll see a comment like:

  <!-- IMAGE: replace with <img src="images/cuchillo.jpg" …> -->

Delete the <svg class="psvg"…</svg> line below it
Paste this in its place:

html  <img src="images/cuchillo.jpg" alt="Cuchillo"
       style="width:100%;height:100%;object-fit:cover;">

Repeat for each product card
Click Commit changes
