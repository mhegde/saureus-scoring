# On-target scoring for S.aureus guides
<b>This script generates on-target scores for S.aureus guides as described in Najm et al., 2018</b>

To score S.aureus guides, first download Azimuth-2.0 from <a href='https://github.com/MicrosoftResearch/Azimuth/releases/tag/v2.0'> here </a>. Make sure to include Azimuth in your path before running the python script to score sgRNAs. 

<b>Inputs</b>
1. <b>Input file</b>:.txt file with first column as 21mer sgRNA sequences and second column as the 36mer context sequence of the format NNNN[21mer]NNGRRNNNNNN
2. <b>Model file</b>: Pickled model file 
3. <b>Output file</b>: Outputfile name