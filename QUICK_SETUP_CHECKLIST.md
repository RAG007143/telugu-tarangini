# Quick Setup Checklist - Intraday Trading Strategy

## ✅ Pre-Setup Requirements
- [ ] TradingView account (free or paid)
- [ ] Access to Pine Script editor
- [ ] 15-minute chart timeframe selected
- [ ] Asset selected (stocks, forex, crypto, etc.)

## 🚀 5-Minute Setup Process

### Step 1: Copy Strategy Code
- [ ] Open `intraday_trading_strategy.pine` file
- [ ] Copy entire code content (Ctrl+A, Ctrl+C)

### Step 2: TradingView Setup
- [ ] Open TradingView.com
- [ ] Open Pine Script Editor (bottom of screen)
- [ ] Paste the code into editor
- [ ] Click "Add to Chart"

### Step 3: Initial Configuration
- [ ] Set timeframe to **15 minutes**
- [ ] Adjust trading session (default: 9:30-15:30 EST)
- [ ] Verify strategy appears on chart

### Step 4: Customize Settings (Optional)
- [ ] EMA settings (Fast: 9, Slow: 21)
- [ ] RSI settings (Length: 14, OB: 70, OS: 30)
- [ ] Volume multiplier (1.5x default)
- [ ] ATR stop loss (2.0x default)

### Step 5: Enable Alerts
- [ ] Right-click on chart → "Add Alert"
- [ ] Select "Intraday Power Strategy"
- [ ] Choose alert conditions:
  - [ ] Long Entry Alert
  - [ ] Short Entry Alert
- [ ] Set notification method (email/SMS/app)

## 📊 Visual Confirmation Checklist

After setup, verify you see:
- [ ] Blue line (Fast EMA)
- [ ] Red line (Slow EMA) 
- [ ] Orange lines (Previous day high/low)
- [ ] RSI indicator panel below
- [ ] Statistics table (top right)
- [ ] Green "BUY" labels when conditions met
- [ ] Red "SELL" labels when conditions met

## 🎯 First Trade Checklist

Before your first live trade:
- [ ] Paper trade for 1-2 weeks minimum
- [ ] Verify signal accuracy
- [ ] Test alert notifications
- [ ] Calculate position size (1-2% risk per trade)
- [ ] Set broker stop loss orders
- [ ] Document trade plan

## ⚙️ Optimization Checklist (After 2+ Weeks)

- [ ] Review win rate (aim for >50%)
- [ ] Check profit factor (aim for >1.2)
- [ ] Analyze maximum drawdown
- [ ] Optimize parameters if needed:
  - [ ] Adjust EMA periods for market
  - [ ] Modify RSI levels
  - [ ] Change volume multiplier
  - [ ] Adjust ATR stop loss

## 🔧 Troubleshooting

### Strategy Not Showing Signals?
- [ ] Check if timeframe is 15 minutes
- [ ] Verify trading session matches market hours
- [ ] Ensure volume data is available
- [ ] Check RSI isn't in extreme zones

### Too Many False Signals?
- [ ] Increase volume multiplier (1.5 → 2.0)
- [ ] Tighten RSI range (40-80 → 45-75)
- [ ] Use longer EMA periods (9/21 → 12/26)

### Missing Good Moves?
- [ ] Decrease volume multiplier (1.5 → 1.2)
- [ ] Widen RSI range (40-80 → 35-85)
- [ ] Use shorter EMA periods (9/21 → 8/13)

## 📱 Mobile Setup

For mobile monitoring:
- [ ] Install TradingView mobile app
- [ ] Log in to same account
- [ ] Enable push notifications
- [ ] Test alert delivery
- [ ] Bookmark strategy chart
- [ ] Practice mobile order entry

## 🔔 Alert Message Examples

**Buy Alert**: "BUY Signal: EMA Crossover + RSI + Volume Confirmed"
**Sell Alert**: "SELL Signal: EMA Crossunder + RSI + Volume Confirmed"

Customize messages to include:
- [ ] Asset symbol
- [ ] Current price
- [ ] Stop loss level
- [ ] Timestamp

## 💡 Pro Tips

- [ ] Start with small position sizes
- [ ] Keep a trading journal
- [ ] Review trades weekly
- [ ] Don't override strategy signals
- [ ] Monitor during active market hours
- [ ] Have backup plan for internet/power issues

---

**Ready to Trade?** ✅ Complete all checkboxes before live trading!