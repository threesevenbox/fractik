# Privacy Audit Checklist — FRACTIK

To be reviewed upon adding any third-party SDK and at least once per year.

---

## Active SDKs

- [ ] Firebase Analytics — Current version: ___
- [ ] Firebase App Check — Current version: ___
- [ ] Google AdMob (`react-native-google-mobile-ads`) — Current version: ___
- [ ] `expo-tracking-transparency` — Current version: ___

---

## Compliance Verifications

- [ ] The Privacy Policy accurately reflects all active SDKs and the data they collect.
- [ ] The Google Play Data Safety Form is up to date in Google Play Console.
- [ ] The App Store Privacy Nutrition Labels are up to date in App Store Connect.
- [ ] The 90-day retention/cleanup strategy for Firestore crash logs is functioning properly.
- [ ] The support/privacy email address is active and deletion requests are processed within 30 days.
- [ ] Privacy Policy URLs configured in both store consoles are publicly accessible and working.

---

## Checklist for Adding a New SDK

- [ ] Identify all data categories collected by the new SDK.
- [ ] Update the Privacy Policy document (Section 2: Data We Collect) accordingly.
- [ ] Update the Google Play Data Safety section.
- [ ] Update the App Store Privacy Nutrition Labels if new data categories are introduced.
- [ ] Verify GDPR, CCPA, and Apple ATT (App Tracking Transparency) compliance for the SDK.
