---
title: "Using RNAV Approaches on Checkrides"
description: "LPV and LNAV/VNAV approaches aren't precision, except when they are."
tags: ['training', 'iap']
lastmod: 2023-04-25
draft: false
---

### LPV and LNAV/VNAV Approaches on the Instrument and CFII Checkrides

Yes, you can use a suitable Approach with Vertical Guidance (APV) approach in place of another precision approach, like an ILS, on your checkride, if the Decision Altitude is less than 300' AGL.  That means the RNAV/GPS approach to your local airfield can count as precision for the purposes of the checkride.

From the Instrument Rating ACS:
> A localizer performance with vertical guidance (LPV) approach with a decision altitude (DA) greater than 300 feet height above terrain (HAT) may be used as a nonprecision approach; however, due to the precision of its glidepath and localizer-like lateral navigation characteristics, an LPV can be used to demonstrate precision approach proficiency (AOA VI Task B) if the DA is equal to or less than 300 feet HAT. 

And from the CFII PTS: 
> An LPV approach is technically a nonprecision approach, however, due to the precision of its glidepath and localizer-like lateral navigation characteristics, an LPV can be used to demonstrate precision approach proficiency (AOA VIII TASK B). Also, although LPV and LNAV/VNAV approaches are nonprecision approaches, they cannot be used to demonstrate nonprecision approach proficiency (AOA VIII TASK A) due to the presence of a glidepath.

So if it walks like a duck and talks like a duck, why can't an APV approach to less than 300' be considered a Precision Approach?

#### APV Approaches, as a Category

The FAA codified APV approaches as something between Precision and Non-Precision.  These approaches provide both horizontal course guidance and vertical glidepath guidance.  They tend to rival the accuracy of an ILS, but don't meet every standard of performance to be classified as a precision approach.  Remember than an ILS is special because it has a localizer, glidepath, and outer marker.  RNAV approaches lack this third (external) element which provides an additional reference for verifying your position.

The underlying standards for APV, and all approaches, are governed by the International Civil Aviation Organization.  If you dig deep into ICAO Annex 10, Volume 1, Chapter 3, Section 7, and go all the way to the end of the section, you'll see the various definitions of approaches and the accuracy requirements for RNAV/GPS-based approaches.

![SBAS Accuracy Criteria](/img/sbas_criteria.png)

There is a small increase in accuracy required for a WAAS RNAV/GPS (a Space-Based Augmentation System) to go from APV to Category I Precision Approach.  The FAA has defined their own accuracy standards, which are similar to ICAO, but aren't the same.  The discrepancy, in Time To Alert, from 6.2 seconds, to 6.0 seconds, seems to be enough to make our APV approaches ineligible for consideration as a Precision Approach.  (LPV-200 indicates an LPV approach with a decision altitude that is 200' AGL.)

![WAAS Accuracy Criteria](/img/waas_performance.png)

So APV approaches are approaches that provide accurate horizontal and vertical guidance.  They can absolutely be as accurate as a Precision approach, and they require no external ground equipment to be maintained, making them easier and faster to create, with fewer ongoing costs and virtually no maintenance.

But is that the end of the story?  What about an LNAV or LP approach that provides a "+V" indication on your avionics?  That gives you a glidepath, and is seemingly as accurate as an LNAV/VNAV or LPV approach.  Of course, it doesn't work that way.  If it did, I wouldn't have asked the question.

### A Note About "+V"

Some panel mounted GPS navigators provide an "Advisory Glidepath" and annunciate the availability of the glidepath with a "+V" indication on the display, when inbound to the Final Approach Fix.  This indicates that an advisory glidepath is available, but this glidepath hasn't been reviewed for TERPS criteria and only provides a straight-line vertical guidance from the FAF to the MAP.  It's possible that you can descent below a step-down fix on "+V" guidance, though I haven't seen a case yet where that would occur.

Confusingly, I've also heard that the FAA is reviewing and modifying approaches to add +V guidance that meets TERPS criteria, which would then mean that the +V advisory glidepath really starts to behave like their bigger brother LPV or LNAV/VNAV approach.  Where TERPS criteria can't be met on these, the GPS navigator will suppress the "+V" indication, returning you to horizontal guidance only LP or LNAV approaches.  It may be that we're in a transition phase where all approaches will either end up an LPV or LNAV/VNAV, or drop vertical guidance altogether and the "+V" indication on approaches will be a snapshot into the time when GPS approaches were rapidly evolving.