# Emergency Plumbing Squad - CTA Elements Documentation

## 📋 Project Overview
This repository contains documentation for Call-to-Action (CTA) elements found in the Emergency Plumbing Squad WordPress website.

## 📄 Documents

### [The List of CTA Elements](./The%20list%20of%20CTA%20Elements.md)
Comprehensive list of all active CTA elements with proposed tracking classes for analytics implementation.

**Features:**
- ✅ 40 active CTA elements identified
- ✅ 33 phone number links (tel:)
- ✅ 7 contact us links
- ✅ Comprehensive tracking class naming system
- ✅ Device-specific targeting (desktop/mobile/all)
- ✅ Template location identification

## 🎯 Tracking Class System

**Structure:** `wi_cta-{type}-{location}-{element}-{display}`

**Examples:**
- `wi_cta-tel-page24hpnm-btn-all` - Phone button on 24h page, all devices
- `wi_cta-contact-footer-default-all` - Contact link in default footer, all devices

## 📱 Active Templates
- page-24hpnm.php (24 Hour Plumber Near Me)
- new-location-page.php (New Location)
- new-state-template.php (State Template)
- template-cta.php (CTA Template)
- And 10+ other active templates

## 🔗 Quick Links
- **Direct Document View:** [View CTA Elements List](./The%20list%20of%20CTA%20Elements.md)
- **Repository:** https://github.com/olhakharlamova/emergencyplumbingsquad

## 📞 Primary Phone Numbers
- `(855) 812-2311` - Primary number (most frequently used)
- `(855) 916-4406` - Alternative number

## 🔄 Latest Updates (January 2025)
- Preserved tracking classes on mobile (JS adjusted).
- Added missing classes:
  - header-24henm.php → wi_cta-tel-header24henm-btn-all
  - page-24hpnm.php → wi_cta-tel-page24hpnm-btn-all
  - functions.php → wi_cta-tel-functions-exo-all, wi_cta-tel-functions-stitem-desktop, wi_cta-tel-functions-stitem-mobile
- Shortcode templates/postcode_location.php confirmed with wi_cta-tel-templatespostcode-all.
- Parent includes/call-now.php uses wi_cta-tel-includes-callnow-{float,preview,widget}.

---
*Last updated: January 2025*