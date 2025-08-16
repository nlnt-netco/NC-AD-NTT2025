## Netcompany Topspin Tournament – Operational Plan

### Overview
- **Format**: Olympic mixed team–style.
- **Teams**: 4 teams, 5 players each (Levels: 1 Newbie, 2 Intermediate, 3 Advanced).
- **Structure**: Single-elimination; 2 rounds (Semifinals → Final), all in one day.

### Seeding and Team Formation
- **Leveling**: Each player pre-assigned Level 1/2/3.
- **Seeding**: Identify top “seed” players (typically top Level 3). Randomly and evenly assign to teams.
- **Rosters**: 5 players per team; captains appointed by organizer or team consensus.

### Handicap Rule (Singles Only)
- **Rule**: In singles, if players are from different levels, the lower-level player starts each game with +3 points per level difference.
  - Level difference 1 → +3 points; difference 2 → +6 points.
- **Applies to**: Singles matches only (no handicap in doubles).

- **Examples**
  - Level 3 vs Level 1: Newbie (L1) starts each game 4–0.
  - Level 2 vs Level 1: Newbie (L1) starts each game 2–0.
  - Level 3 vs Level 3: 0–0 (no handicap).

### Match Menu per Round (7 matches)
- 3 Singles:
  - 1 singles is Newbies-only (Level 1 vs Level 1).
  - 2 singles are open (any level).
- 4 Doubles:
  - 1 doubles is Newbies-only (both players in each pair must be Level 1. If a team has only 1 Level 1, the Level 2 player will be used).
  - 1 doubles requires at least 1 Level 1 in each pair.
  - 2 doubles are open (any level).
- **Participation constraints**
  - Every member must play at least 1 match.
  - Max 3 matches per member (across the 7).
  - Any given doubles pair may be used only once in the round (no repeated pairings).

### Round 1 (Semifinals)
- **Scoring per match**: Best-of-5 games; each game to 11 points (two-point margin).
- **Winner of round**: Team with more match wins (first to 4 wins typically clinches).
- **Order**: Predefined before the round; matches run simultaneously when possible to save time.
- **Lineup**: Captains submit full 7-match lineup to the desk before the round starts.

- **Example lineup (Team Alpha)**
  - S1 (Newbies-only singles): A5 (L1) vs opponent L1
  - S2 (Open singles): A1 (L3) vs opponent
  - S3 (Open singles): A3 (L2) vs opponent
  - D1 (Newbies-only doubles): A5 (L1) + A4 (L2) [note: team only have 1 L1]
  - D2 (At least 1 newbie): A4 (L2) + A2 (L3)
  - D3 (Open doubles): A1 (L3) + A2 (L3)
  - D4 (Open doubles): A2 (L3) + A3 (L2)
  - Check constraints: each player appears ≥1 and ≤3 times; no pair repeats; slots satisfy “newbies-only” and “at least 1 newbie”.

### Final Round (Cumulative Points Format)
- **Order**: Drawn at the start of the final; matches played sequentially on one table.
- **Cumulative points**: Teams carry an accumulating score across the 7 matches.
- **Per-match targets**:
  - Match i uses Starting Points Si and Winning Points Wi:
    - (S1,W1)=(0,11), (S2,W2)=(5,22), …, (S7,W7)=(30,77).
- **How it works**
  - At the start of match i, each team’s displayed total is max(their current total, Si).
  - Points scored in the match add to that team’s total.
  - The match ends when a team reaches Wi. Proceed to the next match with totals preserved.
  - The team with the higher total after match 7 (or earlier if someone reaches W7) wins the tournament.

- **Example (first two matches)**
  - Start of Match 1 (S1=0, W1=11): Both teams start at 0. Team A wins 11–7 → Totals: A=11, B=7.
  - Start of Match 2 (S2=5, W2=22): A starts at 11 (already ≥5), B at 7 (≥5). Suppose B wins this match 15–11 in points before A hits 22; B reaches 22 first to end match → New Totals: A=11+11=22, B=7+15=22. Next match starts with both at max(current total, S3=10) → both 22.
  - Continue until a team reaches W7=77 during Match 7, or finish Match 7 and compare totals.

- **Match menu and participation constraints**: Same 7-match slots and constraints as Round 1.

### Tiebreakers and Edge Cases
- **Round 1 tie (e.g., unfinished matches due to time)**: If wins are equal when play is stopped, count games won across completed matches; if still tied, count points; if still tied, 1 sudden-death game to 11 between captains’ designees (no handicap).
- **Final round**: No tiebreaker, first team to reach 77 points wins.

### Event Timeline
- 09:00–09:30 Opening, warm-up, briefing (rules, safety, format), captain lineup submission for Semifinals
- 10:00–12:30 Round 1 (Semifinals; simultaneous where possible)
- 12:30–13:00 Lunch
- 13:00–14:30 Final (sequential on one table)
- 14:30–15:00 Awards and closing

### Courts, Equipment, and Staffing
- **Tables**: Minimum 2 for Semifinals; 1 featured table for Final; spare tables open for friendlies.
- **Balls**: 40+ plastic, 3-star; provide 6–10 per table.
- **Nets**: Check height/tension pre-session.
- **Scorekeeping**: Tabletop flip-scores or digital scoring for the Final; paper score sheets per match.
- **Officials**: 1 referee (overall rules), 2–4 umpires (rotate per table), runner for results.
- **First aid**: Basic kit on-site.

### Player Brief (simple)
- **Games**: To 11, win by 2, alternate serve every 2 points; switch ends each game.
- **Singles**: Handicaps apply per game if levels differ.
- **Doubles**: No handicap; standard doubles serve order and diagonal serves.
- **Participation**: You’ll play at least 1 and at most 3 matches this round.

### Captain Workflow
- Before each round:
  - Receive the 7-slot match menu.
  - Build lineup meeting slot rules and participation limits.
  - Submit full lineup before round start.
- During round:
  - Ensure players report to tables on time.
  - Verify no pair repeats; track player match counts (≤3).
  - Approve scores and sign sheets promptly.

### Example Lineup Card (blank template)
- Singles 1 (Newbies-only): __________ vs __________
- Singles 2 (Open): __________ vs __________
- Singles 3 (Open): __________ vs __________
- Doubles 1 (Newbies-only): __________ + __________ vs __________ + __________
- Doubles 2 (≥1 Newbie): __________ + __________ vs __________ + __________
- Doubles 3 (Open): __________ + __________ vs __________ + __________
- Doubles 4 (Open): __________ + __________ vs __________ + __________
- Checkboxes:
  - Every player appears ≥1 time [ ]
  - No one appears >3 times [ ]
  - No doubles pair repeats [ ]
  - Slots follow Newbie requirements [ ]

### Communications and Logistics
- **Pre-event**: Send rules sheet and examples; publish team rosters and seed assignments.
- **On-site signage**: Schedule board, bracket, final-round scoring ladder (11/22/33/44/55/66/77) with start-point floors.
- **Results posting**: Update bracket live after each match; announce Final’s running totals every few minutes.

### Notes (from your brief)
- BYO rackets available on request; lunch and drinks provided.
- After Semifinals, players may go to cafeteria for lunch.
- Final uses one table; free tables open for friendlies.
- Dress comfortably.
- Event date: 18 Oct 2025.

### Quick FAQ for New Players
- **What is “at least 1 newbie” doubles?** Each pair must include a Level 1 player.
- **Do handicaps apply in doubles?** No—singles only.
- **Why do points jump to 11/22/33… in the Final?** It creates a dramatic, cumulative race that stays close via starting-point floors.
