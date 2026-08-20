# Privacy Policy for SayYay

**Last updated: August 18, 2026**

SayYay is a photo booth app for iPhone and iPad. It is built to work entirely on your device.

## The short version

**SayYay does not collect, transmit, or store any personal data.** There are no accounts, no servers, no analytics services, no advertising, and no third-party SDKs. Nothing you create in SayYay leaves your device unless you explicitly choose to share it.

## Camera

SayYay uses the camera to show a live preview and to take your photo strip. Camera frames are processed **on your device, in memory, in real time** — used to display the preview, to place virtual decorations on detected faces, and to capture the photos you take.

- Camera frames are **never** uploaded, transmitted, or sent anywhere.

## Face data (TrueDepth API)

SayYay uses Apple's ARKit face tracking, which relies on the TrueDepth camera, for one purpose only: to place virtual decorations — a hat, glasses, a sign, floating effects — in the right position on a face while you frame your shot.

**What is collected.** From ARKit the app receives, for each face currently in view, only: the face's position and orientation in space, a temporary identifier that distinguishes one face from another for as long as they remain in view, whether the face is still being tracked, and a generic face mesh. Nothing else is requested or used — in particular SayYay does not use facial expression data (blend shapes), eye or gaze tracking, or the depth map.

**How it is used.** The position and orientation decide where a decoration is drawn. The temporary identifier lets each person in a group receive their own decoration. The face mesh is used only as an invisible mask, so a hat correctly disappears behind the back of the head instead of floating through it. It is never drawn, saved, or examined.

**Storage and retention.** None of this leaves the frame it arrives in. It exists in the device's memory only while the camera preview is on screen, is replaced every frame, and is discarded the moment the face leaves the view or you leave the camera screen. **No face data is ever written to storage**, and the temporary identifiers do not persist between sessions. The photos you take are ordinary camera images with the decorations drawn on top; they contain no face data, no mesh, and no depth information.

**Sharing.** This data is never transmitted anywhere and is never shared with any third party. SayYay contains no networking code, no servers, and no third-party SDKs, so there is no mechanism by which it could leave your device.

**What SayYay does NOT do.** It does not perform face recognition. It does not identify, authenticate, or attempt to determine the identity, age, gender, or emotional state of anyone. It does not create, derive, or store a faceprint, face template, biometric identifier, or any other data that could be used to recognise a person. It does not build a profile of anyone and does not use face data for advertising, analytics, or any purpose other than drawing decorations in the live preview.

- The photos you take exist only in the app while your session is open, until you save or share them.

## Photos

When you tap Save, SayYay writes the finished photo strip to your device's Photos library using Apple's system permission. SayYay requests **add-only** access — it cannot read, browse, or access your existing photos.

When you tap Share, SayYay hands the finished image to Apple's standard system share sheet. Whatever happens next (AirDrop, Messages, another app you pick) is handled by iOS and by the destination you choose, under their own terms and privacy policies. SayYay itself sends nothing.

## Usage counters (on-device only)

SayYay keeps simple counters on your device — for example, how many times a photo session was completed — so you can view them in Settings. These are **anonymous counts stored only on your device**. They contain no photos, no personal information, and no identifiers, they are never transmitted anywhere, and you can erase them at any time with the reset button in Settings. They are deleted when you delete the app.

## Text you enter

Any caption text you type for your photo strip is stored on your device with the app's templates and is only used to draw the text on your photo strip. It is not transmitted anywhere and is not included in the usage counters.

## Data sharing and sale

SayYay does not share, sell, rent, or disclose any data to anyone, because it does not collect any.

## Children's privacy

SayYay does not collect personal information from anyone, including children under 13.

## Analytics that Apple provides

If you have opted in to sharing analytics with Apple in your device settings, Apple may provide the developer with aggregated, anonymous statistics such as download counts, crash reports, and session counts. This is collected and controlled by Apple, not by SayYay, and is subject to [Apple's privacy policy](https://www.apple.com/legal/privacy/). You can change this in **Settings → Privacy & Security → Analytics & Improvements**.

## Changes to this policy

If this policy changes, the updated version will be posted at this address with a new "Last updated" date.

## Contact

Questions about this policy: **sayyay.app@gmail.com**

---

*[中文版 / Chinese version](privacy-zh)*
