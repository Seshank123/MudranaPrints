MUDRANA PRINTS WEBSITE
======================
Open index.html in any browser. Keep the "images" folder next to index.html
(unzip the download first - do not open index.html from inside the zip).

FOLDER
  index.html                         the complete website (HTML, CSS and JavaScript)
  images/logo.png                    logo
  images/hero-printer.png            front-page background photo
  images/about-workshop.png          About section - large photo
  images/about-supplies.png          About section - small photo
  images/products/*.png              main photo of each service card (14 services)
  images/products/school-uniforms/   EXTRA photos of School Uniforms (uniform-1.png ... uniform-4.png)

CHANGE A PICTURE
  Replace the PNG with a new PNG that has the SAME FILE NAME.

"VIEW MORE" - SEVERAL PHOTOS FOR ONE PRODUCT
  Each product can have extra photos, kept in its OWN folder inside images/products/.
  The School Uniforms product already has 4 extra photos.
  To add extra photos to another product (example: Bags):
    1. create the folder      images/products/bags/   and put PNG photos in it
    2. open index.html, find   const MORE = {   and add
         BAG:["images/products/bags/bag-1.png", "images/products/bags/bag-2.png"],
    3. in the SERVICES list, add   more:MORE.BAG   to the Bags line
  A "View more" button then appears on that product's photo in its details window.
  To add more photos to School Uniforms: put the PNG in images/products/school-uniforms/
  and add its path to the UNIFORM list in  const MORE.

CHANGE TEXT, PHONE, EMAIL, SERVICES, FAQ, REVIEWS
  Open index.html in Notepad or VS Code. Labelled blocks near the top of the <script>:
  BUSINESS, MORE, SERVICES, HIGHLIGHTS, STATS, FAQS and REVIEWS.

TO PUT IT ONLINE
  Upload the whole folder (index.html + images) to your hosting.
