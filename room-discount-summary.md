# Room Discount Implementation Summary

## 15% Room Discount Applied

The dashboard has been updated to include a 15% discount on all room rates. This discount affects all financial calculations throughout the system.

### Changes Made:

1. **FINANCIAL_CONSTANTS Updated**
   - Added `ROOM_DISCOUNT_RATE: 0.15` to the constants

2. **Participant Cost Calculations**
   - Updated to show discounted room costs in the participants table
   - Total cost now reflects: (Room Cost × 0.85) + Meals + Honorarium

3. **Invoice Generation**
   - Shows room rates before discount
   - Displays 15% discount amount in green
   - Shows discounted accommodation subtotal
   - Example:
     ```
     Room Total (before discount): $400.00
     15% Room Discount: -$60.00
     Accommodation Subtotal: $340.00
     ```

4. **Financial Calculations**
   - All accommodation revenue calculations now use discounted rates
   - Gratuity (15%) is calculated on the discounted room rate + meals
   - Organization invoice totals reflect the discount

5. **Participant Profiles**
   - Shows breakdown with discount in accommodation section
   - Financial summary displays discounted accommodation cost

6. **Financial Summary Tab**
   - Accommodation revenue shows "(15% discount applied)"
   - All totals reflect the discounted rates

### Impact on Totals:
- Each participant's accommodation cost is reduced by 15%
- Gratuity is calculated on the discounted amount
- Taxes (GST/PST) are applied after gratuity on the discounted subtotal

### Example Calculation:
For a room at $100/night for 4 nights:
- Original: $400
- Discount: -$60 (15%)
- Discounted: $340
- Plus meals, honorarium, gratuity, and taxes as usual