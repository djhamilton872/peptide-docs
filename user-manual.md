---
layout: default
title: User Manual
nav_order: 3
---

# User Manual
{: .fs-9 }

Complete documentation for all Peptide Track+ features.
{: .fs-6 .fw-300 }

---

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Getting Started

### Creating an Account

1. Navigate to [peptides.hamiltonsweb.com](https://peptides.hamiltonsweb.com)
2. Click **Sign Up** on the login screen
3. Enter your name, email address, and password
4. Click **Create Account**
5. You'll be automatically logged in

### Password Reset

If you forget your password:
1. Click **Forgot Password** on the login screen
2. Enter your email address
3. Check your email for a reset link
4. Follow the link to create a new password

---

## Dashboard

The Dashboard is your home screen, providing an overview of your peptide tracking activity.

### Stats Cards

Quick metrics at the top of your dashboard:
- **Total Compounds** - Number of compounds you're tracking
- **Total Doses Logged** - All-time dose count
- **This Week's Doses** - Doses logged this week
- **Total Spent** - Sum of compound costs

### Today's Schedule Widget

Shows all doses scheduled for today based on your compound settings:

| Column | Description |
|:-------|:------------|
| Time | When the dose is scheduled |
| Compound | Name of the peptide |
| Type | Injection, drops, or pills |
| Units | Calculated syringe units (for vials) |
| Dose | Amount and unit (e.g., "5 mg") |
| Done | Checkbox to mark complete |

**Actions:**
- Click the **date picker** to view other days
- Click **Print** to print the schedule
- Click **Email** to send schedule to yourself

### Dose Timer

Use to properly space peptide doses:
1. Click a preset time (5, 10, 15, or 30 minutes)
2. Or enter a custom time (1-120 minutes)
3. Timer counts down with audio alert when complete
4. Persists even if you close the browser

---

## Compounds

Manage all your peptide compounds in one place.

### Adding a Compound

**Required Fields:**
- **Name** - e.g., "Semaglutide"
- **Type** - Vial, Pills, or Drops
- **Status** - Active or Completed
- **Dose Amount** - e.g., "5"
- **Dose Unit** - mg or mcg
- **Frequency** - Daily, Weekly, etc.
- **Time of Day** - When to take it

**Optional Fields:**
- **Quantity** - Vial size (e.g., "10 mg")
- **Reconstitution** - mL of BAC water added
- **Concentration** - For drops (e.g., "20mg/mL")
- **Start Date** - When you began
- **Cycle Duration** - For cycling compounds
- **Vendor** - Where purchased
- **Cost** - Price paid
- **Notes** - Additional information

### Compound Types

| Type | Description | Unit Calculation |
|:-----|:------------|:-----------------|
| **Vial** | Injectable peptide | (dose_mg / (total_mg / reconstitution_ml)) × 100 |
| **Drops** | Sublingual drops | (dose_mg / concentration_mg_ml) × 20 |
| **Pills** | Oral tablets/capsules | N/A |

### Frequency Options

| Frequency | Description |
|:----------|:------------|
| Daily | Once per day |
| Twice Daily | Two times per day |
| Three Times Daily | Three times per day |
| Every Other Day | Alternating days |
| Every X Days | Custom interval |
| Weekly | Once per week |
| Custom Days | Select specific days |

---

## Doses

Log and track all your dose administrations.

### Logging a Dose

**From Today's Schedule (Easiest):**
- Check the **Done** checkbox next to any scheduled dose
- Automatically logged with current time

**Manual Entry:**
1. Click **Add Dose**
2. Select the **Compound**
3. Enter **Date** and **Time**
4. Enter **Dose Amount** and **Unit**
5. Optional: Add injection site and notes
6. Click **Save Dose**

### Dose History

Doses are organized by time period:
- Morning (6 AM - 12 PM)
- Afternoon (12 PM - 5 PM)
- Evening (5 PM - 9 PM)
- Night (9 PM - 6 AM)

### Exporting Doses

1. Click **Export** in Doses view
2. Choose format: **PDF** or **CSV**
3. Select date range
4. Download the file

---

## Lab Results

Track your lab tests and monitor biomarkers over time.

### Adding Lab Results

1. Click **Add Lab Result**
2. Enter: Test Date, Test Name, Result Value, Unit
3. Optional: Reference Range, Lab Name, Notes
4. Click **Save Lab Result**

### Lab Result Limits

| Plan | Annual Lab Results |
|:-----|:-------------------|
| Free | 10 per year |
| Standard | 50 per year |
| Premium | Unlimited |

---

## Budget

Track spending on your peptide therapy.

### Categories

- Compounds
- Supplies
- Lab Tests
- Consultations
- Shipping
- Other

---

## Vendors

Manage your peptide suppliers with contact info, websites, and notes.

---

## Supplies

Track your peptide-related supplies inventory:
- Syringes
- Needles
- BAC Water
- Alcohol Swabs
- Sharps Container
- Storage containers

---

## Settings

### Profile Tab
Edit your name and email address.

### Display Tab
- Dark/Light mode
- Time format (12/24 hour)
- Date format
- Day start time
- Default view

### Notifications Tab
- Email notifications
- Dose reminders
- Low supply alerts

### Data Tab
- Data retention settings
- Export all data
- Delete account

### Billing Tab
- View current plan
- Usage statistics
- Upgrade/downgrade
- Cancel subscription

### Support Tab
- Report issues directly from the app
- Contact support

### Help Tab
- Quick start guide
- Documentation links

---

## Subscription Plans

| Feature | Free | Standard | Premium |
|:--------|:-----|:---------|:--------|
| Price | $0/mo | $9.99/mo | $19.99/mo |
| Compounds | 3 | Unlimited | Unlimited |
| Lab Results | 10/year | 50/year | Unlimited |
| Data Export | ❌ | ✅ | ✅ |
| Priority Support | ❌ | ✅ | ✅ |

---

## Troubleshooting

### Schedule Not Showing Doses
- Verify compound **Status** is "Active"
- Check **Frequency** settings
- Confirm **Start Date** is today or earlier
- For custom days, verify current day is selected

### Timer Notification Not Working
1. Click 🔔 button to enable notifications
2. Allow when prompted by browser
3. Check system notification settings

### Data Not Syncing
1. Check internet connection
2. Refresh the page
3. Log out and back in
4. Clear browser cache

---

## Support

- **Email:** [support@hamiltonsweb.com](mailto:support@hamiltonsweb.com)
- **In-App:** Settings → Support → Report an Issue

---

[Back to Quick Start]({% link quick-start.md %}){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[Back to Home]({% link index.md %}){: .btn .fs-5 .mb-4 .mb-md-0 }
