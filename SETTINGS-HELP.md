# SharePoint Smart Charts — Settings Help

Detailed, field-by-field help for the web part's property pane. The pane is
organized into **three pages**, which act as the three configuration steps:

| Step | Page | What it controls |
|:----:|------|------------------|
| 1 of 3 | **Settings** | Chart identity & structure |
| 2 of 3 | **Appearance** | Colors, labels, axes |
| 3 of 3 | **Advanced** | Analytics, SPC, interactivity, data |

Every row includes the step it lives on. Fields that don't apply to the chart
type you've chosen are hidden entirely (not greyed out), so what you see
depends on the selected **Chart Type**.

> The property pane renders help text only beneath **text fields**. For
> toggles, sliders, and dropdowns the detail below is your reference for what
> that control does.

---

## Step 1 of 3 — Settings page

### Header group

| Field | Control | Step | Help |
|---|---|---|---|
| Show Web Part Header | Toggle | 1 of 3 | Show a title bar above the chart. Turn off for a "floating" chart with no header. |
| Web Part Header | Text | 1 of 3 | Title shown above the chart. Leave blank to hide the title text (the header area stays). |

### Chart Settings group

| Field | Control | Step | Help |
|---|---|---|---|
| Chart Title | Text | 1 of 3 | Heading displayed above the chart itself (inside the chart area). |
| Chart Type | Dropdown | 1 of 3 | Which chart to render. This controls which other fields are shown or hidden across all three pages. |
| Legend Position | Dropdown | 1 of 3 | Where the legend sits (top/bottom/left/right). Disabled when Show Legend is off. |
| Chart Height | Slider | 1 of 3 | Height of the chart in pixels (150–1200). |
| Show Legend | Toggle | 1 of 3 | Show or hide the legend entirely. |
| Stacked | Toggle | 1 of 3 | Stack series (bar, horizontal bar, line, area only). |
| Show Data Table | Toggle | 1 of 3 | Render the chart plus a table of the underlying rows. |
| Show Export Bar | Toggle | 1 of 3 | Show the export controls (PNG / JPEG / CSV / Excel). |
| X Axis Label | Text | 1 of 3 | Label shown beneath the horizontal axis. Hidden for pie, doughnut, KPI, treemap, heatmap. |
| Y Axis Label | Text | 1 of 3 | Label shown beside the vertical axis. Hidden for pie, doughnut, KPI, treemap, heatmap. |
| Histogram Bins | Slider | 1 of 3 | Number of bins (4–50) for the histogram chart type. |

---

## Step 2 of 3 — Appearance page

### Colors group

| Field | Control | Step | Help |
|---|---|---|---|
| Color Palette | Dropdown | 2 of 3 | Palette applied to series (Office, Colorblind, Vibrant, Pastel, Monochrome, Traffic Light, Warm, Cool). |

### Data Labels group

| Field | Control | Step | Help |
|---|---|---|---|
| Show Data Labels | Toggle | 2 of 3 | Print a value on or beside each data point. |
| Value Prefix | Text | 2 of 3 | Text placed before each data label, e.g. a currency symbol or unit. |
| Value Suffix | Text | 2 of 3 | Text placed after each data label, e.g. `%` or `hrs`. |
| Decimal Places | Slider | 2 of 3 | How many decimal places data labels show (0–4). |
| Abbreviate Numbers | Toggle | 2 of 3 | Compact large numbers (e.g. 1.2K, 3.4M) in labels. |

### Axes & Grid group
Hidden entirely for pie, doughnut, KPI, treemap, heatmap, radar.

| Field | Control | Step | Help |
|---|---|---|---|
| Y Min | Text | 2 of 3 | Lowest value on the vertical axis. Leave blank to auto-scale. |
| Y Max | Text | 2 of 3 | Highest value on the vertical axis. Leave blank to auto-scale. |
| Log Scale (Y) | Toggle | 2 of 3 | Plot the vertical axis on a logarithmic scale. |
| Log Scale (X) | Toggle | 2 of 3 | Plot the horizontal axis on a logarithmic scale (scatter, bubble only). |
| Step Interpolation | Toggle | 2 of 3 | Draw line/area series as step line segments (line, area only). |
| Show Grid Lines | Toggle | 2 of 3 | Hide or show the chart grid. |
| X Label Rotation | Slider | 2 of 3 | Rotate horizontal-axis labels (0–90°) to fit long category names. |
| X Axis Type | Dropdown | 2 of 3 | Treat the X axis as automatic, category, or time (bar, line, area). |

---

## Step 3 of 3 — Advanced page

### Analytics group
Shown for bar, horizontal bar, line, area, scatter.

| Field | Control | Step | Help |
|---|---|---|---|
| Trendline | Dropdown | 3 of 3 | None, Linear, or Moving Average trend overlay. |
| Moving Average Window | Slider | 3 of 3 | Window size for the moving-average trendline (active when type = Moving Average). |
| Forecast Periods | Slider | 3 of 3 | Number of periods to extend a linear trend as a forecast (active when type = Linear). |

### Reference Line group
Shown for bar, horizontal bar, line, area.

| Field | Control | Step | Help |
|---|---|---|---|
| Reference Line | Dropdown | 3 of 3 | None, Fixed Value, Mean, or Median horizontal line. |
| Fixed Value | Text | 3 of 3 | Y value the line is drawn at — used only when type = Fixed Value. |
| Line Color | Text | 3 of 3 | Hex color of the reference line, e.g. `#666666`. |

### Dual Y Axis group
Shown for bar, horizontal bar, line, area.

| Field | Control | Step | Help |
|---|---|---|---|
| Right-axis series | Text | 3 of 3 | Comma-separated column names plotted against the right-hand axis. |
| Right axis label | Text | 3 of 3 | Label for the right-hand (secondary) axis. |
| Log Scale (Y2) | Toggle | 3 of 3 | Logarithmic scale for the right-hand axis. |
| Right value prefix | Text | 3 of 3 | Text placed before each right-axis data label. |
| Right value suffix | Text | 3 of 3 | Text placed after each right-axis data label. |

### Error Bars group
Shown for bar, horizontal bar, line, area.

| Field | Control | Step | Help |
|---|---|---|---|
| Error Bar Type | Dropdown | 3 of 3 | None, Custom column, Std Dev, or Std Error of Mean. |
| Error value column | Text | 3 of 3 | Column whose value becomes each point's error amount — used only when type = Custom column. |

### Waterfall group
Shown for the waterfall chart type.

| Field | Control | Step | Help |
|---|---|---|---|
| Show Total | Toggle | 3 of 3 | Add a final total bar to the waterfall. |
| Positive Color | Text | 3 of 3 | Hex color for upward (gain) steps, e.g. `#107c10`. |
| Negative Color | Text | 3 of 3 | Hex color for downward (loss) steps, e.g. `#d13438`. |
| Total Color | Text | 3 of 3 | Hex color for the final total bar, e.g. `#69797e`. |

### Annotations group
Shown for bar, line, area.

| Field | Control | Step | Help |
|---|---|---|---|
| Annotations | Text | 3 of 3 | Free-form note rendered with the chart. |

### External Filter group
For connecting another web part's Dynamic Data value to filter this chart.

| Field | Control | Step | Help |
|---|---|---|---|
| External filter source | Dynamic data | 3 of 3 | Pick a web part property feeding a value into this chart. |
| Filter column | Text | 3 of 3 | Column that receives the published value to filter rows. Leave blank to show all rows. |

### Significance Brackets group
Shown for the bar chart type.

| Field | Control | Step | Help |
|---|---|---|---|
| Bracket pairs | Text | 3 of 3 | JSON array of bracket pairs, e.g. `[{"col1":"A","col2":"B","label":"*"}]`. |

### Statistical Process Control (SPC) group
The SPC viewer — a control-chart view comparing each metric's latest period
against its own historical centre line and upper/lower control limits.

| Field | Control | Step | Help |
|---|---|---|---|
| Enable SPC viewer | Toggle | 3 of 3 | Turn the SPC trend view on. When enabled the viewer takes over from the normal chart. |
| **Data source columns** | — | 3 of 3 | Columns that map the data into SPC observations. |
| Metric key column | Text | 3 of 3 | Column holding the metric code that identifies each series, e.g. `metric_code`. |
| Metric label column | Text | 3 of 3 | Column with the display name shown for each metric, e.g. `metric_name`. |
| Period column | Text | 3 of 3 | Column holding each observation's period (a date) that SPC sorts and ranges over, e.g. `period_start`. |
| Value column | Text | 3 of 3 | Numeric column with the measured value per period, e.g. `value`. |
| Incomplete-period flag column | Text | 3 of 3 | A period is excluded when this flag is falsy (`0`, `no`, `n`, `false`). Leave blank to treat all periods as complete. |
| **Limits & defaults** | — | 3 of 3 | How limits are computed and the default visible range. |
| Default date-range preset | Dropdown | 3 of 3 | Initial range a viewer sees: last 6/12/24/36 months, financial year to date, or custom. |
| Financial year start month | Text | 3 of 3 | Month (1–12) that begins the financial year, used by the "Financial year to date" preset. Default 4. |
| Minimum observations | Slider | 3 of 3 | Fewest observations (3–36) before limits are drawn; fewer shows "insufficient data". Default 6. |
| Sigmas for UCL/LCL | Dropdown | 3 of 3 | Control-limit width: ±2 or ±3 sigma. |
| **Viewer dropdown filters** | — | 3 of 3 | Optional dropdowns that let a viewer slice by a dimension. |
| Filter configs (JSON) | Text | 3 of 3 | Array of `{field, displayLabelField?, allowAll?}`, e.g. `[{"field":"service_code","displayLabelField":"service_name","allowAll":true}]`. |
| Default selections (JSON) | Text | 3 of 3 | Array of `{field, value}`; value `""` means All, e.g. `[{"field":"service_code","value":"Community"}]`. |

### Interactivity group
All charts.

| Field | Control | Step | Help |
|---|---|---|---|
| Show Filters to Viewers | Toggle | 3 of 3 | Let page visitors filter the chart data themselves. |
| Details on Demand | Toggle | 3 of 3 | Click a data point to see the underlying rows. |
| Overlay Data Points on Bars | Toggle | 3 of 3 | Draw markers on top of bars (bar, horizontal bar only). |
| Show Bubble Size Legend | Toggle | 3 of 3 | Add a size legend to the bubble chart (bubble only). |

### Conditional Formatting group
Shown for bar, horizontal bar, line, area, scatter, bubble, histogram, KPI.

| Field | Control | Step | Help |
|---|---|---|---|
| Threshold Value | Text | 3 of 3 | Value each point is compared against to decide whether the highlight color is applied. |
| Highlight direction | Dropdown | 3 of 3 | Apply the highlight to values below or above the threshold. |
| Highlight Color | Text | 3 of 3 | Hex color applied to points that cross the threshold, e.g. `#d13438`. |

### Data & Refresh group
All charts.

| Field | Control | Step | Help |
|---|---|---|---|
| Auto-Refresh Interval | Slider | 3 of 3 | Re-fetch the data source every N minutes (0 = off). Not available for uploaded files. |
| Cache API Results | Slider | 3 of 3 | Keep REST/Graph results for N minutes in the session cache (0 = off). |