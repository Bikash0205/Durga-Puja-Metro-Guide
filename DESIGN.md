# DESIGN.md — Kolkata Durga Puja Metro & Pedestrian Guide 2026

## 1. Persona & Aesthetic Direction
- **Product Kind:** Mobile-First Web App / Festive Transit & Pedestrian Circuit Guide.
- **Audience:** Puja revellers, night hoppers, tourists, and Kolkata locals on foot.
- **Vibe:** "Kolkata Festive Chic" — Modern iOS/Android aesthetic infused with rich festive tones: deep crimson/kumkum (`#991B1B` / `#7F1D1D`), warm marigold/shindur accent (`#EA580C`, `#D97706`), crisp parchment base (`#FFFBF5`), and distinct Metro line brand accents (Blue, Green, Orange, Purple).
- **Core Principle:** Mobile-first ergonomic touch targets (min 44px), sticky bottom navigation bar, card swipe feel, real-time walking distance calculator, and one-tap Google Maps turn-by-turn navigation (walking/driving).

## 2. Color Token Architecture
- **Canvas / Background:** `#FFF9F2` (Warm Festive Cream), `#F5EBE1` (Subtle Card Surface)
- **Primary Accent:** `#991B1B` (Alpona Crimson / Durga Red)
- **Secondary Accent:** `#D97706` (Marigold Gold)
- **Text Hierarchy:**
  - Headings: `#450A0A` (Deepest Red-Brown)
  - Body: `#1F2937` (Rich Charcoal)
  - Muted / Meta: `#6B7280`
- **Metro Line Brand Badges:**
  - Blue Line (North-South): `#2563EB`
  - Green Line (East-West / Underwater): `#059669`
  - Orange Line (New Garia - Beleghata): `#EA580C`
  - Purple Line (Joka - Majerhat): `#7C3AED`

## 3. Key Components
1. **App Header & Live Status:** Durga Puja 2026 dates banner, live search, and night-metro alert chip.
2. **Pedestrian Circuit Hub (Walking Mode):**
   - Station-to-station walk selector (e.g. Kalighat Circuit, Shyambazar Heritage Circuit, College St & Sealdah Circuit, Salt Lake / VIP Road Circuit).
   - Point-to-Point sequence with walking distance (km) and walking time (mins).
   - "Open Walking Route in Google Maps" button (auto-constructs multi-stop walking waypoint URL).
3. **Pandal Detail & Point-to-Point Hop Navigator:**
   - Tap any pandal card to inspect its details, 2026 special theme/attraction, crowd level, and closest metro exit.
   - Dynamic **"Hop to Next Nearby Pandal"** selector with direct turn-by-turn Google Maps link (Walking or Driving).
4. **Custom Itinerary / Hopper Pocket:**
   - Bookmark/Add pandals to custom walking list.
   - Export custom walking route to Google Maps.
5. **Night Metro 2026 Guide Modal:**
   - Operational schedules, smart-card tips, major interchanges (Esplanade, Kavi Subhash, Sealdah).
