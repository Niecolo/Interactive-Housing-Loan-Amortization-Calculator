

## Input Fields Explained

### 🏦 Loan Details Section

| Field | Description | Example | Tips |
|-------|-------------|---------|------|
| **Loan Amount (₱)** | Total principal you're borrowing | 3,000,000 | Enter the actual loan amount after down payment |
| **Annual Interest Rate (%)** | Yearly interest rate charged by lender | 6.5 | Check your loan agreement for the exact rate |
| **Loan Term (years)** | Duration of the loan | 20 | Common terms: 10, 15, 20, 25, 30 years |
| **Payment Frequency** | How often you make payments | Monthly | Bi-weekly saves more interest over time |
| **First Payment Date** | When your first payment is due | 2026-03-01 | Usually 30 days after loan closing |

---

## Payment Tracking Features

This is where the calculator shines! You can track **four different types** of additional principal payments:

### 1. 🔄 Recurring Extra Payment

**What it does:** Adds a fixed extra amount to **every single payment**.

**Best for:** People who can consistently afford a bit more each month.

**Example:**
- Base payment: ₱22,500/month
- Recurring extra: ₱5,000
- Total paid each month: ₱27,500

**How to use:**
1. Enter the extra amount you want to add to each payment
2. This amount is applied to **principal only**
3. Watch your loan term shrink dramatically!

---

### 2. 📅 One-Time Extra Payment

**What it does:** Applies a **lump sum** payment on a specific date.

**Best for:** Bonus money, tax refunds, inheritance, or windfalls.

**Example:**
- One-time amount: ₱100,000
- One-time date: December 15, 2026
- This entire amount goes toward reducing principal

**How to use:**
1. Enter the lump sum amount
2. Select the date you plan to make this payment
3. The calculator shows the impact from that date forward

---

### 3. 📈 Annual Increase

**What it does:** **Automatically increases** your extra payment by a set amount each year.

**Best for:** People expecting salary increases or wanting to ramp up payments over time.

**Example:**
- Recurring extra: ₱5,000/month (Year 1)
- Annual increase: ₱1,000
- Year 2: ₱6,000/month extra
- Year 3: ₱7,000/month extra
- And so on...

**How to use:**
1. Set your base recurring extra payment
2. Enter how much you want to increase it each year
3. See the compounding effect on your loan term!

---

### 4. 🎯 Custom Payments

**What it does:** Allows you to schedule **multiple specific payments** at specific times.

**Best for:** Irregular income, planned bonuses, or strategic payment schedules.

**Format:** `Month:Amount, Month:Amount, ...`

**Examples:**
```
12:50000, 24:50000, 36:50000
```
- ₱50,000 extra at month 12
- ₱50,000 extra at month 24
- ₱50,000 extra at month 36

```
6:25000, 12:100000, 18:25000
```
- ₱25,000 at month 6
- ₱100,000 at month 12
- ₱25,000 at month 18

**How to use:**
1. List payments as `MonthNumber:Amount`
2. Separate multiple entries with commas
3. Month 1 = first payment, Month 13 = start of year 2, etc.

---

## Understanding the Results

### 📊 Summary Cards

After clicking **Calculate**, you'll see 8 summary cards:

| Card | What It Shows | Why It Matters |
|------|---------------|----------------|
| **Base Monthly Payment** | Your required payment without extras | Your minimum obligation |
| **Total Interest (Base)** | Interest paid on original schedule | What you'd pay without extras |
| **Total Interest (With Extras)** | Interest with your extra payments | What you'll actually pay |
| **Interest Saved** | Difference between base and actual | **Money kept in your pocket!** |
| **Original Payoff Date** | When loan ends without extras | Your original finish line |
| **New Payoff Date** | When loan ends with extras | Your new, earlier finish line |
| **Time Saved** | Years and months shaved off | How much faster you're debt-free |
| **Total Payments** | Total of all payments | Principal + Interest combined |

---

### 📈 Impact Section

This yellow-highlighted section shows:

| Metric | Description |
|--------|-------------|
| **Total Extra Principal Paid** | Sum of all your additional payments |
| **Payments Reduced By** | Number of payments eliminated |
| **Interest Reduction %** | Percentage of interest saved |
| **Effective Interest Rate** | Your true rate after extra payments |

---

### 📊 Progress Bar

Visual representation of your loan payoff:
- **Start:** Original loan amount
- **Current Balance:** Remaining after all scheduled payments
- **Paid:** Total principal reduced
- **Percentage:** How far along you are

---

### 📋 Amortization Table

Detailed payment-by-payment breakdown:

| Column | Description |
|--------|-------------|
| **#** | Payment number |
| **Date** | When payment is due |
| **Payment** | Base payment amount |
| **Extra** | Additional principal (highlighted in green) |
| **Principal** | Portion going to loan balance |
| **Interest** | Portion going to interest |
| **Total Principal** | Cumulative principal paid |
| **Balance** | Remaining loan balance |

**Table View Options:**
- **Show All Payments** – Every single payment
- **Yearly Summary** – Aggregated by year
- **First Year + Last** – Quick overview
- **Custom Range** – Select specific months

---

## Step-by-Step Tutorials

### Tutorial 1: Basic Calculation (No Extra Payments)

**Scenario:** You want to know your basic monthly payment for a ₱3M loan.

**Steps:**
1. Open the calculator
2. Enter **Loan Amount:** 3000000
3. Enter **Interest Rate:** 6.5
4. Enter **Loan Term:** 20
5. Select **Payment Frequency:** Monthly
6. Choose **First Payment Date**
7. Leave all extra payment fields at 0
8. Click **Calculate Amortization**

**Results You'll See:**
- Base monthly payment amount
- Total interest over 20 years
- Full amortization schedule

---

### Tutorial 2: Adding Recurring Extra Payments

**Scenario:** You can afford an extra ₱10,000/month and want to see the impact.

**Steps:**
1. Complete Tutorial 1 steps first
2. In **Recurring Extra Payment**, enter: 10000
3. Click **Calculate Amortization**

**Expected Results:**
- Loan paid off ~8-10 years early
- Interest savings of ₱1,000,000+
- See green-highlighted rows in table

---

### Tutorial 3: One-Time Lump Sum Payment

**Scenario:** You expect a ₱200,000 bonus in December 2027.

**Steps:**
1. Enter your loan details
2. In **One-Time Extra Payment** section:
   - Amount: 200000
   - Date: 2027-12-01
3. Click **Calculate Amortization**

**What to Watch:**
- Notice the balance drop significantly after that date
- See how many months are eliminated

---

### Tutorial 4: Annual Increase Strategy

**Scenario:** You expect annual raises and want to increase payments by ₱2,000/year.

**Steps:**
1. Enter loan details
2. **Recurring Extra Payment:** 5000
3. **Annual Increase:** 2000
4. Click **Calculate Amortization**

**What Happens:**
- Year 1: Extra ₱5,000/month
- Year 2: Extra ₱7,000/month
- Year 3: Extra ₱9,000/month
- Watch your loan disappear!

---

### Tutorial 5: Custom Payment Schedule

**Scenario:** You receive annual bonuses and want to apply them strategically.

**Steps:**
1. Enter loan details
2. **Custom Payments:** `12:50000, 24:75000, 36:100000`
3. Click **Calculate Amortization**

**This Applies:**
- ₱50,000 at end of Year 1
- ₱75,000 at end of Year 2
- ₱100,000 at end of Year 3

---

### Tutorial 6: Combining All Strategies (Advanced)

**Scenario:** You want maximum optimization using all features.

**Steps:**
1. Enter loan details
2. **Recurring Extra Payment:** 5000
3. **One-Time Extra Payment:** 100000 (Date: 2026-12-01)
4. **Annual Increase:** 1000
5. **Custom Payments:** `12:25000, 24:25000`
6. Click **Calculate Amortization**

**This Combines:**
- ₱5,000 extra every month
- ₱100,000 lump sum in December 2026
- Extra payment increases ₱1,000 each year
- Additional ₱25,000 at months 12 and 24

**Expected Result:**
- Loan paid off in less than half the time
- Massive interest savings

---

### Tutorial 7: Exporting Your Schedule

**Steps:**
1. Calculate your amortization
2. Review the table
3. Click **Export CSV** button
4. File downloads as: `amortization_schedule_YYYY-MM-DD.csv`
5. Open in Excel, Google Sheets, or any spreadsheet app

**Use Cases:**
- Share with financial advisor
- Import into budgeting software
- Print for records
- Create custom charts

---

## Tips & Strategies

### 💡 Money-Saving Tips

1. **Start Small:** Even ₱1,000 extra/month makes a difference
2. **Bi-weekly Payments:** Switch to bi-weekly to make 13 payments/year automatically
3. **Round Up:** Round your payment to the nearest thousand
4. **Tax Refunds:** Apply entire refunds to principal
5. **Annual Reviews:** Re-calculate when rates change or you get raises

### 📊 Comparison Strategy

Use the calculator to compare scenarios:

| Scenario | Extra Payment | Time Saved | Interest Saved |
|----------|---------------|------------|----------------|
| Base | ₱0 | - | - |
| Conservative | ₱5,000/month | ~5 years | ~₱500K |
| Aggressive | ₱15,000/month | ~10 years | ~₱1.2M |
| Windfall | ₱100K/year | ~8 years | ~₱900K |

### 🎯 Goal-Setting Framework

1. **Calculate your base** – Know your minimum
2. **Determine affordable extra** – Review your budget
3. **Set milestones** – "Pay off 5 years early"
4. **Track progress** – Re-run calculator annually
5. **Adjust as needed** – Increase extras with income

### ⚠️ Important Considerations

- **Prepayment Penalties:** Check if your lender charges fees for early payoff
- **Emergency Fund:** Ensure you have 3-6 months expenses before making extra payments
- **Higher Interest Debt:** Pay off credit cards first (higher rates)
- **Investment Opportunities:** Compare loan rate vs. potential investment returns

---

## FAQ

### Q: Can I use this for other types of loans?
**A:** Yes! This works for any amortizing loan: car loans, personal loans, student loans, or business loans. Just adjust the currency symbol mentally.

### Q: What if my interest rate is variable?
**A:** Run separate calculations for different rate scenarios (e.g., 5%, 6%, 7%) to see the range of possible outcomes.

### Q: Does the extra payment actually go to principal?
**A:** In this calculator, yes – 100% of extra payments reduce principal. In real life, confirm with your lender that extras are applied to principal, not future interest.

### Q: Why is my bi-weekly payment different from monthly/2?
**A:** Bi-weekly payments result in 26 payments/year = 13 full monthly payments, accelerating payoff.

### Q: Can I print the amortization schedule?
**A:** Yes! Use your browser's Print function (Ctrl+P) or export to CSV and format in Excel.

### Q: What does "Effective Interest Rate" mean?
**A:** It's your true interest rate considering the faster payoff. Extra payments effectively reduce your rate because you pay interest for fewer years.

### Q: Is my data saved anywhere?
**A:** No. All calculations happen in your browser. Nothing is stored or transmitted. Close the browser and data is gone.

### Q: Can I use this on my phone?
**A:** Yes! The calculator is fully responsive and works on smartphones, tablets, and desktops.

### Q: What if I make a mistake in the custom payments field?
**A:** The calculator ignores invalid entries. Format must be `Month:Amount` with commas between entries.

### Q: How accurate is this calculator?
**A:** Very accurate for standard fixed-rate loans. However, always verify with your lender's official statements for actual balances.

---
