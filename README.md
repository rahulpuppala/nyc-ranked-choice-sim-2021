---- G O A L ----
1)  SIMULATE THE MOST ACURATE BALLOT DISTRIBUTION
2)  FIND POSSIBLE PATHS TO VICTORY FOR 2ND AND 3RD SEED CANDIDATES
3)  FIGURE OUT WHICH SIMULATION VARIABLES PRODUCED THE MOST ACCURATE BALLOTS 
---- P L A N ----
1)  create candidates
2)  create data structure for each candidate
        - contains dictionary: likely hood to rank each other candidate
---- SIM BEGINS ----
LOOP 
{
3)  create ballots from initial ranked choice voting
        - add to ballot -> if likely hood of selected a candidate is above X% add candidate to ballot
4)  run instant runoff and log winner
}
---- SIM STATS ----
5) Add and change parameters to simulate real life differences in ballots (threshold for additional ranking, confidence ranges of probabilites)
---- SOURCE DATA ----
6)  Find better way to get likely hood percentages (look at heat maps of leads)
7)  Consider implementing ranked choice voting strategies
---- RETRO ANALYSIS ----
8) COMPARE WHICH SIMULATIONS HAD THE CLOSEST BALLOTS TO ACTUAL DATA - LEARN WHICH FACTORS OF THE SIMULATION WERE MOST IMPORTANT


JUNE 23/24 -   MAKE DATA STRUCTURE AND SIM LOOP AND AGREGATE STATS AND GRAPHS
JUNE 23/24 -   ADD PARAMETERS THAT MAKE SIM MORE REALISTIC 
JUNE 28 -   SET UP RETROACTIVE RESEARCH EXCEPT FOR FINAL BALLOT DATA
                - CREATE COST FUNCTION BETWEEN MY BALLOTS AND TRUE BALLOTS
JUNE 29 -   DO RETROACTIVE RESEARCH - IMPORT AND FORMAT ACTUAL BALLOT DATA AND RUN
