# Rittal - Automation Equipment Knowledge

**Contact:** Brian Jung (Business Development Manager, 281-740-5583, Jung.B@rittal.us)  
**Secondary:** Reicher Barhorst (Account Manager IA Central & West Texas, 737-408-3703, barhorst.r@rittal.us)  
**Location:** Rittal LLC, 11717 Windfern Rd, Houston TX 77064

## Equipment Offerings

### Wire Processing Machines

#### C8 Cutting Machine
- **Function:** Cut-to-length wire
- **Control:** CSV upload for wire processing specs
- **Link:** https://www.rittal.com/us-en_US/products/PG20231215RAS101/PG20240408RAS202/PG20240408RAS205/PRO88263?variantId=4050455

#### S22 Stripping Machine
- **Function:** Wire stripping only
- **Link:** https://www.rittal.com/us-en_US/products/PG20231215RAS101/PG20240408RAS202/PG20240408RAS205/PRO62340?variantId=4050451

#### R8E Automatic Crimping Machine
- **Function:** Single-reel ferrule machine
- **Capability:** Strips and crimps ferrules
- **Limitation:** Single reel (change over required between gauges/colors)
- **Link:** https://www.rittal.com/us-en_US/products/PG20231215RAS101/PG20240408RAS202/PG20240408RAS205/PRO66936?variantId=4050454

#### RC Crimping Machine (Multi-Reel)
- **Function:** Multi-reel ferrule machine
- **Capability:** Strips and crimps ferrules
- **Key Benefit:** All reels always loaded - minimizes change over time
- **Link:** https://www.rittal.com/us-en_US/products/PG20231215RAS101/PG20240408RAS202/PG20240408RAS205/PRO88163?variantId=4050456

### Din Rail & Duct Equipment

#### Cutting Terminal for Din and Duct
- **Price:** ~$75K installed
- **Network Access:** Yes
- **Software:** Optimization software on machine (nesting to reduce scrap)
- **Connectivity:** Network accessible

### Enclosure Modification Milling Machine
- **Weight:** Relatively lightweight
- **Foundation:** No footings required
- **Power:** 400V 1~ (uncommon in US)
  - Rittal sells transformers to step up/down from native voltage
- **Air Supply:** Required - clean, dry air at ~80 PSI

### Wiring Robot
- **Status:** Beta testing (prototype)
- **Demo:** https://www.youtube.com/shorts/slJ8LvATsZg
- **Note:** Currently slow (beta phase)

## Limitations & Gaps

### Labeling
- **Rittal does NOT offer labeling devices** (except fully integrated Wire Terminal)
- **Recommendation:** Brady Wraptor (has some automation)
- **Source:** Brian Jung

### Software Integration
- **Overall:** "Very basic in terms of software"
- **Direct API:** No direct integration to machines
- **C8 Cutting:** CSV file upload supported
- **Change Over:** Manual between gauges and colors (except RC multi-reel)

## System Architecture

### Modular Wire Station
- Customize for shop needs
- CSV-driven for C8 cutting machine
- Manual change over for gauge/color swaps (except RC)

## Key Takeaways

**✅ What Rittal Does Well:**
- Multi-reel crimping (RC) reduces change over
- Network access on Cutting Terminal
- Optimization software built-in
- No foundation requirements for milling machine

**❌ Gaps vs. Blitzpanel's Needs:**
- No labeling solution in-house
- No API/network integration for most machines
- Manual change over on most equipment
- Limited software automation

**💡 Opportunities:**
- Pair Rittal wire processing with Brady labeling
- Use RC multi-reel to minimize change over
- Explore if Cutting Terminal network access could be extended to other machines

---

**Thread Date Range:** Dec 22, 2025 - Jan 28, 2026  
**Last Update:** Feb 1, 2026
