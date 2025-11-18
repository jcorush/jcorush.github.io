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
  max-width: 1200px;
  margin: auto;
  display: flex;
}
/* Sidebar for tabs */
.tab {
  display: flex;
  flex-direction: column;
  width: 25%;
  border-right: 2px solid #ccc;
  padding: 20px;
  box-sizing: border-box;
}
.tab .profile {
  text-align: center;
  margin-bottom: 20px;
}
.tab .profile img {
  width: 150px;
  border-radius: 8px;
  margin-bottom: 10px;
}
.tab .profile h1 {
  margin: 2px 0;
  font-weight: normal;
  color: #555;
}
.tab button {
  background-color: inherit;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 10px;
  margin-bottom: 5px;
  text-align: left;
  font-size: 16px;
}
.tab button:hover {
  background-color: #ddd;
}
.tab button.active {
  background-color: #ccc;
}
/* Main content */
.main-content {
  width: 75%;
  padding: 20px;
  box-sizing: border-box;
}
</style>
</head>
<body>

<div class="tab">
  <div class="profile">
    <img src="cover_photo" alt="Profile Photo" />
    <h1>Joel Corush</h1>
    <h3> Assistant Professor</h3>
    <h3> Evolutionary Ichthyologist</h3>

  </div>
  <button class="tablinks" onclick="openTab(event,'About me')">About me</button>
  <button class="tablinks" onclick="openTab(event,'Research')">Research</button>
  <button class="tablinks" onclick="openTab(event,'Publications')">Publications</button>
  <button class="tablinks" onclick="openTab(event,'People')">People</button>
  <button class="tablinks" onclick="openTab(event,'PhD')">Ph.D Opportunities</button>
  <button class="tablinks" onclick="openTab(event,'Teaching')">Teaching</button>

</div>

<div class="main-content">

<div id="About me" class="tabcontent">
  <h2>Joel Corush </h2>
    <h3>Assistant Professor <br>Evolutionary Ichthyologist<br>Biology Department <br>Illinois Institute of Technology<br>Robert A. Pritzker Science Center<br>3105 South Dearborn Street, Room 182<br>Chicago, IL 60616<br>email: jcorush@illinoistech.edu</h3>
  <br><br>
  <h3>Education</h3>
     <ul>
    <li>Postdoc - Illinois Natural History Survey at University of Illinois at Urbana-Champaign</li>
    <li>Postdoc - Wayne State University</li>
    <li>Ph.D. - Ecology and Evolutionary Biology - University of Tennessee - Knoxville</li>
    <li>B.A. - Biology - Drake University</li>
  </ul>
</div>


<div id="Research" class="tabcontent">
  <p>I use population genetics, phylogenetic comparative methods, and natural history to study trait evolution in fishes. My research focuses on how life-history traits—such as breeding behavior and migration patterns—shape population connectivity, movement across landscapes, and hybridization rates. I then explore how these traits evolved. Two major lines of research in my lab are: (1) the evolution of breeding behavior in North American minnows, and (2) the biogeography and life-history evolution of Indo-Pacific mudskippers.</p>
  
  <!-- New two-column section -->
  <div style="display: flex; gap: 20px; margin-top: 20px;">
    <div style="flex: 1;"> <!-- photo column -->
    <img src="Minnow_PCM_tree.png" alt="Minnow research" style="width:100%; border-radius:8px;">
    </div>
    <div style="flex: 3; display: flex; align-items: center;"> <!-- text column -->
    <p>I am interested in understanding how complex nesting behaviors evolve and the evolutionary consequences of this reproductive strategy. I use phylogenetic comparative methods to examine if hybridization is associated with particular breeding behaviors.</p>
     </div>
  </div>
</div>
  
<div id="Publications" class="tabcontent">
  <p>For a full list of publications see my <a href="https://scholar.google.com/citations?user=Xh3zefgAAAAJ&hl=en&oi=ao.html" title="Google Scholar page">Google Scholar page</a></p>
  <p>Select publications:</p>
  <ul>
    <li>Corush, J. B., Cucalón, R. V., Metzke, B. A., Tan, M., & Davis, M. A. (2025). Pleistocene glaciation and Anthropocene fragmentation influence genetic variation in the Illinois state–listed mottled sculpin (Cottus bairdii). Environmental Biology of Fishes, 1-18.</li>
    <li>Corush, J. B. (2024). Nest-Associating Minnows Prefer Occupying Longear Sunfish Nests Over Green Sunfish Nests. Northeastern Naturalist, 31(4), 479-487.</li>
    <li>Cucalón, R. V., Corush, J. B., Niemiller, M. L., Curtis, A. N., Hart, P. B., Kuhajda, B. R., ... & Tan, M. (2024). Population genomics and mitochondrial DNA reveal cryptic diversity in North American Spring Cavefishes (Amblyopsidae, Forbesichthys). Conservation Genetics, 25(6), 1283-1301.</li>
    <li>Corush, J. B., Pierson, T. W., Shiao, J. C., Katayama, Y., Zhang, J., & Fitzpatrick, B. M. (2022). Amphibious mudskipper populations are genetically connected along coastlines, but differentiated across water. Journal of Biogeography, 49(4), 767-779.</li>
    <li>Corush, J. B., Fitzpatrick, B. M., Wolfe, E. L., & Keck, B. P. (2021). Breeding behaviour predicts patterns of natural hybridization in North American minnows (Cyprinidae). Journal of Evolutionary Biology, 34(3), 486-500.</li>
    <li>Corush, J. B. (2019). Evolutionary patterns of diadromy in fishes: more than a transitional state between marine and freshwater. BMC Evolutionary Biology, 19(1), 168.</li>
    <li>Fitzpatrick, B. M., Ryan, M. E., Johnson, J. R., Corush, J., & Carter, E. T. (2015). Hybridization and the species problem in conservation. Current Zoology, 61(1), 206-216.</li>
  </ul>
</div>

<div id="People" class="tabcontent">
  <p>Current lab members: </p>
  <ul>
    <li>P.R. - Masters Student </li>
     <ul>
         <li>P.R. Joined the lab in fall 2025. </li>
     </ul>  
  </ul>
</div>

<div id="PhD" class="tabcontent">
  <p>I am recruting a Ph.D. (or Masters-to-Ph.D.) students to join my lab in Illinois Institute of Technology's Biology department starting Fall 2026!</p>
   <br><br>
  <p>I am open to students interested in a wide range of topics related to evolutionary biology, fish trait evolution, comparative phylogenetic methods, and population genetics. My lab uses a combination of molecular, analytical, and natural history methods. Some of the systems my lab  focus on include:<br>
  1) Hybridization and breeding behavior evolution in North American minnows,<br>
  2) Biogeography and amphibious behavior evolution in mudskippers,<br>
  3) Invasive round goby population dynamics in the Great Lakes region.<br></p>
    <br><br>
  <p>IIT is in the heart of Chicago and the historic Bronzeville neighborhood. The Biology department is located a short walk from L stops on the Red and Green lines.  My lab also has an affilieation with the Field Museums allowing access to collection and molecaulr lab space.</p>  
  <p>If you are interested in the above topics (in fishes or other organisms), or in topics related to my previously published papers, please reach out with a brief description of your interests and a CV.</p>
</div>

<div id="Teaching" class="tabcontent">
  <p>Teaching <br></p>
    <li> Illinois Institute of Technology</li>
  <ul>
    <li>Molecular Biology ((BIOL 515) - Fall 2025</li>
    <li>Urban Evology ((BIOL 200) - Spring 2026</li>
  </ul> 
  <li>University Of Illinois6</li>
  <ul>
    <li>-Conservation of ‘extinct’ species (IB546) - graduate seminar. </li>
    <li>--Phylogenetic Comparative Methods (IB546) - graduate seminar. (co-instructer) </li>
  </ul>
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
