# Mist4610_Group7 - Project 1

## Team Name:
61608 - Group 7
## Team Members:
1. Jamie Kim - [@Jamie-S-Kim](https://github.com/Jamie-S-Kim)
2. Sienna Wong - [@s1ennawong](https://github.com/s1ennawong)
3. Shaehaan Khaja - [@shaehaankhaja](https://github.com/shaehaankhaja)
4. Seth White - [@sethwhite444](https://github.com/sethwhite444)
5. Owen Verlander - [@owenver](https://github.com/owenver)
## Problem Description:

## Data Model
<img width="1530" height="1476" alt="IMG_8415" src="https://github.com/user-attachments/assets/7ea0c59b-a278-43b8-ad70-9d04b714e7ab" />

## Data Dictionary:
<img width="773" height="444" alt="Screenshot 2026-04-03 at 6 01 49 PM" src="https://github.com/user-attachments/assets/ce25fbe1-197f-4b3d-b773-f04399164ccf" />
<img width="740" height="346" alt="Screenshot 2026-04-03 at 6 03 22 PM" src="https://github.com/user-attachments/assets/4f736bb5-8020-48a5-883b-3734af554131" />
<img width="726" height="233" alt="Screenshot 2026-04-03 at 6 03 43 PM" src="https://github.com/user-attachments/assets/baccd967-3e71-4397-9131-e1cfe32d1002" />
<img width="740" height="383" alt="Screenshot 2026-04-03 at 6 03 56 PM" src="https://github.com/user-attachments/assets/0f93b537-96b8-4503-ba0d-8ab77c8f320a" />
<img width="720" height="535" alt="Screenshot 2026-04-03 at 6 04 19 PM" src="https://github.com/user-attachments/assets/3e4896ea-a14d-457c-9d53-c230ebec5ae3" />
<img width="756" height="389" alt="Screenshot 2026-04-03 at 6 04 30 PM" src="https://github.com/user-attachments/assets/11e6a363-3174-475f-b896-24998597c3ba" />
<img width="721" height="517" alt="Screenshot 2026-04-03 at 6 04 42 PM" src="https://github.com/user-attachments/assets/4c145d39-695b-4fdc-a3c7-585c33c2ffa8" />
<img width="724" height="539" alt="Screenshot 2026-04-03 at 6 04 57 PM" src="https://github.com/user-attachments/assets/5ef4e50c-bc9b-409a-aa72-8e5ff3124766" />
<img width="701" height="372" alt="Screenshot 2026-04-03 at 6 05 24 PM" src="https://github.com/user-attachments/assets/333a50e7-246c-41b6-85c5-f974ac2a3788" />
<img width="753" height="468" alt="Screenshot 2026-04-03 at 6 05 40 PM" src="https://github.com/user-attachments/assets/797c8e5d-c796-43d8-9175-4dfe24a0e1f2" />
<img width="776" height="293" alt="Screenshot 2026-04-03 at 6 06 00 PM" src="https://github.com/user-attachments/assets/8486ab89-32de-4d90-8f6f-d1ea870a99a8" />
<img width="777" height="431" alt="Screenshot 2026-04-03 at 6 06 22 PM" src="https://github.com/user-attachments/assets/e16a8d8d-a616-4e99-b73a-7ebc1c36533c" />
<img width="788" height="446" alt="Screenshot 2026-04-03 at 6 06 42 PM" src="https://github.com/user-attachments/assets/992ea1ae-dc5c-4ad0-9341-cd0303821979" />

## Queries:
  1. Query 1 selects a list of each player, and includes the teams and the tournaments they partcipated in, ordered by the tournament ID, team ID, and match ID.
<img width="2206" height="1216" alt="image" src="https://github.com/user-attachments/assets/c01f72b8-9968-4a0a-af27-86f2ca8e527f" />

Query 1 helps tournament managers track player participation across different teams as well as events, which is essential for tournament roster management. By seeing which players are associated with specific teams in each tournament, managers are able to ensure there are no violations in a database, such as a player marked in multiple teams in the same tournament. Additionally, this information helps marketing decisions, such as promoting a specific well-known player in a certain tournament.

  2. Query 2 lists each match's respective winning team, displaying the winning team's score, what tournament the match happened in, and their match ID, ordered by the match ID.
<img width="2060" height="1228" alt="image" src="https://github.com/user-attachments/assets/79b715d8-6daa-4374-ae6a-0bb036f8de9f" />

Query 2 provides managers with a clear view of match outcomes by identifying the winning team, as well as their respective performance in their winning match. This is crucial to validate match results, and to make sure the tournament brackets are advancing correctly. Managers can also use this information to analyze trends, such as dominating teams, or matches with higher scores. This insight allows managers to view and evaluate tournament quality and competitiveness, which is valuable to the operative side of E-Sports, and the audience’s side. 

  3. Query 3 creates a list of sponsors, which tournament they sponsored, their contributions, and their respective ROI metric. This is filtered to select sponsors that donated over at least $50,000, and their ROI being over at least 100, ordered by the sponsor's name, and tournament ID.
<img width="2186" height="952" alt="image" src="https://github.com/user-attachments/assets/07c114d1-47b1-4d37-b2cb-6df9e0f08733" />
Query 3 allows managers to see which sponsors are making significant financial contributions and whether those investments are yielding strong returns. By filtering for high contributions and strong ROI, managers can identify their most valuable sponsor relationships to prioritize and maintain a relationship with them. This information is critical for the future, whenever sponsorship deals need to be negotiated. This metric also allows managers to ensure that tournaments can maintain financial stability by putting a focus on partners that provide a higher impact.


  4. Query 4 summarizes sponsorship performance for each tournament and categorizes tournaments into funding levels based on total sponsorship contributions.
<img width="1020" height="607" alt="query4_results" src="https://github.com/user-attachments/assets/42f61c41-16df-4e7b-b3c2-4de8a161714b" />

Query 4 helps managers understand how sponsorship is distributed across tournaments by showing the number of sponsors, total funding received, and the average ROI. By grouping tournaments into funding levels, managers can quickly identify which events are attracting strong financial support and which may need more sponsor outreach. This insight is useful for planning future tournaments, improving sponsorship strategies, and allocating resources more effectively.

  5. Query 5 identifies teams that earned above-average prize money within their respective tournaments.
<img width="1015" height="604" alt="query5_results" src="https://github.com/user-attachments/assets/66677788-8d41-4bc4-8c90-34ebd1b37936" />

Query 5 allows managers to evaluate team performance from a financial perspective by highlighting teams that outperform the average prize earnings in each tournament. This helps identify top-performing teams and understand how prize money is distributed among competitors. These insights can support decisions related to team recognition, sponsorship targeting, and evaluating overall tournament competitiveness.

  6. Query 6 shows how each team performed in each tournament by comparing their expected ranking (seed number) to their actual result (final rank).
<img width="1018" height="594" alt="query6_results" src="https://github.com/user-attachments/assets/3611b592-f712-49f8-a4e1-1118c285f30f" />

Query 6 helps managers assess team performance relative to expectations by displaying both the seed number and final rank for each team. This allows managers to identify teams that overperformed or underperformed, which can be useful for evaluating competitive balance and improving future tournament seeding decisions. It also provides insight into overall tournament outcomes and team consistency.
  
  7. Query 7 provides an overview of tournaments by displaying their dates, duration, status, and location, while filtering for tournaments with valid locations and relevant statuses.
<img width="992" height="607" alt="query7_results" src="https://github.com/user-attachments/assets/bd5ee3fc-3078-4e29-9fbb-7ee7ae750837" />

Query 7 helps managers review important operational details about tournaments, including how long each event lasts and where it is being held. By filtering for tournaments with meaningful statuses and valid locations, managers can focus on events that are most relevant for scheduling, planning, and monitoring tournament activity.

## Database Information:
- Name of the database: ns_Sp26_61608_Group7
