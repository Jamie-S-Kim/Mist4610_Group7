# Mist4610_Group7 - Project 1

## Team Name:

## Team Members:

## Problem Description:

## Data Model

## Data Dictionary:

## Queries:
  1. Query 1 selects a list of each player, and includes the teams and the tournaments they partcipated in, ordered by the tournament ID, team ID, and match ID.
<img width="2206" height="1216" alt="image" src="https://github.com/user-attachments/assets/c01f72b8-9968-4a0a-af27-86f2ca8e527f" />

Query 1 helps tournament managers track player participation across different teams as well as events, which is essential for tournament roster management. By seeing which players are associated with specific teams in each tournament, managers are able to ensure there are no violations in a database, such as a player marked in multiple teams in the same tournament. Additionally, this information helps marketing decisions, such as promoting a specific well-known player in a certain tournament.

  2. Query 2 lists each match's respective winning team, displaying the winning team's score, what tournament the match happened in, and their match ID, ordered by the match ID.
<img width="2060" height="1228" alt="image" src="https://github.com/user-attachments/assets/79b715d8-6daa-4374-ae6a-0bb036f8de9f" />

Query 2 provides managers with a clear view of match outcomes by identifying the winning team, as well as their respective performance in their winning match. This is crucial to validate match results, and to make sure the tournament brackets are advancing correctly. Managers can also use this information to analyze trends, such as dominating teams, or matches with higher scores. This insight allows managers to view and evaluate tournament quality and competitiveness, which is valuable to the operative side of E-Sports, and the audience’s side. 
<img width="2186" height="952" alt="image" src="https://github.com/user-attachments/assets/07c114d1-47b1-4d37-b2cb-6df9e0f08733" />

  3. Query 3 creates a list of sponsors, which tournament they sponsored, their contributions, and their respective ROI metric. This is filtered to select sponsors that donated over at least $50,000, and their ROI being over at least 100, ordered by the sponsor's name, and tournament ID.

Query 3 allows managers to see which sponsors are making significant financial contributions and whether those investments are yielding strong returns. By filtering for high contributions and strong ROI, managers can identify their most valuable sponsor relationships to prioritize and maintain a relationship with them. This information is critical for the future, whenever sponsorship deals need to be negotiated. This metric also allows managers to ensure that tournaments can maintain financial stability by putting a focus on partners that provide a higher impact.

  4. Query 4 summarizes sponsorship performance for each tournament and categorizes tournaments into funding levels based on total sponsorship contributions.

Query 4 helps managers understand how sponsorship is distributed across tournaments by showing the number of sponsors, total funding received, and the average ROI. By grouping tournaments into funding levels, managers can quickly identify which events are attracting strong financial support and which may need more sponsor outreach. This insight is useful for planning future tournaments, improving sponsorship strategies, and allocating resources more effectively.

  5. Query 5 identifies teams that earned above-average prize money within their respective tournaments.

Query 5 allows managers to evaluate team performance from a financial perspective by highlighting teams that outperform the average prize earnings in each tournament. This helps identify top-performing teams and understand how prize money is distributed among competitors. These insights can support decisions related to team recognition, sponsorship targeting, and evaluating overall tournament competitiveness.

  6. Query 6 shows how each team performed in each tournament by comparing their expected ranking (seed number) to their actual result (final rank).

Query 6 helps managers assess team performance relative to expectations by displaying both the seed number and final rank for each team. This allows managers to identify teams that overperformed or underperformed, which can be useful for evaluating competitive balance and improving future tournament seeding decisions. It also provides insight into overall tournament outcomes and team consistency.
  
  7. Query 7 provides an overview of tournaments by displaying their dates, duration, status, and location, while filtering for tournaments with valid locations and relevant statuses.

Query 7 helps managers review important operational details about tournaments, including how long each event lasts and where it is being held. By filtering for tournaments with meaningful statuses and valid locations, managers can focus on events that are most relevant for scheduling, planning, and monitoring tournament activity.

## Database Information:
