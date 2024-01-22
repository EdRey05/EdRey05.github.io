<h1 class="center-text"> Data Science Portfolio </h1> 
<hr>

<h2 class="center-text"> Patient survival analysis by Kaplan-Meier estimates </h2>

<div class="two-columns">
  <div class="left-column-50">
    <p><strong> Summary </strong></p>
    <p class="justify-text"> Coming soon!. </p>
  </div>   
  <div class="right-column-50">
    <!--<img src="Images_GIFs_Videos/Streamlit_Projects_003.gif" alt="Streamlit Projects GIF" />-->
  </div>
</div>
<details><summary markdown="span"><strong> Expand this to read more... </strong></summary>
  <p><strong> More Context </strong></p>
  <p> A </p>
  <div class="two-columns">
      <div class="left-column-50">
          <p class="justify-text"><strong> Problems </strong></p>
          <ul> 
              <li class="justify-text">A. </li>
              <li class="justify-text">B. </li>
              <li class="justify-text">C. </li>
              <li class="justify-text">D. </li>
              <li class="justify-text">E. </li>
              <li class="justify-text">F. </li>
          </ul>
      </div>
      <div class="right-column-50">
          <p class="justify-text"><strong> Solutions </strong></p>
          <ul> 
              <li class="justify-text">A. </li>
              <li class="justify-text">B. </li>
              <li class="justify-text">C. </li>
              <li class="justify-text">D. </li>
              <li class="justify-text">E. </li>
          </ul>
      </div>
  </div>
  <p><strong> Check the Streamlit tool I made here: <a href="https://github.com/EdRey05/Streamlit_projects/tree/main/003_KM_plotter">Demo_KM_plotter</a></strong></p>
</details>
<br>
<hr>

<h2 class="center-text"> Gene expression analysis using CCLE/DepMap data </h2>

<div class="two-columns">
  <div class="left-column-50">
    <p><strong> Summary </strong></p>
    <p class="justify-text"> Coming soon!. </p>
  </div>
  <div class="right-column-50">
    <!--<img src="Images_GIFs_Videos/Streamlit_Projects_001.gif" alt="Streamlit Projects GIF" />-->
  </div>
</div>
<details><summary markdown="span"><strong> Expand this to read more... </strong></summary>
  <p><strong> More Context </strong></p>
  <p> A </p>
  <div class="two-columns">
      <div class="left-column-50">
          <p class="justify-text"><strong> Problems </strong></p>
          <ul> 
              <li class="justify-text">A. </li>
              <li class="justify-text">B. </li>
              <li class="justify-text">C. </li>
              <li class="justify-text">D. </li>
              <li class="justify-text">E. </li>
              <li class="justify-text">F. </li>
          </ul>
      </div>
      <div class="right-column-50">
          <p class="justify-text"><strong> Solutions </strong></p>
          <ul> 
              <li class="justify-text">A. </li>
              <li class="justify-text">B. </li>
              <li class="justify-text">C. </li>
              <li class="justify-text">D. </li>
              <li class="justify-text">E. </li>
          </ul>
      </div>
  </div>
  <p><strong> Check the Streamlit tool I made here: <a href="https://github.com/EdRey05/Streamlit_projects/tree/main/001_RNA_expression_DepMap">Demo_RNA_DepMap</a></strong></p>
</details>
<br>
<hr>

<h2 class="center-text"> Search for cancer-specific protein interactions by Proximity Ligation Assays </h2>

<div class="two-columns">
  <div class="left-column-50">
    <p><strong> Summary </strong></p>
    <p class="justify-text"> As part of my Ph.D. project, I used <strong>PLA assays</strong> to identify proteins that <strong>
                            interact only with mutant receptors</strong> present in thyroid cancers, and <strong>not with normal 
                            receptors</strong> present in healthy cells. <br><br>
                            For this purpose, I <strong>developed a full workflow: from automated imaging, to image processing and 
                            quantification in ImageJ/Fiji</strong>. Due to the large number of images acquired, I wrote <strong>Python 
                            scripts</strong> to <strong>automate</strong> some steps of the workflow or speed up others. <br><br>
                            Using these tools, I was able to <strong>identify 2 protein candidates</strong> that showed the behavior 
                            of interest (see figure for CRK). These and future findings using my workflow provide valuable insights
                            that can be translated into <strong>therapeutic strategies</strong>.
    </p> 
  </div>
  <div class="right-column-50">
    <img src="https://github.com/EdRey05/EdRey05.github.io/assets/62916582/8fad7857-27a1-4ee4-a980-3bce32a09ece" alt="CRK Dot plot" />
  </div>
</div>
<details><summary markdown="span"><strong> Expand this to read more... </strong></summary>
  <p><strong> More Context </strong></p>
  <p class="justify-text"> Based on research and information provided by collaborators who perform PLA experiments, I carried out several 
      <strong>small-scale tests</strong>. However, I found out that due to our conditions (antibodies, cell lines, treatments), there was 
      noticeable <strong>variability and background signal</strong> such that larger sample sizes would be required (first I tested <50 
      images of individual cells). In addition, I observed that confocal resolution was not essential to ensure good results and thus 
      evaluated other options. Finally, I decided to use the <strong>EVOS M7000</strong> imager (Thermo Fisher) which has automated 
      imaging capabilities and decent resolution of PLA objects at 40x magnification. <br>
  </p>
  <div class="two-columns">
    <div class="left-column-35">
      <br>
      <p class="justify-text"> Here I illustrate the workflow I generated (→), including the extra steps required due to the <strong>large 
                              number of images</strong> that I acquired with the EVOS imager. <br><br>
                              However, that brought several <strong>complications </strong> since my lab used to -mostly- do <strong>manual 
                              experiment analysis</strong> for small-scale experiments, which was very time consuming. Thus, I developed 
                              <strong>data-solutions</strong> for as many stages as I could (<strong>all with an * symbol before their name
                              </strong>).
      </p>
    </div>
    <div class="right-column-65">
      <img src="https://github.com/EdRey05/EdRey05.github.io/assets/62916582/fa82a60c-6108-4e50-a8f3-67d55b09ae35" alt="PLA Workflow" />    
    </div>
  </div>
  <br>
  <div class="two-columns">
      <div class="left-column-50">
          <p class="justify-text"><strong> Problems </strong></p>
          <ul> 
              <li class="justify-text">The imager saved the raw images as <strong>single-channel, single-slice</strong> images instead of 
                                      hyperstacks. This provided 12 images instead of 1. </li>
              <li class="justify-text">I acquired <strong>300+ hyperstacks/fields of view (FOVs)</strong>, which was too many for manual
                                      review. </li>
              <li class="justify-text">All FOVs requied <strong>pre-processing</strong> before quantification (<strong>Z-projection and 
                                      background subtraction</strong>). </li>
              <li class="justify-text">We needed to <strong>manually draw and save two .roi files</strong> for each cell to be quantified 
                                      (100-500 per experimental group). </li>
              <li class="justify-text">For the quantification, each big FOV required to be split, the <strong>PLA channel to be isolated 
                                      and thresholded</strong>. Here, different pre-set methods are offered within ImageJ/Fiji, but produce
                                      different results depending on the input images and features. </li>
              <li class="justify-text">The quantification <strong>results needed to be reviewed</strong> to evaluate whether the thresholding
                                      and object detection parameters were appropriate. These sometimes needed to be slightly adjusted 
                                      for each experiment to produce the best results. </li>
          </ul>
      </div>
      <div class="right-column-50">
          <p class="justify-text"><strong> Solutions </strong></p>
          <ul> 
              <li class="justify-text">I wrote a <strong>script to merge output images to hyperstacks</strong> in ImageJ/Fiji by analyzing the 
                                      output image file name which contained cues about the FOV, slice, and channel numbers. </li>
              <li class="justify-text">I wrote a <strong>script for grid stitching</strong> in ImageJ/Fiji, to produce 10 big FOVs per 
                                      experimental group. This was much more manageable and still easy to manually navigate and review. </li>
              <li class="justify-text">I wrote a <strong>script for pre-processing</strong> in ImageJ/Fiji, to Z-project and apply background 
                                       subtraction. </li>
              <li class="justify-text">Due to time constraints, I could not implement a solution to identify the cells/areas of interest and
                                      draw the contours for the .roi files. However, I wrote <strong>3 scripts to save and handle the areas
                                      </strong> in ImageJ/Fiji, which significantly speeded up the process. </li>
              <li class="justify-text">I wrote a <strong>script for quantification</strong> in ImageJ/Fiji that allows the user to select the
                                      thresholding method to use (methods panel and/or Find Maxima plug-in). Also, the user can enter the 
                                      parameters for PLA object detection (size, circularity). </li>
              <li class="justify-text">I made a <strong>Streamlit data app to summarize quantification outputs</strong>. The app automates the 
                                      generation of Power Point presentations with images and object count results. </li>
          </ul>
      </div>
  </div>
  <div class="two-columns">
      <div class="left-column-50">
          <p class="justify-text"><strong> Results </strong></p>
            <ol> 
              <li class="justify-text">I consolidated my merge, stitch, and pre-process scripts into a single script that takes few initial 
                  parameters and automates these steps by chaining their inputs and outputs (<strong><a href="https://github.com/EdRey05/Resources_for_Mulligan_Lab/blob/main/Tools%20for%20students/Eduardo%20Reyes/04-Image_Processing_SYTTMZ_automated_PLA.py">See script</a></strong>). </li>
              <li class="justify-text">The only manual parts left are to select the areas (cells) of interest, and the analysis of the results
                  in GraphPad prism. Everything else has been succesfully automated, most scripts take several <strong>input parameters</strong> 
                  that allow <strong>reusability</strong> and some other parts of the code are <strong>flexible enough for fine-tunning</strong> 
                  (<strong>more/less channels, slices, FOVs, areas, etc.</strong>). </li>
              <li class="justify-text">Approximately <strong>10,000 images</strong> of individual cells were analyzed (<strong>6 different 
                  interactions, 7 experimental groups each</strong>). </li>
              <li class="justify-text">This box plot (→) has the <strong>same data as the dot plot above</strong>, but shows the statistical 
                  analysis results and the dotted line is the additional threshold I used in my experiments (20 normalized puncta per cell) to 
                  consider a real interaction result given the background signal. In all groups, images of 140-270 individual cells were 
                  quantified. </li>
              <li class="justify-text"><strong>More data/results can't be shared at the moment</strong>. The other protein candidates identified 
                  through these experiments will be published in the next few years, as they are part of ongoing projects. Most of my PLA 
                  experiments were done in 2022 and I was able to publish them all before I graduated in Sept 2023. </li>
            </ol>
      </div>
      <div class="right-column-50">
          <img src="https://github.com/EdRey05/EdRey05.github.io/assets/62916582/25da16e5-a2da-4682-a921-7ad4680f17e9" alt="CRK Box plot" />
      </div>
  </div>
  <br>
  <p><strong> Check the Github page showcasing some of the scripts mentioned here: <a href="https://edrey05.github.io/Resources_for_Mulligan_Lab/">PLA ImageJ scripts</a></strong></p>
  <p><strong> Check the Streamlit data app I made here: <a href="https://github.com/EdRey05/Streamlit_projects/tree/main/002_Automated_PPTX_PLA">Demo_PLA_PPTX</a></strong></p>
</details>
<br>
<hr>

<h2> More about my work </h2>

<details><summary markdown="span"> Expand this to read more...</summary>
  <br>
  <div class="two-columns">
    <div class="left-column-35">
      <p><strong> Check my other Github pages </strong></p>
      <ul>
        <li> <strong><a href="https://edrey05.github.io/Resources_for_Mulligan_Lab/">Tools generated during my PhD</a></strong> </li>
        <li> <strong><a href="https://edrey05.github.io/Streamlit_projects/">Streamlit projects</a></strong> </li>
      </ul>
    </div>
    <div class="right-column-65">
      <p><strong> My Github Stats: </strong></p>
      <p><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EdRey05&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact" alt="Top Languages">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=EdRey05&theme=dark&hide_border=false" alt="GitHub Streak Stats"></p>
    </div>
  </div>
</details>
<br>
<hr>
