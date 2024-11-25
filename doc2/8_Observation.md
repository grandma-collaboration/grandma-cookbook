# 8. Skyportal: Observation Plans and Photometry for Follow-up Advocate

## 8.1 Observation Plans
- Talk about observability
- talk about day night map on the cover
- talk abotu filling out observation plans and when you do so.
- why we use 300s so much (on forge on one of the proposals it explains how we reach magnitudes at certain exposures)


## 8.2 Uploading Photometry
Some filter systems are commonly associated with specific magnitude systems. For example:

SDSS filters (u’, g’, r’, i’, z’) are typically calibrated in the AB system.
Johnson-Cousins filters (e.g., U, B, V, R, I), also referred to as Bessel filters, are often calibrated in Vega magnitudes.
Many near-infrared filters (J, H, K from the 2MASS system) also use the Vega system.
Standard filters include UGRIZ. 

When a counterpart is detected, use the UVOT counterpart coordinates immediately, if available. If SWIFT UVOT does not detect a counterpart, use the coordinates from other telescopes detecting the counterpart. Update to the most accurate counterpart coordinates available, even if not provided by SWIFT/UVOT.

General guidelines:

Use an air mass of 1.8 across all telescopes.
If a gain is not specified, default to a value of 1, as gains may vary slightly across telescopes. If a gain is missing in the header and causes an inspection error, consult the telescope team for the correct gain.
If the limiting magnitude (upper limit) is unknown, make an estimated guess and leave a note. The upper limit is not typically used if a magnitude and error are provided.
Finally, include the coordinates used in the analysis file, especially if obtained from stdweb, the telescope team, or a GCN notice. Do not wait to add data to the table if coordinates are missing; just ensure they’re added once available.
