This container performs substructure matching using `grep`, after an idea from: 

* http://www.daylight.com/meetings/emug00/Sayle/substruct.html

Basically `grep` can be used to search SMILE structures, finding matches.

A discussion of how it is working can be found at:

* http://matthewkwilliams.com/index.php/2015/04/18/naive-substructure-substance-matching-on-the-raspberry-pi/


The Docker container is built like this:

    docker build -t nimblestratus/rpi-substructure-grepper .

