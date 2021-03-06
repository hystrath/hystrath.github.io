---
layout: page
title: Synchronisation
nav-short: true
--- 

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>DOWNLOAD</header>
  <a href="https://hystrath.github.io/compatibility/">Compatibility</a>
  <a href="https://hystrath.github.io/maintenance/">Maintenance</a>
  <a href="https://hystrath.github.io/installation/">Installation</a>
  <a href="https://hystrath.github.io/sync/">Sync</a>
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

### OF-v1706   
{: #OF-v1706 }

1. Change the current working directory to your local *hyStrath* repository
    ```sh 
    cd $WM_PROJECT_USER_DIR/hyStrath
    ```
    <div style="line-height:50%;">
        <br>
    </div>
2. Grab online updates and merge them with your local work
    ```sh
    git pull origin master  
    ``` 
    <div style="line-height:50%;">
        <br>
    </div>
3. Decide which module(s) you wish to synchronise (_NUMPROCS_ is the number of processors to be used)  
    ```sh
    ./install.sh NUMPROCS 2>/dev/null
    ```
