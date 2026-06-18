Build a mobile-responsive full-stack web application called "Driveway Closer" for residential HVAC contractors to pitch tiered pricing to homeowners.

The application needs 3 distinct components built out sequentially:

1. THE DATABASE SCHEMA:
- Set up a 'companies' table storing name, email, logo, hourly_labor_rate, target_margin, and financing_factor.
- Set up an 'equipment_catalog' table storing tier (Good, Better, Best), tonnage, wholesale_cost, and est_install_hours.
- Set up a 'quotes' table storing customer data, calculated tier pricing totals, selected_tier, and status.

2. A 4-STEP ONBOARDING WIZARD:
- Step 1: Collect Company Name, Email, and Logo upload.
- Step 2: Input Sliders for Hourly Labor Rate (default $150), Target Margin (default 45%), and Financing Factor (default 0.015).
- Step 3: Brand selection checkboxes. Ticking a brand should automatically seed the equipment_catalog with realistic national average wholesale costs for 2.0 to 5.0 ton units across Good, Better, and Best tiers.
- Step 4: Run a fake 3-ton calculation to let the owner see a live test run on screen.

3. THE DRIVEWAY PROPOSAL INTERFACE & LOGIC:
- Create an input screen for technicians to enter customer name, email, required tonnage, and immediate repair costs.
- Implement the backend pricing engine using the Gross Margin Formula:
Retail Price = (Wholesale Cost + (Install Hours * Labor Rate)) / (1 - Target Margin)
- Apply the Financing Factor to show the monthly rate: Monthly = Retail Price * Financing Factor
- Render an interactive, high-visibility 3-column pricing grid (Good/Better/Best) with the specific dynamic bullet points provided in our blueprint.
- Add a digital touchscreen signature pad at the bottom with an "Approve Installation" button that changes the status to 'Approved'.

Make the design highly optimized for field technicians using smartphones outdoors in bright sunlight (high contrast, large tap targets, no heavy typing required).
