# Energy Network Privacy Policy

This policy describes how Energy Network handles information in the Energy
Network Android application (the “App”). Energy Network does not show
third-party advertising and does not sell personal information.

## Information that may be processed

The App supports local play without an account. If you use account or online
features, the App may process:

* **Account information:** Firebase Authentication may receive an email address
  and password for email sign-in, or the account identifier, name, email
  address, and profile photo supplied by Google Sign-In. Anonymous guest
  accounts use a Firebase-generated identifier.
* **Profile and game information:** the display name, avatar, progression,
  achievements, scores, match results, replay data, room codes, invitations,
  friend relationships, and online presence needed to provide multiplayer and
  profile features.
* **Notifications:** Firebase Cloud Messaging provides a device notification
  token so the App can deliver match and invitation notifications. The token
  is associated with the signed-in profile while notifications are enabled.
* **Diagnostics and analytics:** Firebase Analytics receives events such as
  sign-in method, game mode, match outcome, duration, scores, achievement
  events, and broad feature usage. The App does not intentionally send email
  addresses, Firebase user IDs, friend IDs, invite targets, room codes, or
  game IDs as Analytics event parameters.

Firebase Authentication, Cloud Firestore, Realtime Database, Cloud Messaging,
and Analytics are provided by Google Firebase. Their processing is subject to
Google’s terms and privacy documentation. The App does not currently use
Firebase Storage for user content.

## Information stored on the device

Room stores local profile, progression, achievement, and game data. Android
DataStore stores preferences such as settings and accessibility choices.
Firestore and Realtime Database persistence may cache signed-in profile and
multiplayer data on the device for offline resilience. Local-only play remains
on the device unless you choose a feature that synchronizes it.

## Nearby multiplayer and permissions

Nearby multiplayer uses Android device-discovery and peer-to-peer services to
find and communicate with another nearby device. Depending on Android version
and device, Android may request Bluetooth, nearby Wi-Fi, or location
permissions. These permissions are used for discovery and communication, not
for advertising or background location tracking. Haptic feedback uses the
vibration permission. Notifications use the notification permission where
required by Android.

## Choices, retention, and deletion

You can play locally without signing in, decline optional permissions, disable
notifications, and sign out of an account. Declining network or Nearby
permissions limits only the related feature. Local data can be removed by
clearing the App’s storage or uninstalling the App. To request deletion of
cloud profile, multiplayer, notification-token, or associated account data,
contact us using the address below and include enough information for us to
identify the request without sending a password. We retain information only
for as long as needed to provide the service, comply with law, resolve
disputes, and maintain security; exact retention can depend on Firebase
configuration and operational backups.

## Security and changes

We use the security controls provided by Android and Firebase, but no
electronic storage or transmission is guaranteed to be completely secure.
We may update this policy when the App or its data practices change. The
updated policy will be shipped with the App.

## Contact

For privacy questions or deletion requests, contact:
**support@energynetwork.game**
