# JackpotAnalytics: Lottery Trends & Probability Insights

**Author:** Darious Brown  
**GitHub:** [Dare215](https://github.com/Dare215)  
**Email:** dariousbrown3@icloud.com  

## 1) Project Overview
JackpotAnalytics is a statistical exploration of Powerball, Mega Millions, and Pick10 lottery games.  
The analysis aims to uncover draw trends, frequencies, randomness, and the actual odds players face, targeting responsible, regular lottery ticket buyers.

## 2) Dataset
- **Source:** Official state and national lottery draw archives  
- **Files:**  
  - `powerball_cleaned.csv`  
  - `mega_millions_cleaned.csv`  
  - `pick10_cleaned.csv`  
- **Key Variables:** `Draw Date`, `Winning Numbers`, `Jackpot Amount`, `Winners Count`

## 3) Key Features
- **Frequency Analysis:** Determine how often each number appears across thousands of draws.
- **Randomness Insights:** Validate that no number holds a consistent “lucky” status.
- **Game Comparison:** Analyze differences between Powerball, Mega Millions, and Pick10 odds.
- **Probability Demonstration:** Visualize the minuscule winning chances in large pool lotteries.
- **Budget Awareness:** Provide data-driven reminders about the role of chance.

## 4) Project Structure
```
JackpotAnalytics/
│── Lottery ticket Buyers.ipynb      # Analysis & visualizations
│── DSC640Loto.docx                   # Written audience-focused summary
│── powerball_cleaned.csv             # Cleaned Powerball draws
│── mega_millions_cleaned.csv         # Cleaned Mega Millions draws
│── pick10_cleaned.csv                # Cleaned Pick10 draws
│── README.md                         # Documentation
```

## 5) How to Run

### Option A — Python / Terminal
```bash
# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate   # Mac/Linux
.venv\Scripts\activate    # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook "Lottery ticket Buyers.ipynb"
```

### Option B — PyCharm
1. Open folder in PyCharm  
2. Configure Python interpreter (point to `.venv`)  
3. Install dependencies from `requirements.txt`  
4. Run the notebook

## 6) Results Summary
- Lottery odds remain under 1% for all players, often closer to 0.0000003% for large national lotteries.
- Number repetition does not increase winning chances — outcomes are fully random.
- High-frequency numbers are a result of randomness, not luck.
- Data shows larger jackpot pools inversely correlate with winning probability.

## 7) Ethical Considerations
- Do not promote gambling to vulnerable groups.
- Ensure transparency when communicating odds.
- Present findings for awareness, not as a gambling strategy.

## 8) Future Enhancements
- Develop an interactive dashboard for real-time lottery trend tracking.
- Include smaller-scale, community-based lotteries for probability comparison.
- Incorporate player spending vs. winnings analysis.

## 9) License
MIT License — Free to use with attribution.
