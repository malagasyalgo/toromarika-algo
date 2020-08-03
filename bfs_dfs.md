Notes: saika natao tuto iray ihany ity, fa tena lasa lava be ilay izy dia tsy maintsy nozaraina telo
Prerequisites: Set, Queue, Stack, Recursion
BFS (Breadth First Search) sy DFS (Depth First Search) dia techniques roa tena important amin’ny algorithme sy data structure. Techniques fanaovana parcours-na data structure miendrika “Graph” izy ireo.
Graph
Voalohany indrindra aloha inona no atao hoe “Graph” ? 
Raha tsorina dia data structure manana forme-na reseau ny graph, izany hoe misy entity roa (na maromaro) mifandray. Ny entity antsoina hoe “Node” na “Vertex” ary ny finfandraisana dia antsoina hoe “Edge”


graph
Mety afaka mitazona information daholo na ny Node na ny Edge, mety hisy “direction” ihany koa ny Edge


graph with edge values & graph with edge directions

Misy karazany marobe ny graph izay tsy hidirantsika lalina, fa ireo karazany izay matetika hita anaty challenge no andeha horesahina:
Matrix: matetika dia matetika no misy matrix hanaovana parcours anaty challenge, ohatra ny challenge mifandraika amin’ny Jeux d’echec, Tetris, Number of islands, Game of life, Dungeon Game, Fanorona, Pac Man (io no hanaovantsika ny exemple BFS sy DFS rehefa avy eo), etc. 
Ohatr’ity sary manaraka ity ny endriky ny matrix sous forme-na graph:  

Matrix sous forme de graph

Trees, Binary Trees: Ny trees (na arbres) dia structure miendrika Graph ihany saingy manana hierarchie Parent-Enfant(s). Betsaka ny ampiasana trees (autocomplete, manipulation XML/HTML, IA jeux de plateaux, etc...), ary matetika mihitsy no misy adina parcours-na trees any amin’ny interview sy any amin’ny programming challenges. Ny binary trees dia trees ihany sainy ny Parent iray dia roa ihany ny zanany farafahabetsany. Ny node tsy manana parent dia antoina hoe root (racine) ary ny node tsy manana enfants dia antsoina hoe leaf (feuille). 


Binary Tree (Root/Parent/Enfants/Feuilles)


Tree

Linked List: Ny linked list dia karazana graph faran’izay tsotra ary mora ny manao parcours aminy. Ny Node iray anaty “singly linked list” dia Edge iray mankany amin’ny “next” ihany no misy aminy, raha “doubly linked list” kosa izy dia sady manana Edge mankany amin’ny “next” no mankany amin’ny “prev”. Betsaka ny ampiasana ny Linked List, ohatra iray ampiasana azy ny parcours BFS izay ho hitantsika.  


Linked lists

Ny “Graph” : Azokazonareo an-tsaina amin’izay ngamba hoe izay structure miendrika “Reseau” dia azo raisina ho graph daholo, misy karazany maro ny graph ary manana endriny maro (sasantsasany amin’izany ireto amin’ny sary ambany). Mbola be dia be no azo lazaina momban’ny Graph ary misy taranja manokana mihitsy mandalina azy : Graph Theory. Fa tsy hidirantsika lalina izany (raha te hiditra lalindalina kokoa nefa dia ato mandeha http://web.cecs.pdx.edu/~sheard/course/Cs163/Doc/Graphs.html, ary raha tena mbola te handalina misimisy kokoa dia ato https://inst.eecs.berkeley.edu/~cs61bl/r/topic/topic.html?topic=lab23.topic) :) Fa amin’ity aloha matrix dia efa ampy hianarantsika ny BFS/DFS.
