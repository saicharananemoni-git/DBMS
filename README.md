# ParkPulse - Smart Parking Management System

**ParkPulse** is a high-efficiency, full-featured web application designed for smart cities, commercial complexes, airports, and multi-deck garages. It automates vehicle ingress/egress, optimizes bay allocation, monitors real-time sensor occupancy, and streamlines revenue settlement.

---

## 🌟 Key Features & Capabilities

1. **Secure Gateway Login & OTP Verification**:
   - **One-Time Password (OTP) Auth**: Protects access to the terminal until authorized via mobile OTP.
   - **Real-Time SMS Simulator & Auto-Fill**: Live simulated SMS delivery banner displaying the generated 4-digit security code with a 1-click **Auto-Fill OTP** button for instant testing.
   - **Operator Management & Sign-Out**: Displays active operator profile and allows 1-click logout directly from the navigation bar.

2. **Interactive 2D Parking Deck Grid & Wayfinding**:
   - **Multi-Level Garages**: Toggle seamlessly between *Level G (Ground Express & EV Hub)*, *Level P1 (Multi-Deck Car Park)*, and *Level P2 (Rooftop & Two-Wheeler Deck)*.
   - **Real-Time Bay Status**: High-contrast, color-coded bays:
     - 🟢 **Available (FREE)**: One-click check-in or reserve.
     - 🔴 **Occupied (BUSY)**: Live parked duration timer and accumulated fare counter.
     - 🟡 **Reserved (RESV)**: Time-limited VIP/hold bays.
     - 🔵 **EV Fast Charging (CHARGING)**: Live battery state-of-charge (%) bar and power delivery counter.
     - ⚪ **Maintenance (MAINT)**: Out-of-service bays toggleable for facility managers.
   - **Lane Architecture**: Authentic driveway markings, one-way traffic arrows, entrance/exit barriers, and elevator pillars.

2. **Automated Gate Entry Kiosk (ANPR Simulator)**:
   - **License Plate Scanner Simulator**: One-click ANPR camera trigger or manual plate input.
   - **Smart Bay Recommender**: AI algorithm automatically selects the closest and optimal vacant bay according to vehicle classification (Standard Car, EV, Accessible Permit, Motorcycle).
   - **Digital Thermal Parking Ticket**: Generates a POS ticket with scannable QR code, barcode, bay allocation, and print capability.

3. **Automated Gate Exit & Cashier Kiosk**:
   - Rapid vehicle lookup by License Plate, Ticket Reference, or Bay Number.
   - **Dynamic Tariff Engine**:
     - Billable hours calculation with configurable grace periods.
     - EV energy surcharge & kWh consumption metering.
     - Peak hours surge pricing multiplier (+25%).
     - Promotional voucher support (`MALL20` for 20% off, `VIP50` for 50% off, `FREE`).
   - Multiple payment options: **UPI / QR Pay**, **Card POS**, **Fastag / RFID**, and **Cash Desk**.
   - Confetti celebration upon clearance, and generates a printable **Tax Invoice & Barrier Clearance Slip** with verification QR code.

4. **"Find My Car" Indoor Wayfinding**:
   - Drivers enter their license plate or ticket reference.
   - App delivers step-by-step pedestrian walking directions from the main elevator to their exact vehicle bay.
   - Automatically switches floors and illuminates the car's bay on the map with a glowing animated beacon pin.

5. **Live IoT Sensor Telemetry Simulator**:
   - Toggle switch in the header to simulate live ultrasonic/loop sensors reporting real-time vehicle arrivals and departures.

6. **Financial Ledger, Audit Logs & Reporting**:
   - Comprehensive audit trail of all parking movements.
   - Average dwell duration, revenue breakdown, and vehicle type metrics.
   - **Export to CSV**: Download reports for financial audits and management review.

7. **Configurable Tariffs & Dynamic Pricing**:
   - Adjust hourly rates per vehicle type, EV fast charging tariffs, tax rates, and currency symbols (`$`, `₹`, `€`, `£`).

8. **Ultra-Clean Responsive UI & Themes**:
   - Dark mode default with quick switch to light theme.
   - Print stylesheets formatted for POS thermal receipt printers.

---

## 🚀 Running the Application

The web application is running live in your workspace:

- **Local URL**: [http://localhost:3000](http://localhost:3000)
- **Network URL**: Accessible across your local Wi-Fi network

### Manual Start / Build Commands:
```bash
# Start development server
npm run dev

# Production build
npm run build

# Preview production build
npm run preview
```

---

## 📁 Recommended Workspace Directory
Set your active workspace folder in your editor to:
`C:\Users\anil kumar\.gemini\antigravity\scratch\smart-parking-system`
