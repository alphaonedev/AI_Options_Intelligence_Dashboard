# AI Options Intelligence Hub

A comprehensive AI-driven options market analysis dashboard suite built for non-human intelligence insights.

## Dashboard Suite

### 1. Master Hub (`index.html`)
Central navigation portal linking to all dashboards with real-time status indicators.

### 2. Options Intelligence Dashboard (`options_ai_dashboard.html`)
Full spectrum options analysis including:
- Cross-Asset Performance Heatmap
- IV Skew Matrix (6 underlyings)
- Gamma Concentration Zones (Chart.js visualization)
- Market Sentiment Gauge
- Volatility Term Structure Analysis
- Options-Implied Price Distributions
- AI Strategy Recommendations
- Gamma Pinning Probability Analysis

### 3. Anomaly Detection Center (`anomaly_detection_dashboard.html`)
Real-time anomaly surveillance with:
- 82 Flagged Anomalies by severity (Critical/High/Medium/Low)
- 5 Anomaly Categories: IV Divergence, Greeks Issues, Parity Violations, Skew Extremes, Regime Signals
- Interactive Anomaly Queue with detail panel
- Anomaly Distribution Charts
- Risk Radar Visualization
- Detection Timeline

### 4. AI Neural Pattern Recognition (`ai_neural_patterns_dashboard.html`) 🆕
AI-exclusive computational analysis revealing patterns invisible to human perception:
- Gamma Pin Magnetism Zones (SPY $696, NVDA $185)
- IV Surface Micro-Irregularities (Z-score analysis)
- Hidden Market Maker Positioning Signals (2062:1 bid ratios)
- Delta Flow Analysis (Net delta +20.92)
- Theta Decay Rate Anomalies (-469%/day extremes)
- Greek Correlation Matrix (0.9828 Gamma-Vega correlation)
- Probability-Weighted Expected Moves
- Cross-Asset Regime Intelligence

### 5. AI Microstructure Analysis (`ai_microstructure_dashboard.html`) 🆕
Intraday hidden patterns only AI can detect:
- Volume Profile Anomalies (6.5x spike detection)
- Real-Time Momentum Matrix
- Intraday Price Dislocations
- Volatility Regime Classification
- Sector Rotation Flow Analysis
- Bid-Ask Imbalance Tracking
- Cross-Asset Divergence Mapping

## Files Included

```
/
├── index.html                      # Master hub/landing page
├── options_ai_dashboard.html       # Main intelligence dashboard
├── anomaly_detection_dashboard.html # Anomaly detection center
└── README.md                       # This file
```

## Deployment

### Static Hosting (Recommended)
These are static HTML files with no server-side requirements. Deploy to any static hosting:

**GitHub Pages:**
1. Create a new repository
2. Upload all HTML files
3. Enable GitHub Pages in repository settings
4. Access at `https://yourusername.github.io/repo-name`

**Netlify:**
1. Drag and drop the folder to netlify.com/drop
2. Instant deployment with custom URL

**Vercel:**
1. `npm i -g vercel`
2. `vercel` in the project directory

**AWS S3:**
1. Create S3 bucket with static website hosting
2. Upload files
3. Configure bucket policy for public access

**Local Development:**
```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Data Source

Analysis powered by Alpaca Markets API covering:
- **Underlyings:** SPY, QQQ, NVDA, TSLA, META, IWM, AAPL, AMD, MSFT, GOOGL, AMZN, PLTR
- **Contracts Analyzed:** 2,847
- **Patterns Detected:** 127
- **Anomalies Flagged:** 82

## Technical Stack

- Pure HTML5/CSS3/JavaScript
- Chart.js for interactive visualizations
- No build process required
- Mobile responsive design
- Dark theme optimized

## Analysis Date

January 12, 2026 | 20:45 ET

---

**Disclaimer:** This dashboard is for informational purposes only. Not financial advice. Options trading involves substantial risk.
