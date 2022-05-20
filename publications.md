---
layout: page
title: Publications
nav-short: true
---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>PUBLICATIONS</header>
  <a href="https://hystrath.github.io/publications/#guidelines">Guidelines</a>
  <a href="https://hystrath.github.io/publications/#journal-articles">Journal articles</a>
  <a href="https://hystrath.github.io/publications/#conference-papers">Conference papers</a>
  <a href="https://hystrath.github.io/publications/#extended-abstracts">Extended abstracts</a>
  <a href="https://hystrath.github.io/publications/#theses">Theses</a>
  <a href="https://hystrath.github.io/publications/#technical-reports">Technical reports</a>
  <a href="https://hystrath.github.io/publications/#presentation-slides">Presentation slides</a>
</div>

<span style="position: fixed;font-size:30px;cursor:pointer; margin:0px; top:60px;left:30px;" onclick="reopenNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "210px";
  document.getElementById("mySidenav").style.transition = "0s";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
  localStorage.removeItem('show_sidenav');
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "210px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  localStorage.setItem("show_sidenav", true);
}

if (localStorage.getItem("show_sidenav")) openNav()
</script>

{: #guidelines }

Please cite the publication(s) related to the solver(s) that are used and make a reference to the release name and commit tag as follows:  
```
@MISC{Github_hyStrath,  
title = {Github repository of the hyStrath platform},  
month = {MM},  
year = {YYYY},  
note = {Release `Fleming', commit <commit tag>},
howpublished = {\url{https://github.com/vincentcasseau/hyStrath/}}  
} 
```

<br>

<h3>JOURNAL ARTICLES</h3>
{: #journal-articles }
  <p><b><i>dsmcFoam+ MNF</i></b> &nbsp; | &nbsp; C. White, M. K. Borg, T. J. Scanlon, S. M. Longshaw, B. John, D. R. Emerson, and J. M. Reese, "dsmcFoam+: An OpenFOAM based direct simulation Monte Carlo solver," <i>Computer Physics Communications</i>, vol. 224, no. 1, pp. 22-43, <b>2018</b> &nbsp; <a href="https://pure.strath.ac.uk/portal/files/81235392/White_etal_CPC_2017_an_OpenFOAM_based_direct_simulation_Monte_Carlo_solver.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>
  <p><b><i>pdFoam</i></b> &nbsp; | &nbsp; C. J. Capon, M. Brown, C. White, T. J. Scanlon, and R. R. Boyce, "pdFOAM: A PIC-DSMC code for near-Earth plasma-body interactions," <i>Computers and Fluids</i>, vol. 149, no. 1, pp. 160-171, <b>2017</b> &nbsp; <a href="http://eprints.gla.ac.uk/138700/7/138700.pdf" target="_blank" style="color:orange"> [PDF Preprint→]</a></p>
  <p><b><i>hy2Foam</i></b> &nbsp; | &nbsp; V. Casseau, D. E.R. Espinoza, T. J. Scanlon, and R. E. Brown, "A Two-Temperature Open-Source CFD Model for Hypersonic Reacting Flows, Part Two: Multi-Dimensional Analysis," <i>Aerospace</i>, vol. 3, no. 4, p. 45, <b>2016</b> &nbsp; <a href="http://www.mdpi.com/2226-4310/3/4/45/html" target="_blank" style="color:orange"> [Full HTML→]</a></p>
  <p><b><i>hy2Foam</i></b> &nbsp; | &nbsp; V. Casseau, R. C. Palharini, T. J. Scanlon, and R. E. Brown, "A Two-Temperature Open-Source CFD Model for Hypersonic Reacting Flows, Part One: Zero-Dimensional Analysis," <i>Aerospace</i>, vol. 3, no. 4, p. 34, <b>2016</b> &nbsp; <a href="ttp://www.mdpi.com/2226-4310/3/4/34/html" target="_blank" style="color:orange"> [Full HTML→]</a></p>  
  <p><b><i>dsmcFoam+ MNF</i></b> &nbsp; | &nbsp; T. J. Scanlon, C. White, M. K. Borg, R. C. Palharini, E. Farbar, I. D. Boyd, J. M. Reese, and R. E. Brown, "Open-Source Direct Simulation Monte Carlo Chemistry Modeling for Hypersonic Flows," <i>AIAA Journal</i>, vol. 53, no. 6, pp. 1670-1681, <b>2015</b> &nbsp; <a href="https://deepblue.lib.umich.edu/bitstream/handle/2027.42/140685/1.J053370.pdf?sequence=1" target="_blank" style="color:orange"> [PDF→]</a></p>
  <p><b><i>dsmcFoam+ MNF</i></b> &nbsp; | &nbsp; R. C. Palharini, C. White, T. J. Scanlon, R. E. Brown, M. K. Borg, and J. M. Reese "Benchmark numerical simulations of rarefied non-reacting gas flows using an open-source DSMC code," <i>Computers and Fluids</i>, vol. 120, no. 1, pp. 140-157, <b>2015</b> &nbsp; <a href="https://www.pure.ed.ac.uk/ws/portalfiles/portal/21924394/PalhariniEtAlCompFluids2015.pdf" target="_blank" style="color:orange"> [PDF Preprint→]</a></p>
  <p><b><i>dsmcFoam+ MNF</i></b> &nbsp; | &nbsp; T. J. Scanlon, E. Roohi, C. White, M. Darbandi, and J. M. Reese, "An open source, parallel DSMC code for rarefied gas flows in arbitrary geometries," <i>Computer & Fluids</i>, vol. 39, no. 10, pp. 2078-2089, <b>2010</b> &nbsp; <a href="https://www.research.ed.ac.uk/portal/files/17079048/ScanlonEtAlCandF2010.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>

<h3>CONFERENCE PAPERS</h3>
{: #conference-papers }
  <p><b><i>dsmcFoam+</i></b> &nbsp; | &nbsp; V. Casseau and C. White, "Effective diffusivity in porous media under rarefied gas conditions," <i>31st International Symposium on Rarefied Gas Dynamics</i> (Glasgow, UK, 23-27 July 2018), vol. 2132, no. 1, 150001, <b>2019</b> &nbsp; <a href="https://github.com/vincentcasseau/hyStrath/blob/master/doc/ConferencePreprint_RGD31_CasseauWhite.pdf" target="_blank" style="color:orange"> [PDF Preprint→]</a></p>
  <p><b><i>ARC</i></b> &nbsp; | &nbsp; V. Renato and T. J. Scanlon, "Multi-dimensional Ablation and Thermal Response Program for Martian Entry Analysis," <i>68th International Astronautical Congress</i> (Adelaide, Australia, 25-29 September 2017), <b>2017</b> &nbsp; <a href="https://strathprints.strath.ac.uk/62926/1/Renato_Scanlon_IAC_2017_Multi_dimensional_ablation_and_thermal_response_program_for_Martian_entry_analysis.pdf" target="_blank" style="color:orange"> [PDF Preprint→]</a></p>
  <p><b><i>ARC</i></b> &nbsp; | &nbsp; V. Renato, T. J. Scanlon, and R. E. Brown, "Multi-dimensional Ablation and Thermal Response Program for
Re-entry Analysis," <i>31st International Symposium on Space Technology and Science</i> (Matsuyama City, Japan, 3-9 June 2017), <b>2017</b> &nbsp; <a href="https://pure.strath.ac.uk/portal/files/72079768/Renato_etal_ISTS_2017_Multi_dimensional_ablation_and_thermal_response_program_for_re_entry_analysis.pdf" target="_blank" style="color:orange"> [PDF Preprint→]</a></p>
  <p><b><i>hyFoam</i></b> &nbsp; | &nbsp; J.-J. O.E. Hoste, V. Casseau, M. Fossati, I. J. Taylor, and R. Gollan, "Numerical Modeling and Simulation of Supersonic Reacting Flows in Propulsion Systems by Open-Source Solvers," <i>21st AIAA International Space Planes and Hypersonic Systems and Technologies Conference</i> (Xiamen, China, 6-9 March 2017), AIAA Paper 2017-2411, <b>2017</b> &nbsp; <a href="http://eprints.gla.ac.uk/140369/1/140369.pdf" target="_blank" style="color:orange"> [PDF Preprint→]</a></p>
  <p><b><i>hyperFoam</i></b> &nbsp; | &nbsp; D. E.R. Espinoza, V. Casseau, T. J. Scanlon, and R. E. Brown, "An open-source hybrid CFD-DSMC solver for high speed flows," <i>30th International Symposium on Rarefied Gas Dynamics</i> (Victoria, BC, Canada, 10-15 July 2016), vol. 1786, no. 1, 050007, <b>2016</b> &nbsp; <a href="http://strathprints.strath.ac.uk/59955/14/Espinoza_etal_SRGD2016_An_open_source_hybrid_CFD_DSMC_solver_for_high_speed_flows.pdf" target="_blank" style="color:orange"> [PDF Preprint→]</a></p>  
  <p><b><i>rhoCentralFoam</i></b> &nbsp; | &nbsp; D. E.R. Espinoza, T. J. Scanlon, and R. E. Brown, "Validation of tools to accelerate high-speed CFD simulations using OpenFOAM," <i>20th AIAA International Space Planes and Hypersonic Systems and Technologies Conference</i> (Glasgow, UK, 6-9 July 2015), AIAA Paper 2015-3566, <b>2015</b> &nbsp; <a href="https://strathprints.strath.ac.uk/55051/1/Espinoza_etal_MHYP15_Validation_tools_to_accelerate_high_speed_CFD_simulations_using_OpenFOAM.pdf" target="_blank" style="color:orange"> [PDF Preprint→]</a></p> 
 
<h3>EXTENDED ABSTRACTS</h3>
{: #extended-abstracts }
  <p><b><i>hy2Foam</i></b>, <b><i>dsmcFoam+</i></b>, <b><i>hyperFoam</i></b> &nbsp; | &nbsp; V. Casseau, D. E.R. Espinoza, and T. J. Scanlon, "Open-Source High-fidelity Solvers Dedicated to Re-entry Analysis and Design for Demise," <i>Final Stardust Conference</i>, European Space Agency - ESTEC (Noordwijk, Netherlands, 31 October - 3 November 2016), <b>2016</b> &nbsp; <a href="https://github.com/vincentcasseau/hyStrath/blob/master/doc/ExtendedAbstract_Stardust2016_CasseauEspinoza.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>
  <p><b><i>dsmcFoam MNF</i></b> &nbsp;  T. J. Scanlon, R. C. Palharini, C. White, D. E.R. Espinoza, and V. Casseau, "Simulations of rarefied and continuum hypersonic flow over re-entry objects," <i>8th European Symposium on Aerothermodynamics for Space Vehicles</i> (Lisbon, Portugal, 2-6 March 2015), <b>2015</b> &nbsp; <a href="https://strathprints.strath.ac.uk/51961/" target="_blank" style="color:orange"> [PDF→]</a></p> 
  
<h3>THESES</h3>
{: #theses }
  <p><b><i>hyperFoam</i></b> &nbsp; | &nbsp; D. E.R. Espinoza, "An Open-Source Hybrid CFD-DSMC Solver for High-Speed Flows," PhD thesis, University of Strathclyde, Glasgow (UK), <b>2018</b> &nbsp; <a href="https://github.com/vincentcasseau/hyStrath/blob/master/doc/PhDthesis-danielespinoza.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>
  <p><b><i>ARC</i></b> &nbsp; | &nbsp; V. Renato, "Multi-dimensional Thermal Response & Permeability Characterization for Porous Ablative Materials," PhD thesis, University of Strathclyde, Glasgow (UK), <b>2018</b> &nbsp; <a href="https://github.com/vincentcasseau/hyStrath/blob/master/doc/PhDthesis-violarenato.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>
  <p><b><i>Eilmer3</i></b>, <b><i>Eilmer4</i></b> &nbsp; | &nbsp; J.-J. O.E. Hoste, "Scramjet Combustion Modeling using Eddy Dissipation Model," PhD thesis, University of Strathclyde, Glasgow (UK), <b>2018</b> &nbsp; <a href="https://github.com/vincentcasseau/hyStrath/blob/master/doc/PhDthesis-jimmyjohnhoste.pdf" target="_blank" style="color:orange"> [PDF→]</a> &nbsp; NB: <a href="http://cfcfd.mechmining.uq.edu.au/docs/tools/eilmer/"> Eilmer 3 </a> is a research and educational simulation code for 2D and 3D gas dynamics designed by Dr Peter Jacobs, Dr Rowan Gollan, Dr Daniel Potter and others (University of Queensland, Australia). See also the <a href="https://hystrath.github.io/tutos-hyfoam/#3-lorrains-scramjet"> tutorial case available on hyStrath</a> that uses <i>hyFoam</i></p>  
  <p><b><i>rhoCentralFoam</i></b>, <b><i>Eilmer3</i></b>, <b><i>hyFoam</i></b> &nbsp; | &nbsp; D. Puorto, "Suitability of rhoCentralFoam for Scramjet Internal Flows," Master's thesis, University of Naples Federico II, Naples (Italy), <b>2017</b></p>
  <p><b><i>pdFoam</i></b> &nbsp; | &nbsp;  C. J. Capon, "Ionospheric Aerodynamics in Low Earth Orbit," PhD thesis, University of New South Wales, Canberra (Australia), <b>2017</b> &nbsp; <a href="http://unsworks.unsw.edu.au/fapi/datastream/unsworks:46528/SOURCE01?view=true" target="_blank" style="color:orange"> [PDF→]</a></p> 
  <p><b><i>hyFoam</i></b>, <b><i>hy2Foam</i></b> &nbsp; | &nbsp;  V. Casseau, "An Open-Source CFD Solver for Planetary Entry," PhD thesis, University of Strathclyde, Glasgow (UK), <b>2017</b> &nbsp; <a href="https://github.com/vincentcasseau/hyStrath/blob/master/doc/PhDthesis-vincentcasseau.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>  
  <p><b><i>dsmcFoam MNF</i></b> &nbsp; | &nbsp;  R. C. Palharini, "Atmospheric Reentry Modelling Using an Open-Source DSMC Code," PhD thesis, University of Strathclyde, Glasgow (UK), <b>2014</b> &nbsp; <a href="https://github.com/vincentcasseau/hyStrath/blob/master/doc/PhDthesis-rodrigopalharini.pdf" target="_blank" style="color:orange"> [PDF→]</a></p> 

<h3>TECHNICAL REPORTS</h3>
{: #technical-reports }
  <p><b><i>hyFoam</i></b> &nbsp; | &nbsp; J.-J. O.E. Hoste and V. Casseau, "Verification and Validation of <i>hyFoam</i> for Supersonic External Flows," TechReport-HS1, <b>05/2021</b> &nbsp; <a href="https://github.com/vincentcasseau/hyStrath/blob/master/doc/TechReport-HS1-hostecasseau.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>  

<h3>PRESENTATION SLIDES</h3> 
{: #presentation-slides }
  <p><b><i>hy2Foam</i></b>, <b><i>dsmcFoam+</i></b>, <b><i>hyperFoam</i></b> &nbsp; | &nbsp; V. Casseau, D. E.R. Espinoza, and T. J. Scanlon, "Open-Source High-fidelity Solvers Dedicated to Re-entry Analysis and Design for Demise," <i>Final Stardust Conference</i>, European Space Agency - ESTEC (Noordwijk, Netherlands, 31 October - 3 November 2016), <b>2016</b> &nbsp; <a href="https://github.com/vincentcasseau/hyStrath/blob/master/doc/Slides_FinalStardustConference2016_CasseauEspinoza.pdf" target="_blank" style="color:orange"> [PDF→]</a></p>  
