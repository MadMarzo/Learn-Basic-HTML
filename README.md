# Learn-Basic-HTML
I'm now slogging along the freecodecamp.org learning material

<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>
  
  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
  
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <label for="indoor">
      <input id="indoor" value="indoor" type="radio" name="indoor-outdoor"> Indoor
      </label>
    <label>
      <input id="outdoor" value="outdoor" type="radio" name="indoor-outdoor"> Outdoor
      </label>
      <br>
    <label>
      <input id="loving" value="loving" type="checkbox" name="personality"> Loving
      </label>
    <label>
      <input id="lazy" value="lazy" type="checkbox" name="personality"> Lazy</label>
    <label>
      <input id="energetic" value="energetic" type="checkbox" name="personality"> Energetic</label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>
