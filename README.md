# Excel-
Average non-continuous cells
=(IF(G8<>"",G8,0)+IF(K8<>"",K8,0)+IF(O8<>"",O8,0)+IF(S8<>"",S8,0)+IF(W8<>"",W8,0)+IF(AA8<>"",AA8,0)+IF(AE8<>"",AE8,0))/(IF(G8<>"",1,0)+IF(K8<>"",1,0)+IF(O8<>"",1,0)+IF(S8<>"",1,0)+IF(W8<>"",1,0)+IF(AA8<>"",1,0)+IF(AE8<>"",1,0))

Average non-continuous cells AND hidden blanks/hidden error
=IF(RELEVANT > 0,(IF(G5<>"",G5,0)+IF(K5<>"",K5,0)+IF(O5<>"",O5,0)+IF(S5<>"",S5,0)+IF(W5<>"",W5,0)+IF(AA5<>"",AA5,0)+IF(AE5<>"",AE5,0))/(IF(G5<>"",1,0)+IF(K5<>"",1,0)+IF(O5<>"",1,0)+IF(S5<>"",1,0)+IF(W5<>"",1,0)+IF(AA5<>"",1,0)+IF(AE5<>"",1,0)),"")
