---
layout: page
title: Contributions
nav-short: true
---

Every contribution is welcome whether that is:
- an open-source tool useful for hypersonic / rarefied gas dynamics calculations
- a new/revised OpenFOAM library/solver
- an update to a more recent version of OpenFOAM
- an additional documented tutorial
- a bug report/fix, using the [Issues](https://github.com/vincentcasseau/hyStrath/issues) page
- an addition to be made to the _How-tos_ 
- etc

Please [get in touch](https://hystrath.github.io/contact) if you are interested.

<br>

--- 

## How can I contribute?
{: #How-can-I-contribute }

You will need to fill a _pull request_ and this can be achieved as follows:  

1. Fork your own copy of _hyStrath_ using the fork button    
2. Open a terminal window and create a local copy of your _hyStrath_ repository   
```sh
cd $WM_PROJECT_USER_DIR  
git clone https://github.com/USERNAME/hyStrath
```   
3. Add/edit files in your local repository  
4. At any time, track the changes that you have made using  
```sh
git status
```  
5. Once you are ready to commit and push your changes, type in
```
cd $WM_PROJECT_USER_DIR/hyStrath  
git add PATH/TO/NEW/CONTENTS/  
git commit -m 'SOLVER_NAME: AN_EXPLICIT_DESCRIPTION_OF_THE_CHANGES'  
git push origin master  
```    
6. Press the [_New pull request_](https://github.com/vincentcasseau/hyStrath/compare) button in the _Pull Requests_ tab   
7. Compare the _master_ on vincentcasseau/hyStrath with your _master_ on USERNAME/hyStrath and press _Create pull request_ once you are done
8. Your contribution to _hyStrath_ will be pending for approval and will be dealt with shortly. Thank you!  

<br>

--- 
## List of external contributions

| Contributor | _hyStrath_ branch | Contribution | Date |  
|-------------|:-------------:|:-------------:|:-------------:|
| [R.Tech Engineering](http://rtech-engineering.com/), Verniolle, France | OF-v1706 | [Update to OpenFOAM v1706](https://hystrath.github.io/maintenance/), v1706 branch created | 12 May 2018 |

<br>

--- 
## List of integrations

| Author | _hyStrath_ branch | Contribution | Date |  
|-------------|:-------------:|:-------------:|:-------------:|
| [the Micro & Nano Flows Group](http://www.micronanoflows.ac.uk/) | **Master** | [Original dsmcFoam solver and lagrangian library](https://github.com/MicroNanoFlows/OpenFOAM-2.4.0-MNF/tree/devel-craig), OF-2.4.0 | March 2017 |
| Anton Kidess | **Master** | [**_blockMeshDG_**](https://openfoamwiki.net/index.php/Contrib_blockMeshDG) | March 2017 |
| Bernhard Gschaider | **Master** | [**_makeAxialMesh_**](http://openfoamwiki.net/index.php/Contrib/MakeAxialMesh) | March 2017 |

