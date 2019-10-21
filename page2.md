<h1>Page 2</h1>
<p>
  <a href="index.html">Home</a> | <a href="page3.html">Page 3</a>
</p>

<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */

.column {
  float: left;
  width: 50%;
  padding: 10px;
 /* height: 300px; Should be removed. Only for demonstration */
}

/* Clear floats after the columns */

.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>

<h2>Two Equal Columns</h2>


<div class="row">
  <div class="column" style="background-color:#aaa;">
    <h2>Column 1</h2>
    <p><img src="https://upload.wikimedia.org/wikipedia/commons/6/60/Giraffe-solo_Koure-NIGER.jpg" /></p>
  </div>
  <div class="column" style="background-color:#bbb;">
    <h2>Column 2</h2>
    <p>The West African giraffe (G. c. peralta) is endemic to south-western Niger.[24] This animal has a lighter pelage than other subspecies,[40]:322 with red lobe-shaped blotches that reach below the hocks. The ossicones are more erect than in other subspecies and males have well-developed median lumps.[33]:52–53 It is the most endangered subspecies within Giraffa, with 400 individuals remaining in the wild.[24] Giraffes in Cameroon were formerly believed to belong to this species, but are actually G. c. antiquorum.[32] This error resulted in some confusion over its status in zoos, but in 2007, it was established that all "G. c. peralta" kept in European zoos actually are G. c. antiquorum. The same 2007 study found that The West African giraffe was more closely related to the Rothschild's giraffe than the Kordofan and its ancestor may have migrated from eastern to northern Africa and then to its current range with the development of the Sahara Desert. At its largest, Lake Chad may have acted as a barrier between West African and Kordofan giraffes during the Holocene (before 5000 BC).[32]</p>
  </div>
</div>
<div style="clear:both;"></div>
