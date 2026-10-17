# Agewise — Age Calculator Website

A responsive Next.js App Router project using TypeScript, Tailwind CSS, date-fns, Lucide icons, and jsPDF.

## Features
- Calendar age in years, months, and days
- Total months, weeks, days, hours, and minutes lived
- Birthday weekday, next birthday countdown, and Western zodiac sign
- Calculate age as of a selected past/present date
- Compare two birth dates
- Copy/share results and download a PDF summary
- Light/dark theme toggle
- Responsive design, accessible form labels, FAQ, metadata, and WebApplication structured data
- Calculations run locally in the browser; no database or backend required

## Requirements
- Node.js 20.9 or newer recommended
- npm

## Run locally
```bash
npm install
npm run dev
```
Open http://localhost:3000.

## Production build
```bash
npm run build
npm start
```

## Notes
- Birth dates in the future are rejected.
- The “Calculate age as of” field supports dates from birth onward, including future dates.
- Total hours/minutes are calculated from the selected birth time to the selected calculation date and time. For past/future dates, the birth time is used as the comparison time; for today, the current local time is used.
- For a February 29 birthday, the birthday countdown uses February 28 in non-leap years.
- Replace the sample `hello@example.com` contact email before publishing.
