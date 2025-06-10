# Co-Learning Exchange Dashboard - Flying Dust First Nation

A comprehensive dashboard for managing the Co-Learning Exchange event hosted by Flying Dust First Nation (June 10-14, 2025).

## Features

- **Participant Management**: Track 35 participants from 7 organizations
- **Accommodation Tracking**: Manage 24 room assignments
- **Financial Summary**: Real-time revenue calculations with GST/PST
- **Event Agenda**: 5-day detailed schedule with meal descriptions
- **Menu Planning**: Complete meal details including costs
- **Health & Safety**: Track certifications and dietary requirements
- **Export Capabilities**: Generate PDFs for participants, menus, and agendas
- **Invoice Generation**: Create organization-specific invoices

## Project Structure

```
fdfncolearning-exchange-dashboard/
├── index.html              # Main dashboard application
├── invoice-sample.html     # Invoice template and generator
├── README.md              # This file
├── room-discount-summary.md # Room pricing documentation
├── css/
│   └── styles.css         # Custom styles and animations
└── js/
    └── data/              # Data files (for future modularization)
        ├── constants.js   # Financial constants (GST, PST, etc.)
        ├── menuData.js    # Menu items and costs
        ├── agendaData.js  # Event schedule
        └── attendanceData.js # Participants and accommodations
```

## How to Use

1. **Open the Dashboard**: Simply open `index.html` in a modern web browser
2. **Navigate Sections**: Use the sidebar to access different features
3. **Edit Data**: Click "Edit" buttons to modify information
4. **Export Data**: Use export buttons to generate PDFs or download JSON data

## Key Information

### Event Details
- **Dates**: June 10-14, 2025
- **Location**: Flying Dust First Nation, Meadow Lake
- **Participants**: 35 from 7 organizations
- **Accommodations**: 24 rooms (cabins and glamping)

### Financial Constants
- **GST**: 5%
- **PST**: 6%
- **Gratuity**: 15% (on accommodations and food service)
- **Room Discount**: 15%
- **Honorarium**: $250 per participant

### Meals Included
All meals are now displayed with full descriptions in the agenda:
- Welcome Supper (NY Steak Buffet)
- Daily Continental Breakfast
- Bagged Lunches
- Traditional Bison Feast
- Shore Lunch
- Closing Feast

## Browser Compatibility

Works best with modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari

## Data Updates

To update event data in the future:
1. The `js/data/` folder contains extracted data files
2. These can be edited separately and integrated later
3. Currently, all data is embedded in `index.html` for simplicity

## Local Storage

The dashboard uses browser local storage to save:
- Menu modifications
- Agenda changes
- Sidebar state

## Support

For questions or issues, contact the Flying Dust First Nation event coordinator.

---

Built with Tailwind CSS, Chart.js, and jsPDF