# Basic instructions for regular updates
Text highlighted in **bold** indicates content that requires manual editing.

- Link to the latest workshop:
  - Search for "Latest COINE Workshop" in *index.html* and update the url and text follows this format:

<h3><a href="**Edit the URL that links to the workshop website**" target="_blank" class="link">The Latest COINE Workshop</a></h3>
<p>**Edit the text that appears on the webpage**</p>

- Add new item in post-proceedings series:
  - Add new block with the following format under <tbody> in *coine_workshop_series.html*:

<tr>
  <td>The 29th COINE workshop (<a href="**Edit the URL that links to the workshop website**" target="_blank">COINE **Year**</a>)</td>
  <td>**Location**</td>
  <td><a href="**Edit the URL that links to the AAMAS website**" target="_blank">AAMAS **Year**</a></td>
</tr>

- Add new item in book series:
  - Retrieve the book image from the Springer website and save it in the images/post_proceedings folder
  - Add new block with the following format under <div class="row gtr-200"> in *coine_book_series.html*:

<div class="col-6 col-12-small">
  <section class="proceedings-item">
    <a href="#"><img src="images/post_proceedings/**IMAGE_NAME**" style="width:100%;max-width:120px;float:left;margin-right:10px;" alt="" /></a>
    <p>Editors: **Editor1, Editor2, Editor3**<br/>
          **Edit book title**.<br/>
          Springer-Verlag, Lecture Notes in Artificial Intelligence, **Volume, Year**.
    </p>
    <a href="https://link.springer.com/book/10.1007/978-3-031-82039-7" target="_blank" class="special">Learn more</a>
  </section>
</div>
