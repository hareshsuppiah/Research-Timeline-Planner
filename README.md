# 📊 Research Timeline Planner with Gantt Chart

**A powerful Excel-based tool for planning and tracking complex multi-year research projects with automatic visual timelines.**

Perfect for PhD students, postdocs, research teams, and anyone managing complex academic research with multiple milestones and deliverables.

---

![Research Timeline Planner Screenshot](CleanShot%202025-09-30%20at%2014.17.09@2x.png)
*Example showing a PhD timeline with confirmation subtasks, study planning, and automatic Gantt chart visualization*

---

## 📥 How to Download

**Option 1: Direct Download (Easiest)** ⭐
1. Click on the file name: **`Research_Timeline_Planner.xlsx`**
2. Click the **"Download"** button (or **"Download raw file"** button in the top right)
3. Save the file to your computer
4. Open with Microsoft Excel, Google Sheets, or LibreOffice

**Option 2: Download Entire Repository**
1. Click the green **"Code"** button at the top of this page
2. Select **"Download ZIP"**
3. Extract the ZIP file on your computer
4. Open the Excel file from the extracted folder

### ✅ Compatibility
- ✅ **Best experience:** Microsoft Excel 2016 or later
- ⚠️ **Google Sheets:** Works, but conditional formatting may have limited functionality
- ⚠️ **LibreOffice Calc:** Compatible, but some color formatting may differ
- 💡 **Tip:** Enable content/formulas if prompted when opening

---

## 📋 Table of Contents

- [Use Cases](#-use-cases)
- [Key Features](#-key-features)
- [Getting Started](#-getting-started)
- [Column Descriptions](#-column-descriptions)
- [Customization Guide](#-customization-guide)
- [Technical Details](#-technical-details)
- [Troubleshooting](#-troubleshooting)
- [Version History](#-version-history)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎯 Use Cases

This tool is designed for researchers at all career stages who need to plan and track complex, multi-year projects with interconnected milestones and deliverables.

### 👨‍🎓 PhD/Masters Students
- **Candidature planning:** Track confirmation, mid-candidature, and pre-submission milestones
- **Thesis chapter timelines:** Coordinate literature review, data collection, analysis, and writing
- **Multi-study research programs:** Manage multiple studies (pilot, main study, follow-ups)
- **Comprehensive exam preparation:** Plan reading, writing, and defense timelines
- **Publication tracking:** Monitor paper submission and revision cycles

### 🔬 Postdoctoral Researchers
- **Grant deliverable tracking:** Ensure you meet funding body requirements on time
- **Multi-project coordination:** Balance multiple research streams and collaborations
- **Paper submission timelines:** Plan strategic submission to high-impact journals
- **Fellowship milestone planning:** Track progress toward tenure or permanent positions
- **Lab transition planning:** Coordinate equipment, hiring, and project startup

### 👥 Research Teams
- **Collaborative project management:** Coordinate work across multiple team members
- **Multi-study coordination:** Track overlapping studies and shared resources
- **Grant reporting deadlines:** Never miss a progress report or ethics renewal
- **Lab milestone tracking:** Visualize team priorities and dependencies

### 👩‍🏫 Research Supervisors
- **Student progress monitoring:** Track multiple students simultaneously
- **Lab activity planning:** Coordinate equipment use, space, and resources
- **Group milestone coordination:** Align individual projects with lab goals
- **Succession planning:** Plan for student graduations and new recruits

---

## ✨ Key Features

### 🎨 **Automatic Visual Gantt Chart**
Timeline automatically updates when you change start/end dates. No manual drawing required.

### 📂 **Hierarchical Structure**
Organize your work into **Projects** → **Milestones** → **Subtasks** for crystal-clear planning.

### 🚦 **Color-Coded Status Tracking**
- **Status dropdown:** Confirmed (🟢 Green) / Tentative (🟡 Yellow) / At Risk (🔴 Red)
- **Progress dropdown:** Not Started (⚫ Grey) / In Progress (🟡 Yellow) / Complete (🟢 Green)

### 📅 **Extended Timeline Range**
Pre-configured for **Oct 2024 - Dec 2032** (99 months), easily extensible to any date range.

### 🔒 **Frozen Panes**
Scroll through long timelines while keeping project names visible.

### ✅ **Date Validation**
Uses real Excel dates (MMM-YY format) with smart formulas for reliable month-based comparison.

### 🔧 **Smart Formulas**
Uses `EOMONTH` function for accurate month-based Gantt chart logic.

### 📖 **Comprehensive Instructions**
Includes detailed instruction sheet with customization tips and troubleshooting.

### 🎯 **Pre-Populated Example**
Comes with a complete PhD confirmation example you can adapt or replace.

### ♾️ **Infinitely Extensible**
Add unlimited projects, milestones, and tasks. Extend timeline beyond 2032 by copying columns.

---

## 🚀 Getting Started

### Step 1: Open the File
Download `Research_Timeline_Planner.xlsx` and open in your preferred spreadsheet application (Excel recommended).

### Step 2: Review the Example
The template includes a pre-populated PhD timeline example showing:
- Confirmation milestone with 8 subtasks
- Example Delphi study with complete research workflow
- Other PhD milestones (mid-candidature, pre-submission)

### Step 3: Customize for Your Project
**Option A: Adapt the Example**
- Replace example project names with your own
- Update dates to match your timeline
- Modify tasks to reflect your research plan

**Option B: Start Fresh**
- Clear the example rows (keep header row)
- Add your projects, milestones, and tasks
- Enter start and end dates

### Step 4: Track Progress
As your research progresses:
1. Update **Status** dropdown to reflect confidence level
2. Update **Progress** dropdown when tasks begin or complete
3. Add new tasks as needed
4. Adjust dates if timelines shift

### Step 5: Use for Communication
- Take screenshots for supervisor meetings
- Export as PDF for grant applications
- Share with collaborators for coordination

---

## 📊 Column Descriptions

| Column | Name | Purpose | Format/Options |
|--------|------|---------|----------------|
| **A** | **Project/Milestone/Task** | Hierarchical name of activity | Text (use indentation for subtasks) |
| **B** | **Start Date** | When activity begins | `MMM-YY` (e.g., Jan-25) |
| **C** | **Finish Date** | When activity completes | `MMM-YY` (e.g., Mar-25) |
| **D** | **Dependencies** | What must be completed first | Text (reference other tasks) |
| **E** | **Risks** | Potential delays or challenges | Text (be specific) |
| **F** | **Outputs** | Deliverables, publications, approvals | Text (what you'll produce) |
| **G** | **Status** | Risk/confidence level | Dropdown: Confirmed 🟢 / Tentative 🟡 / At Risk 🔴 |
| **H** | **Progress** | Completion state | Dropdown: Not Started ⚫ / In Progress 🟡 / Complete 🟢 |
| **I+** | **Timeline** | Automatic Gantt chart visualization | Auto-generated (don't edit manually) |

### Column Usage Tips

**Project/Milestone/Task (Column A)**
- Use **bold** for top-level projects
- Use indentation for visual hierarchy:
  - Project (no indent)
    - Milestone (1-2 spaces)
      - Subtask (3-4 spaces)

**Start/Finish Dates (Columns B & C)**
- Use consistent date format: `Jan-25`, `Feb-25`, etc.
- Excel will auto-format if you type dates like `1/1/2025`
- End date must be same month or later than start date

**Dependencies (Column D)**
- Reference task names: "Ethics approval", "Pilot study complete"
- Use this to identify critical path in your project

**Risks (Column E)**
- Be specific: "Recruitment may be slow in summer months"
- Think about: timing, resources, external factors, approvals

**Outputs (Column F)**
- Tangible deliverables: "Journal article submitted", "Chapter draft"
- Use this column to ensure every task produces something

---

## 🎨 Customization Guide

### Extending the Timeline Beyond 2032

1. **Select the last column** in the Gantt chart area (currently Dec-32)
2. **Copy the column** (Ctrl+C / Cmd+C)
3. **Paste** into the next column to the right
4. **Update the date** in the header row (e.g., Jan-33)
5. **Repeat** as many times as needed
6. All formulas will automatically adjust

### Customizing Dropdown Values and Colors

**Status Dropdown:**
1. Select any cell in the **Status** column (Column G)
2. Go to **Data** → **Data Validation**
3. Modify the list values (default: Confirmed, Tentative, At Risk)
4. To change colors: **Home** → **Conditional Formatting** → **Manage Rules**
5. Edit the rule for each status value

**Progress Dropdown:**
1. Same process as Status dropdown
2. Default values: Not Started, In Progress, Complete
3. Modify conditional formatting rules to change colors

### Adding New Dropdown Options

Want to track additional information? Create a new dropdown:
1. Insert a new column where desired
2. **Data** → **Data Validation** → **List**
3. Enter your values separated by commas
4. (Optional) Add conditional formatting for color coding

### Changing the Date Range

To start your timeline at a different date:
1. Update the first column header (Column I) to your start month
2. Update subsequent column headers sequentially
3. Gantt formulas will automatically adapt

---

## 🔧 Technical Details

<details>
<summary>Click to expand technical information</summary>

### Gantt Chart Formula Structure

The Gantt chart uses a formula that compares each month column against the task's start and end dates:

```excel
=IF(AND($B2<>"", $C2<>"", EOMONTH(I$1,0)>=EOMONTH($B2,0), EOMONTH(I$1,0)<=EOMONTH($C2,0)), 1, "")
```

**How it works:**
- `EOMONTH(I$1,0)` converts column header date to end-of-month
- `EOMONTH($B2,0)` converts start date to end-of-month
- `EOMONTH($C2,0)` converts finish date to end-of-month
- Compares by month (ignores day of month)
- Returns `1` if current column month is within task date range
- Returns blank otherwise

### Conditional Formatting

**Gantt Chart Bars:**
- Cells containing `1` are filled with color
- Number format `;;;` hides the value (shows color only)

**Status Column:**
- Confirmed → Green fill
- Tentative → Yellow fill
- At Risk → Red fill

**Progress Column:**
- Not Started → Grey fill
- In Progress → Yellow fill
- Complete → Green fill

### Data Validation

Dropdowns use **Data Validation** with:
- **List** source type
- Custom **input message** to guide users
- **Error alert** to prevent invalid entries

### Frozen Panes

- Rows 1-2 frozen (headers always visible)
- Columns A-H frozen (task details always visible)
- Allows scrolling through long timelines while maintaining context

### Copy-Paste Friendly

All formulas use proper cell references:
- `$` symbols anchor columns/rows correctly
- Dragging or copying rows automatically adjusts formulas
- New tasks inherit formatting and formulas from above

</details>

---

## ❓ Troubleshooting

### Problem: Gantt chart bars not showing

**Solutions:**
1. ✅ Check that **Start Date** (Column B) and **Finish Date** (Column C) are filled
2. ✅ Verify dates are in `MMM-YY` format (e.g., `Jan-25`, not `January 2025`)
3. ✅ Ensure **Finish Date** is same month or later than **Start Date**
4. ✅ Check that the column header dates span your task's date range
5. ✅ Verify conditional formatting rules are active (Home → Conditional Formatting)

### Problem: Dropdown colors not changing

**Solutions:**
1. ✅ Check **Conditional Formatting** rules (Home → Conditional Formatting → Manage Rules)
2. ✅ Ensure dropdown values exactly match the rule criteria (case-sensitive)
3. ✅ If using Google Sheets: Some formatting may not transfer perfectly
4. ✅ Re-apply conditional formatting rules if necessary

### Problem: Dates not formatting correctly

**Solutions:**
1. ✅ Type dates as `1/2025` and let Excel auto-format to `Jan-25`
2. ✅ Avoid typing as plain text like "January 2025"
3. ✅ Use Excel's **Format Cells** → **Custom** → `mmm-yy` for manual formatting
4. ✅ Ensure column is formatted as **Date**, not **Text**

### Problem: Timeline doesn't extend far enough

**Solution:**
1. ✅ Copy the last column in the Gantt area
2. ✅ Paste to the right as many times as needed
3. ✅ Update each header to the next sequential month
4. ✅ Formulas auto-adjust for the new columns

### Problem: Want to add more rows

**Solution:**
1. ✅ Insert row anywhere in the task list
2. ✅ Copy formulas from row above (select row, Ctrl+C, paste)
3. ✅ Conditional formatting and data validation automatically extend

### Problem: File won't open or looks broken

**Solutions:**
1. ✅ Make sure you're using Excel 2016 or later (or Google Sheets/LibreOffice)
2. ✅ Enable macros/content if prompted (file has no macros, so this is safe)
3. ✅ Try downloading again - file may have corrupted during download
4. ✅ Check file size - should be ~30-40 KB

### Problem: Need help with advanced customization

**Solution:**
1. 📧 Open an issue on GitHub with your question
2. 📧 Contact the creator (see [Contact](#-contact) section)
3. 📖 Review the **Instructions** sheet within the Excel file

---

## 📝 Version History

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

**Current Version: v1.0.0**

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- 🐛 Reporting bugs
- 💡 Suggesting new features
- 🔧 Submitting improvements
- 📧 Contact information

---

## 📄 License

This project is licensed under the **MIT License**.

You are free to:
- ✅ Use commercially
- ✅ Modify and adapt
- ✅ Distribute
- ✅ Use privately

See [LICENSE](LICENSE) for full details.

---

## 📬 Contact

**Creator:** Haresh Suppiah

- 🌐 **GitHub:** [@hareshsuppiah](https://github.com/hareshsuppiah)
- 📧 **Email:** [your-email@example.com] *(Update with your actual email)*
- 💼 **LinkedIn:** [Add your LinkedIn if desired]

---

## 🌟 Found This Useful?

If this tool helped your research planning, consider:
- ⭐ **Starring this repository** on GitHub
- 🔗 **Sharing** with colleagues and students
- 💬 **Providing feedback** via GitHub issues
- 🤝 **Contributing** improvements back to the project

---

## 📸 Screenshot Instructions

**For maintainers:** After taking screenshots:
1. Take a screenshot of the Excel file showing both the task list and Gantt chart
2. Save as `screenshot.png` in the repository root
3. (Optional) Take a second screenshot showing the color-coded dropdown menus in action
4. Save as `screenshot-dropdowns.png` if creating a second image
5. Commit and push both images to the repository
6. Update this README to reference additional screenshots if added

---

**Built for researchers, by researchers. Happy planning! 🎓📊**