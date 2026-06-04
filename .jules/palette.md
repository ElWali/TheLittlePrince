## 2025-05-14 - Tilda localization defaults in aria-labels
**Learning:** Tilda-exported sites often contain default localization strings (e.g., in Russian) for built-in components like dialog close buttons. Even when the main content is English, these accessibility attributes may remain in the original language of the Tilda interface used by the creator.
**Action:** Always audit `aria-label` and `aria-description` attributes in Tilda-exported projects for hardcoded non-English strings, especially on interactive elements like modals and navigation toggles.
