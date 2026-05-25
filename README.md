🗳️ Tamil Nadu Legislative Assembly — Election Analysis 2026
A complete data analysis and visualization project covering all 234 constituencies of the 2026 Tamil Nadu Assembly Elections — built with Python and Power BI.

📊 Dashboard Overview
This project analyzes the 2026 Tamil Nadu election results, compares them with 2021, and surfaces key insights about seat shifts, party performance, victory margins, and regional trends.
Built with: Python · pandas · Power BI

🔍 Key Findings
Metric
Value
Total constituencies analyzed 
234
Seats that flipped parties 
144 (61%)
Largest victory margin
98,110 votes — Edappadi (AIADMK)
Smallest victory margin
1 vote — Tiruppattur (TVK)
Average victory margin
16,784 votes

🏆 Party Results — 2026 vs 2021
Party
2021 Seats
2026 Seats
Change

TVK
0 (new party)
108
+108

DMK
133
59
-74

AIADMK
66
47
-19

INC
18
5
-13

PMK
5
4
-1

VCK
4
2
-2

### TVK did not exist in 2021. In their debut election they won 108 seats — 46% of the entire assembly. ###


⚔️ Closest Battles — 2026

Constituency
Candidate
Party
Margin

Tiruppattur
Seenivasa Sethupathy R
TVK
1

Veppanahalli
Srinivasan P S
DMK
138

Kanniyakumari
Thalavai Sundaram N
AIADMK
214

Polur
Abishek R
TVK
227

Tirukkoyilur
Palanisamy S
AIADMK
285

Paramathi-Velur
Sekar S
AIADMK
308

Kulithalai
Suriyanur A Chandran
DMK
579

Kumbakonam
Vinoth
TVK
679

Palani
Ravimanoharan K
AIADMK
693

Tindivanam
Vanni Arasu
VCK
734

📁 Project Structure
tn-election-analysis-2026/
│
├── data/
│   ├── tn_2026_results.csv        # Full 2026 election results
│   ├── tn_2021_results.csv        # Full 2021 election results
│   ├── winner2026.csv             # Winners per constituency 2026
│   ├── winner2021.csv             # Winners per constituency 2021
│   ├── flip_analysis.csv          # Party-wise flip analysis
│   ├── flipped_only.csv           # Only constituencies that flipped
│   ├── closest_battles_2026.csv   # Lowest margin wins
│   ├── regional_shift.csv         # Seats by region and party
│   └── constituency_master.csv    # Master list of constituencies
│
├── notebooks/
│   └── tn_election_analysis.ipynb # Python analysis notebook
│
├── dashboard/
│   └── 1st.pbix                   # Power BI dashboard file
│
└── README.md

🛠️ How to Run
Python Analysis

Clone the repository:
git clone https://github.com/yourusername/tn-election-analysis-2026.git
cd tn-election-analysis-2026

Install dependencies:
pip install pandas matplotlib seaborn jupyter

Open the notebook:
jupyter notebook notebooks/tn_election_analysis.ipynb

Power BI Dashboard

Download and install Power BI Desktop (free)
Open dashboard/1st.pbix
The dashboard loads with all visuals ready

📈 Dashboard Features
KPI Cards — Total seats, flipped seats, largest and closest margin
Party Comparison Chart — 2021 vs 2026 seat counts side by side
Seat Share Donut — 2026 party-wise percentage breakdown
Regional Stacked Bar — Seats by region (Central, Chennai Metro, Delta, Kongu, North, South) broken down by party
Top 5 Victory Margins — Horizontal bar chart colored by party
Closest Battles Table — Color-coded party badges with margin in votes

🗂️ Dataset Columns
winner2026.csv / winner2021.csv
Column
Description

constituency
Constituency name

ac_number
Assembly constituency number

candidate
Winning candidate name

party
Winning party

votes
Votes received

turnout
Voter turnout %

reserved
SC/ST reservation status

region
Geographic region

margin
Victory margin in votes


💡 Insights
TVK's debut is the biggest story — entering as a brand new party and winning an outright majority is historically rare
DMK's collapse from 133 to 59 seats despite being the 2021 winner shows a massive anti-incumbency wave
61% seat turnover indicates one of the most volatile elections in Tamil Nadu history
1 vote margin in Tiruppattur is among the closest election victories in Tamil Nadu history


🙋 About
This is my first data analysis and dashboard project, built to develop skills in:
Data cleaning with Python (pandas)
Exploratory data analysis
Data visualization with Power BI
Dashboard design and storytelling with data

Feedback and suggestions are welcome!

📬 Connect
LinkedIn:https://www.linkedin.com/in/rehan-bagwan-bb59593a6?utm_source=share_via&utm_content=profile&utm_medium=member_android

GitHub: https://github.com/rehanbagwan281-glitch/Tamil-Nadu-Legislative-Assembly-Election-Analysis-2026.git

Data source: Tamil Nadu Election Commission 2026
