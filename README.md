These are the character rasters (including filler) and networks (with no filler) I used in the video. Please note I couldn't upload One Piece because it was too large.

IMPORTANT: 05/01/2025 please note I believe that the bleach raster is currently wrong, I must have uploaded an old version of it. I will find and upload the correct version when I get back home (fingers crossed I remember lol) 

1. The networks were generated from the rasters with the following method:

If characters i and j appear in Ni and Nj episodes, and jointly in N_ij episodes, then the friendship score is

F_ij = N_ij/ max(Ni, Nj)

2. Filler episodes are documented in the pkl file

3. gexf files can be opened using the networkX module in python

4. The network properties file is essentially of my results to check against. You can use the 'Connect. Thresh' column to threshold the weak links. As a reminder, this threshold is the highest threshold that still keeps the network fully connected. The 'Binary' prefix for columns just means that measure was calculated while ignoring the link strengths (post thresholding)
