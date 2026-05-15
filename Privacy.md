# Pedal Quest — Privacy Policy

**Last updated:** 14/05/2026 (for Americans: 05/14/2026)

Pedal Quest is a private cycling adventure log made for children aged 7 to 13. We've built privacy into the app from day one. This page explains, in plain language, how Pedal Quest handles your child's information.

## The short version

- We do not have any servers. We do not collect or receive any of your data.
- Everything your child records — rides, photos, badges, nicknames — is stored on your device and, optionally, in your own private iCloud.
- There are no accounts, no advertisements, no analytics SDKs and no third-party trackers.
- The only network traffic the app initiates is to Apple's iCloud (for your own sync) and Apple Maps (for map tiles).

## What the app stores

On your device (and, if iCloud Drive is on, in your private iCloud database):

- A nickname you choose for your child
- Their date of birth and interests if entered (used only to make the app feel personal)
- An optional bike photo and avatar
- Each ride's GPS trail, distance, time and any photos or diary notes attached
- Badges earned and custom badges invented
- Your settings (units, theme, sound and haptic preferences)

We — the developer — have no access to any of this. It lives in your Apple iCloud account.

## Location

The app uses your device's location only while a ride is being recorded, and only with **"When In Use"** permission. Location is used to draw your trail on Apple Maps and to calculate distance and speed. Location data is never sent to us or to any third party.

## Camera and photos

Optional. Used only if you choose to set an avatar photo, set a bike photo, or attach photos to a ride. Photos are stored alongside the ride in your own iCloud. EXIF metadata (including any location embedded in the photo) is stripped before storage.

## Bluetooth and local network (ride-buddy pairing)

Optional and **OFF by default**. When a grown-up enables it, two nearby phones running Pedal Quest can pair using Apple's MultipeerConnectivity framework. The session is encrypted. No data is sent over the internet.

While paired, each phone sends the other a small introduction: the rider's chosen nickname, their avatar style, and — if they've set one — a small thumbnail of their avatar photo (about 96 pixels square). The buddy's phone uses this to draw them on the map and on the "paired with" card. The thumbnail is held in memory for the ride only and is never saved to disk on the buddy's device.

When you finish a ride while paired with a buddy, a small memory is saved with that ride: the buddy's chosen nickname, their avatar style, and any badges they earned during the ride. **The avatar photo is not part of this memory** — only the symbol-style avatar is kept. This memory lives in your own iCloud private database and never leaves your devices — we cannot see it. You can forget the memory from any individual ride at any time, and the buddy's data is wiped immediately when you do.

The "Favourite ride buddies" list (used for one-tap reconnection) continues to store only the buddy's chosen nickname, the symbol-style avatar they use, and an opaque pairing identifier; it does not include badges, ride history or any photo.

## iCloud

Pedal Quest uses your own iCloud Drive private database via SwiftData to sync rides between your devices. We — the developer — cannot see this data. It is end-to-end private between your devices and your Apple ID. The app works fully without iCloud too.

## Children

Pedal Quest is designed for children but does not require children to provide any personal information. The nickname, date of birth, interests and bike-colour fields are optional and used only on-device to personalise the experience. No accounts are created. No data is shared with us or any third party.

## Third parties

We do not use any third-party SDKs, analytics tools, advertising networks, or social-login providers.

## Changes

If we ever change this policy, we will update the date at the top of this page. Material changes will be announced in the app.

## Contact

If you have any questions about how Pedal Quest handles privacy, please email: [marc@iamcoding.uk](mailto:marc@iamcoding.uk)
