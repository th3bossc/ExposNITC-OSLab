#!/usr/bin/bash

folderName=$(dirname $0)/$1;
for FILE in $folderName/*.spl; do 
    echo $(basename $FILE);
    ./spl $FILE;
    echo -e;
done