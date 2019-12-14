Due to limited time and less malware knowledge, the server side actually can not running with two Xmrig file at this time and also not deployed to a docker image. They only can run separately, which actually made the server side useless at this time. But it is true that scanning official tomcat and mysql image in docker is necessary for analyzing a real app with malware in docker.

The unoffical_xmrig file contains the source code for alpine-xmrig downloaded from docker. Same as official_ximrig file, it contains the the source code for xmrig-xmrig.

Scanning tool Anchore is in the scanningtool_and_result file, attached with scanning result with two xmrigs, mysql and tomcat.

Other files is for incomplete server side. Except server side and clamscan running on the local, others are running on the docker.