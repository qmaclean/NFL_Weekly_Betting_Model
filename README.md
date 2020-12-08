# NFL_Weekly_Betting_Model
This is a spreads betting model, use simple regression to calculate spreads each week. 

Instructions to Update:
1. Go to Pro Football Reference.com to update based on weekly results.
    https://www.pro-football-reference.com/years/2020/games.htm
2. Delete all future match-up in downloaded csv file. 
3. Change headers to match 2020_results.csv filte
4. Save as 2020_results.csv file
5. Upload to same environment as python file.
6. Run Python File
7. How to Interpret:
  The output predicts score difference, reference the current schedule to see who's playing eachother. 
  Let's say Arizona is a -4 and playing SF a -1. This would interpret as SF being favored by 3 pts. 
  
 One strategy is to identify mismatches in betting lines in order to strictly bet. Let's say the line actual has Arizona -3 (Favored) to SF. You would bet on SF +3 since the model output had SF favored over Arizona. 
 
 Track your bets in a spreadsheet over time to see performance. 
