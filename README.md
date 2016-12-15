# HTML5-and-CCS

<!-- I'm going to notetate all the things!-->

<!-- This is downloading/using a font that isn't something that is default. This is downloading the Google font Lobster-->
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">


<style>
  .red-text {
    color: red;
  }
<!-- Again a class that for headings. looks like you can have h1 through h6. Font-family sets the phone. When you place a second defualt font with the downloaded font, if a website can download the phone, it would switch to the default one.-->
  h2 {
    font-family: Lobster, Monospace;
  }
<!-- This creates a classs for a paragraphs-->
  p {
    font-size: 16px;
    font-family: Monospace;
  }
<!-- This creates a boarder. with the boarder-radius you can use % or pxs-->
  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }
<!-- This makes an image smaller -->
  .smaller-image {
    width: 100px;
  }
</style>
<!-- This is the heading-->
<h2 class="red-text">CatPhotoApp</h2>

<!-- This makes the phono the actual link-->
<p>Click <a href="#">here</a> for more cat photos.</p>

<!-- This is an-->
<a href="#"><img class="smaller-image thick-green-border" alt="A cute orange cat lying on its back. " src="https://bit.ly/fcc-relaxing-cat"></a>

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

<input type= "text">
