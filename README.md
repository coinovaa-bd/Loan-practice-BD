# Loan Practice BD (Demo)

A simple Bangla-first demo app packaged with Capacitor. It is a practice/education app only. It does **not** provide loans, approve applications, or submit user data to lenders.

## Build an APK using GitHub (phone-friendly)

1. Download and extract this ZIP on your Android phone.
2. Open https://github.com/ and sign in.
3. Create a new **public or private repository** named `loan-practice-bd`.
4. Upload the **contents** of this folder (including `.github/workflows/build-apk.yml`) to the repository. Make sure GitHub's upload includes the hidden `.github` folder; if the mobile upload flow hides it, use GitHub's web interface in Chrome with **Desktop site** enabled, or upload from a computer.
5. Open the repository's **Actions** tab. If asked, enable Actions.
6. Select **Build Loan Practice BD APK** and tap **Run workflow**. A push to `main`/`master` also starts a build.
7. Wait for the workflow to finish with a green check.
8. Open that workflow run and find **Artifacts**. Download `Loan-Practice-BD-debug-apk`.
9. Extract the artifact ZIP and tap `app-debug.apk` to install. Android may ask you to allow Chrome/Files to install unknown apps. Only install APKs you built from your own repository.

## What's included
- Home screen, demo application practice form, calculator, local practice history, guide, profile, and clearly labelled owner demo panel.
- No PIN/OTP, no real loan processing, no NID/bank data collection.
- Local-only practice history using browser/app storage.
- GitHub Actions workflow that creates a debug APK.

## Important before publishing
- The owner panel is a visual demo, **not secure authentication**. Do not use it to manage real users or money. A real admin system needs a backend, server-side authentication, authorization, and security review.
- No real AdMob ads are integrated. Add ads only after creating and approving an AdMob account, and follow Google Play/AdMob policies. Do not force clicks or mislead users.
- A debug APK is for testing. A Play Store release needs a properly signed release build, privacy policy, store listing, and policy compliance.
- Do not collect real personal or financial data in this practice app.
