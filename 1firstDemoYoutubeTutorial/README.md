# firstDemoYoutubeTutorial

https://www.youtube.com/watch?v=9MyIABer_NY&ab_channel=RodrigueTchamna 

Firstly, install SUMO. 

After: 

  1º) Create files: my_edge.edg.xml, my_nodes.nod.xml, my_type.type.xml

  2º) Mix the files creating my_nodes.nod.xml. Use the cmd: netconvert --node-files my_nodes.nod.xml --edge-files my_edge.edg.xml -t my_type.type.xml -o my_net.net.xml

  3º) Create my_route.rou.xml

  4º) Create my_config_file.sumocfg (WITHOUT XML, IT'S A SUMO EXTENSION)

Lastly,in the folder, open my_config_file. It should open in SUMO. Or, open CMD: sumo-gui -c my_config_file.sumocfg

