# Co-learning Exchange Dashboard

A comprehensive event management dashboard for the Co-learning Exchange at Flying Dust First Nation, Waters Edge Eco Lodge, Meadow Lake Provincial Park, Saskatchewan.

## Features

### 📊 Dashboard Overview
- Real-time participant statistics
- Organization breakdown with visual charts
- Financial summary with dynamic calculations
- Accommodation occupancy tracking

### 👥 Participant Management
- Complete participant listing with search and filter
- Individual participant profiles
- Editable participant information
- Health & safety tracking (dietary requirements, allergies, certifications)

### 🏨 Accommodation Management
- Room assignment tracking
- Occupancy visualization
- Room type categorization (Cabins, Hotel Rooms, Glamping Tents)
- 15% discount on all room rates

### 💰 Financial Tracking
- Automated invoice generation with PDF export
- Organization-based billing
- Financial calculations include:
  - 15% room discount
  - 15% gratuity (on accommodation and meals only)
  - GST (5%) and PST (6%)
  - Presenter & Community Honorarium ($250/participant)

### 📅 Event Management
- 5-day event agenda (June 10-14, 2025)
- Editable daily schedules
- Menu planning with cost tracking
- Weather forecast integration
- Fire ban status monitoring

### 🍽️ Menu & Catering
- Daily meal planning
- Cost calculations per meal
- Updated pricing: Lunches $15/day, Suppers $30/day
- Special dietary accommodation tracking

## Technical Details

- **Built with**: HTML5, Tailwind CSS, Vanilla JavaScript
- **Libraries**: Chart.js for visualizations, jsPDF for invoice generation
- **Storage**: LocalStorage for data persistence
- **Responsive**: Mobile and desktop optimized

## Key Financial Formulas

```
Room Cost = Base Rate × Nights × 0.85 (15% discount)
Gratuity = (Discounted Room Cost + Meals) × 0.15
Subtotal = Room + Meals + Honorarium + Gratuity
Total = Subtotal × 1.11 (GST + PST)
```

## Usage

1. Open `index.html` in a modern web browser
2. Navigate using the sidebar menu
3. Click participant names or organizations for detailed profiles
4. Use the edit buttons to modify data
5. Generate invoices from the Organizations tab

## Data Structure

The dashboard uses embedded JSON data for:
- 35 participants across 7 organizations
- 24 accommodation units
- 5-day agenda with activities
- Menu items with individual costs

## Recent Updates

- Added 15% discount on all room rates
- Fixed financial calculation consistency across all tabs
- Implemented comprehensive search functionality
- Added participant and organization profile modals
- Updated meal pricing (Lunches: $15, Suppers: $30)
- Fixed JavaScript errors and data loading issues

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

This project is proprietary to Flying Dust First Nation.