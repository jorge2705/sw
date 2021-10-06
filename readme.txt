Install Ocaml in linux and compile the modules to generated the binary adapted to your system following the next procedure :

~/chatbot_master/brev$make
~/chatbot_master/planer$make
~/chatbot_master/translator$dune build


In case the Ocaml compiler sends a message related to the .cmi files, is because sometimes it can not delete these files in automatic, so in that case, it is necessary to remove these files manually.
You can manually delete these *.cmi files which are placed in \brev\Sources and \planer\Sources. 
Then when you execute the "make" command these will be generated again. 

