# Adding real photos

Every photo slot on the site is currently a dashed gray placeholder (a `.photo-placeholder`
div) labeled with what should go there. To add a real photo:

1. Compress it first at squoosh.app or tinypng.com (aim under 300KB).
2. Drop the file in this folder, e.g. `images/bathroom-before.jpg`.
3. In the relevant HTML file, replace the placeholder div:

   ```html
   <div class="photo-placeholder tall">Bathroom remodel — before...</div>
   ```

   with an image tag using the same descriptive text as `alt`:

   ```html
   <img src="images/bathroom-before.jpg" alt="Bathroom remodel before — Port Richey, FL handyman">
   ```

Send Claude the photo files (not screenshots of the current site) and this swap can be
done directly.
