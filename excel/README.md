Excel workbook for the financial statement analysis

# Dynamic Order Tracking Dashboard (Excel)

An interactive Excel dashboard that tracks the status of orders from dispatch to delivery, using checkboxes, a progress bar and automatic status labels.

## What it does
- Tracks each item through three stages: **Order Dispatch**, **On the way** and **Delivery Today**
- Uses **checkboxes** so the status is updated with a single click
- Shows a **progress bar** (0%, 33%, 67%, 100%) for every item
- Shows an automatic **status label** with colour coding: Pending, Dispatched, Out for Delivery and Delivered

## Features
- Checkbox controls linked to cells
- Progress calculated from the completed stages [formula used, e.g. COUNTIF or SUM]
- Status text generated with [IF / IFS formula]
- Conditional formatting: data bars for progress and colour rules for each status
- Separate DASHBOARD and WORK sheets [add if your dashboard sheet has charts or summary counts]

## Tools used
Microsoft Excel: checkboxes, conditional formatting, data bars, [IF/COUNTIF formulas], [charts/pivot tables on the dashboard if used]

## Files
- `excel/order-tracking-dashboard.xlsx`: Excel workbook

## What I learned
Building an interactive tracker in Excel with form controls, formulas and conditional formatting.
