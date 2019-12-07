
The folder “adjacency matrices” contains the household adjacency matrices for each village. 

“householdcharacteristics.csv” gives relevant information on the various surveyed households:
- village: the village ID
- HHnum_in_village: the household ID (within each village, these correspond to nodes in networks)
- hohreligion: household religion
- castesubcaste: household caste (only defined for some villages)
- rooftype1: rooftype indictator 	
- rooftype2: rooftype indictator	
- rooftype3: rooftype indictator	
- rooftype4: rooftype indictator	
- rooftype5: rooftype indictator	
- room_no: number of rooms	
- bed_no: number of beds	
- electricity: electricity + provider 	
- latrine: toilet? 	
- ownrent: type of house ownership
- leader: is household a leader?
- adopt: did household adopt?

“cm.net” is a MATLAB code (attached for your convenience) to create a degree-preserving configuration of a given graph.