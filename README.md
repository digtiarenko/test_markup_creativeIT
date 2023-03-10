# test_markup_creativeIT

## 1. Project is bundled with Parcel, 
which allows us to split HTML file into partial (each for a section. e.g. footer). This technique is super convenient for maintainig
 and improving code. Also bundler alowws to split single CSS. So in result we have a pairs of HTML + CSS chunks, which is super easy to support.

## 2. Since the page is in Hebrew, 
a base direction rule RLT applied in HTML. I also declared the language of the document using the lang attribute. For the same reason use 'logical properties' when setting up your style: ie. use 'start' and 'end', rather than 'left' or 'right'.makes it much 
easier to localise your content in the future or include text with a different direction. the alignment of that content treats start as right, and end as left.

## 3. I divided all images in content, background and icons. 
Everything is optimized and reduced in size without damage for a quality. We saved at least 27% of total weight of graphic contetent. 
Icons are united in SVG-sprites. So our client is avoiding having to make a separate request for each icon. Whole page is only 2,25 MB. 
