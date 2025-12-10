# Booker T. Washington WebTower · “We Lead, Others Follow”

This WebTower is a **trophy cabinet** for Booker T. Washington High School
alumni businesses, mapped into the FlightLine / Memphis DC grid.

## Purpose

- Show BTW as a **Business Univercity** (city of businesses, not just classes).
- Display alumni businesses as digital trophies.
- Give alumni a simple way to submit their business and be added to the wall.
- Anchor the page to the **real school coordinates** for maps + FlightLine.

## How It Works

1. **Hero + Motto**
   - Shows school name, motto, and location.

2. **Alumni Trophy Cabinet**
   - A grid of cards:
     - Business name
     - Owner (alum name & class year)
     - Short description
     - Link to website / social / booking
   - You can manually add alumni as `<article>` cards in `index.html`.

3. **Alumni Sign-Up**
   - A “Claim Your Trophy Slot” button that links to a **Google Form**.
   - Each response can feed a Google Sheet that you mirror into the page.

4. **FlightLine / Memphis DC**
   - Data attributes on the `<body>` tag hold:
     - `data-lat=""` and `data-lng=""` for the school coordinates.
   - Later you can connect this to maps and grids.

## Duplicating for Other Memphis High Schools

1. Duplicate this repo.
2. Replace in `index.html`:
   - School name
   - Motto
   - Colors (CSS variables at the top)
   - Coordinates on `<body data-lat="" data-lng="">`
3. Update README with the new school’s details.
4. Enable GitHub Pages and add the new URL to the Memphis DC grid.

Booker T. Washington is the **first** node in the Memphis High Schools
Business Univercity network. Each new school is another WebTower in the city.
