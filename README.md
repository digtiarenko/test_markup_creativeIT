# test_markup_creativeIT

## 1 Project is bundled with Parcel,
which allows us to split the HTML file into partials (e.g., footer) for each section. This technique is super convenient for maintaining and improving the code. Additionally, the bundler allows us to split a single CSS file, resulting in pairs of HTML and CSS chunks, making it super easy to support.

## 2. Since the page is in Hebrew, 
a base direction rule RLT is applied to HTML. I also declared the language of the document using the lang attribute. For the same reason, we use 'logical properties' when setting up styles, such as using 'start' and 'end' instead of 'left' or 'right'. This approach makes it much easier to localize content in the future or include text with a different direction. The alignment of the content treats start as right and end as left.

## 3. To optimize the page, 
I divided all images into content, background, and icons. Everything is optimized and reduced in size without any quality damage. Saved at least 27% of the total weight of graphic content. Icons are united in SVG sprites, so browser doesn't have to make a separate request for each icon. The whole page is only 2.25 MB.

## 4. I used SCSS preprocessor, 
which allows us to use $variables and @mixins, which might be handy if the project has a mobile and tablet version. Still, under the hood, it allows us to use simple CSS if needed.

## 5. Lastly, I added some :hover effects to the page based on my opinion since there were none in Figma.
