------------------------------------------------------------
CySabioRK for Cytoscape-2.8.3
------------------------------------------------------------
We are pleased to announce the release of CySabioRK
which is available for download at

http://www.charite.de/sysbio/people/koenig/software/cysabiork/
http://sourceforge.net/projects/cysbml/

CySabioRK is a Cytoscape plugin for accessing kinetic information from
SabioRK via the Sabio RESTful interface.

Please try and report any problems you encounter using CySBML to
matthias.koenig@charite.de

Thanks and have fun 
The CySabioRK team.

------------------------------------------------------------
Copyright (c) 2014, Matthias Koenig, Computational Systems Biochemistry, 
Charite Berlin
matthias.koenig [at] charite.de

This library is free software; you can redistribute it and/or modify it
under the terms of the GNU Lesser General Public License as published
by the Free Software Foundation; either version 2.1 of the License, or
any later version.

This library is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY, WITHOUT EVEN THE IMPLIED WARRANTY OF
MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.  The software and
documentation provided hereunder is on an "as is" basis, and the
Institute for Systems Biology and the Whitehead Institute
have no obligations to provide maintenance, support,
updates, enhancements or modifications.  In no event shall the
Institute for Systems Biology and the Whitehead Institute
be liable to any party for direct, indirect, special,
incidental or consequential damages, including lost profits, arising
out of the use of this software and its documentation, even if the
Institute for Systems Biology and the Whitehead Institute
have been advised of the possibility of such damage.  See
the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with this library; if not, write to the Free Software Foundation,
Inc., 59 Temple Place, Suite 330, Boston, MA 02111-1307 USA.

------------------------------------------------------------
*** Features ***
- Accessing SabioRK data via search interface in Cytoscape

------------------------------------------------------------
*** Installation ***
[1] install Cytoscape v2.8.3 or newer from 
    http://www.cytoscape.org/download.html

[2] download current versions of CySBML and CySabioRK from 
    http://sourceforge.net/projects/cysbml/
    http://sourceforge.net/projects/cysabiork/

[3] move the downloaded files
         CySBML-vx.xx.jar' 
         CySabioRK-vx.xx.jar' 
    in the Cytoscape plugin folder under 
    'Cytoscape_v2.8.*/plugins/'.
    In Windows this folder is normally located under 
    C:/Program Files/Cytoscape_v2.8.*/plugins.
    
[4] remove 'sbml-reader-2.8.*-jar-with-dependencies.jar' from 
    the plugin folder.

CySabioRK is installed and available in Cytoscape under 
plugins after the next startup of Cytoscape.

------------------------------------------------------------
*** Uninstall ***
[1] remove the CySabioRK-vx.xx.jar from the plugin folder.

------------------------------------------------------------
*** Referenced jar files ***
Jersey RESTful apply
    https://jersey.java.net/download.html
    jersey-client-1.17.1.jar
	jersey-core-1.17.1.jar

------------------------------------------------------------
*** Change Log ***
v0.17
- logger updated 

v0.16
- update library dependecies -> jersey-1.17.1

v0.15
- first working version
------------------------------------------------------------
Matthias Koenig
Computational Systems Biochemistry
Institute of Biochemistry
Charité - Universitätsmedizin Berlin
Reinickendorfer Str. 61
Haus 10
13347 Berlin
Germany
http://www.charite.de/sysbio/people/koenig/

Tel: + 49 30 450 528 404
Fax: + 49 30 450 528 937
Email: matthias.koenig@charite.de 

------------------------------------------------------------