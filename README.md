Refined Hybrid Training — Gym Menu & Session Builder
Version: V1.1.0
Status: Live page (single shareable link)
The public-facing web app for Refined Hybrid Training — a trainer-focused gym. One page, two tabs: it always opens on the Gym Menu (the full equipment catalog, the "home page") so visitors see everything on the floor before they tap Build a Session to generate a workout plan.
Faith • Strength • Community

What it is
A static, no-login web page anyone can open from a link. No accounts, no saved data — every visitor runs it privately in their own browser.
Tab 1 — Gym Menu (home): every piece of equipment on the gym floor, with photos, descriptions, muscle groups, search, and category filters.
Tab 2 — Build a Session: a workout plan builder that generates training plans using only the equipment actually in the gym.

Gym Menu — equipment list (31 listings)
Bolt strength machines (10)
Bolt Classic Series Rhino — Compact Leg Press
Bolt Shock Series — Pec / Rear Delt Combo
Bolt Storm Series Hydra — Adjustable Leg Extension / Seated Curl Combo (user photo)
Bolt Classic Series Midas — Plate Loaded Hack Squat
Bolt Classic Series Attila — Plate Loaded Chest Press
Triton Commercial Adjustable Bench
Ironclad Functional Trainer — Dual 250 lb Weight Stacks (cable station)
Bolt Storm Series Widow — Freestanding Lat Pulldown / Low Row (cable station; stack weight listed neutrally — Bolt's listing says 300 lb in the title/specs, 250 lb in one line of body copy, pending physical confirmation)
Bolt Classic Series Slicer — Plate Loaded Mid Row
Bolt Fortuna — Plate Loaded Standing Hip Thrust
HYROX / conditioning (7)
Centr Perform Series Ski Machine
Centr HYROX Official Competition Power Sled
Centr HYROX Official Competition Power Rope (15 m sled-pull rope) (user photo)
Centr Perform Series Rower
Centr HYROX Perform Turf (2 lanes + end zones)
Centr HYROX Official Competition Rig Target
Centr HYROX Official Competition Sandbags — 10 / 20 / 30 kg (user photo of the 20 kg bag)
Free weights (7)
Rubber Hex Dumbbells — 5–100 lb
Barbells (bench, squat, deadlift bars)
Weight Plates — 24 bumper plates (45×16, 25×4, 10×4) + 120 cast iron plates (45×70, 25×14, 10×16, 5×12, 2.5×8)
10 lb Weighted Wall Ball
70 lb Cast Iron Kettlebell
Rogue R-6 Power Rack
Rogue Crown Pull-up Bar
Cable attachments & accessories (7, added V1.1.0)
Rogue Deadlift Bar Jack — loading accessory for barbells/plates. Equipment only — not a workout, excluded from the session builder.
Tricep Rope Attachment (Ironclad / Widow)
Rogue Curl Bar Cable Attachment (Ironclad / Widow)
Single Handle Cable Attachment ×2 (Ironclad / Widow — unilateral work)
Rogue CG-1BMG Crossbow Multi-Grip Cable Attachment, 20° (Ironclad / Widow)
Rogue Lat Bar (Widow / Ironclad)
Rogue Rotating V-Grip Cable Attachment (Ironclad / Widow)
Each card shows: photo, 1–2 sentence description, primary + secondary muscle groups, and which main equipment an accessory attaches to. Demo/how-to video is the card's primary button; cards without a real demo have no button (never a dead link). No prices and no retailer/store links anywhere on the page — by design.
Filters: Lower Body · Upper Body · Full Body · HYROX · Free Weights, plus text search.

Build a Session — feature list
7 muscle-group pairings (e.g. Chest + Triceps, Back + Biceps, Legs, Shoulders + Arms, Glutes + Hamstrings, Full Body, HYROX Conditioning)
3 durations: 30 / 45 / 60 minutes
5 training goals, each with a plain-English explanation and science-based programming:
Goal
Programming
Strength
4–5 sets × 3–5 reps, 3–4 min rest. Compounds first, heaviest effort.
Build Muscle
3–4 sets × 8–12 reps, 60–120 s rest. Controlled tempo, full ROM.
Tone & Define
2–3 sets × 10–15 reps, 45–75 s rest. Moderate loads, sensible antagonist supersets.
Fat Loss
2–3 circuit rounds, 12–20 reps or 30–45 s work, 30–45 s rest + sled/rower/ski finisher.
Work Capacity
30–60 s work / ~30 s rest intervals, 15–25 min conditioning blocks.
Compound-first ordering — multi-joint lifts always precede isolation work.
Inline editing of sets, reps, and rest on every exercise.
Drag-to-reorder with visible grip handles — mouse and touch; plan renumbers instantly and flows into exports.
Randomize — a fresh exercise mix for the same pairing, duration, and goal.
Exercise Library — every exercise grouped by machine with photos; checkboxes build a fully custom plan with all the same features.
YouTube how-to video on every exercise, including the 12 cable-attachment movements (rope pushdowns, overhead rope extensions, cable curls, single-arm rows/pressdowns/flyes, multi-grip rows, close-grip pulldowns, lat pulldowns, straight-arm pulldowns, close-grip seated rows, V-bar pushdowns).
Save as Image (branded PNG download), copy to clipboard, print-friendly layout, and a compact screenshot mode.

Design & content rules
Brand palette: black, white, bone, brass. Tagline: Faith • Strength • Community.
All imagery hosted locally in the page — no hotlinking. User-supplied photos used where provided (Hydra, sandbag, power rope, all 7 accessories).
YouTube timestamp links use the &t=seconds format and are never altered.
A render-time safeguard allows only YouTube or direct video-file URLs as card links.
Tech notes
Single static page (HTML/CSS/JS). No backend, no database, no build step required to view.
PNG export renders client-side.
Fully responsive; verified at desktop and 390 px mobile widths with no overflow or console errors.
Suggested repo layout
/
├── README.md
├── index.html          # the page (exported)
├── assets/
│   ├── img/            # equipment photos (local)
│   └── ...
└── docs/
    ├── equipment.md    # per-item specs, photos, video URLs
    └── exercises.md    # builder exercise → video mapping
Changelog
V1.1.0 (2026-10-12) — Combined single page: Gym Menu as the home screen, session builder as a tab. Added 7 Rogue accessories (bar jack + 6 cable attachments) with 12 new builder exercises.
V1.0.x (2026-10-06 → 10-09) — Separate Equipment List and Workout Plan Builder pages; wall ball + kettlebell additions; Gym Menu-first navigation hierarchy.
License
Private project — add your chosen license before making this repo public.
