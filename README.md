These are the character rasters (including filler) and networks (with no filler) I used in the video. Please note I couldn't upload One Piece because it was too large.

1. The networks were generated from the rasters with the following method:

If characters i and j appear in Ni and Nj episodes, and jointly in N_ij episodes, then the friendship score is

F_ij = N_ij/ max(Ni, Nj)

2. Filler episodes are documented in the pkl file

3. gexf files can be opened using the networkX module in python
