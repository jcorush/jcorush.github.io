<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>My Academic Site</title>
<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  max-width: 900px;
  margin: auto;
}
.two-column {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
  align-items: center;
  padding: 20px 0;
}
img {
  width: 100%;
  height: auto;
  border-radius: 8px;
}
h1 {
  margin-bottom: 0;
}
h2 {
  margin-top: 5px;
  font-weight: normal;
  color: #555;
}
h3 {
  margin-top: 2px;
  font-weight: normal;
  color: #555;
}\h3 small {
  display: block;
  font-weight: normal;
  color: #555;
}
.single-column {
  padding: 20px 0;
}
/* Tabs */
.tab {
  overflow: hidden;
  border-bottom: 2px solid #ccc;
  margin-bottom: 20px;
}
.tab button {
  background-color: inherit;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 10px 20px;
  transition: 0.3s;
  font-size: 16px;
}
.tab button:hover {
  background-color: #ddd;
}
.tab button.active {
  background-color: #ccc;
}
.tabcontent {
  display: none;
  padding: 10px 0;
  border-top: none;
}
</style>
</head>
<body>

<section class="two-column">
  <div>
    <h1>Joel Corush</h1>
    <h3>Assistant Professor <br>Evolutionary Ichthyologist<br>Biology Department <br>Illinois Institute of Technology<br>Robert A. Pritzker Science Center<br>3105 South Dearborn Street, Room 182<br>Chicago, IL 60616<br>email: jcorush @ illinoistech.edu</h3>
  </div>
  <div>
    <img src="cover_photo" alt="Profile Photo" />
  </div>
</section>

<div class="tab">
  <button class="tablinks" onclick="openTab(event,'Education')">Education</button>
  <button class="tablinks" onclick="openTab(event,'Research')">Research</button>
  <button class="tablinks" onclick="openTab(event,'Contact')">Contact</button>
</div>

<div id="Education" class="tabcontent">
  <ul>
    <li>Postdoc - Illinois Natural History Survey at University of Illinois at Urbana-Champaign</li>
    <li>Postdoc - Wayne State University</li>
    <li>Ph.D. - Ecology and Evolutionary Biology - University of Tennessee - Knoxville</li>
    <li>B.A. - Biology - Drake University</li>
  </ul>
</div>

<div id="Research" class="tabcontent">
  <p>I use population genetics, phylogenetic comparative methods, and natural history to study trait evolution in fishes. My research focuses on how life-history traits—such as breeding behavior and migration patterns—shape population connectivity, movement across landscapes, and hybridization rates. I then explore how these traits evolved. Two major lines of research in my lab are: (1) the evolution of breeding behavior in North American minnows, and (2) the biogeography and life-history evolution of Indo-Pacific mudskippers.</p>
</div>

<div id="Contact" class="tabcontent">
  <p>Email: jcorush@illinoistech.edu</p>
</div>

<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}
document.getElementsByClassName("tablinks")[0].click();
</script>

</body>
</html>
