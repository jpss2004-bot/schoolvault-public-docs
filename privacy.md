# SchoolVault privacy notice

Last updated: October 1, 2026

SchoolVault is an independent, invitation-only student beta operated by Jose Pablo Samano (Microsoft Store publisher: jpss2004-bot). This notice covers SchoolVault Companion and its connected SchoolVault web app. Support and privacy contact: **jpss2004@gmail.com**. SchoolVault is not affiliated with or endorsed by Acadia University, Google or Microsoft.

## Information we process

- **Account:** Google account identifier, verified email address and name, plus your chosen time zone. Google sign-in requests identity scopes only (`openid`, `email`, `profile`). This beta does not request Gmail mailbox access or retain Google's provider access token for mail.
- **Moodle connection:** the Moodle account label and account identifier you confirm, course titles and links, visible text from supported course and activity pages, capture times and coverage warnings. Collected text can include instructor and peer content visible to your Moodle account.
- **Your work:** notes and their versions, chat questions, drafts and assistant replies, selected course context, source references, and PDF or plain-text files you choose to upload.
- **Operation:** session and device records, connection status, collection timestamps, jobs and audit records. Hosting providers may also process ordinary request metadata, such as IP addresses, for operating their services.

SchoolVault Companion opens a separate Microsoft Edge profile for you to sign in directly to Acadia Moodle. It reads rendered course content after you confirm the Moodle identity. The companion does not capture your Moodle password or upload the Edge profile or its session cookies to SchoolVault. Cookies and browser session data remain on your laptop. The current capture reads supported visible pages; PDFs, external videos, grades and deeper forum/book pages are not automatically collected by this capture.

## Why and where information is processed

We use this information to authenticate you, connect your own Moodle account, maintain your course vault, retrieve relevant material, save your work, generate requested assistant answers and operate and troubleshoot the beta.

The web service, database and uploaded files are hosted on Render. Google processes your sign-in through its own services. Microsoft distributes the companion through the Microsoft Store, and Acadia operates your Moodle sign-in. Those services also have their own privacy notices.

For assistant questions, selected excerpts from your own sources and recent chat, together with your question, are processed by a SchoolVault worker on the operator's dedicated School Mac mini using a locally running language model. They are not sent to an external AI model provider in this beta. Assistant replies are saved in your account. AI replies may be inaccurate; check the original course source before relying on dates or requirements.

Each account has its own vault. Other students do not receive access to your vault through the app. The operator and authorized infrastructure providers can process information as needed to run the service and provide support. This beta does not sell personal information, serve advertising, or pool students' private course material into a shared student vault. Information may be disclosed when required by applicable law.

## Storage and safeguards

Connections to SchoolVault use HTTPS. The database enforces account separation, and uploaded files are stored under account-specific private paths. Server session and companion tokens are stored as hashes. The Windows companion encrypts its local connection credential using Windows secure storage. Its separate Moodle browser profile remains on your device.

Course sources and notes retain versions, and the beta currently has no automatic deletion schedule. Data can remain until removed through an operator-assisted request; operational copies and backups may persist beyond removal from the active service. Archiving a chat, signing out, disconnecting a laptop or uninstalling the companion does not delete your cloud vault.

## Your choices and requests

- You can stop collection by closing the companion and revoke a laptop's SchoolVault connection in the web app.
- Resetting the companion removes its local pairing credential. It does not remove its separate Moodle browser profile. On Windows that profile is under `%APPDATA%\SchoolVault Companion Desktop\moodle-browser`; contact support for help removing local data safely.
- You can request access, correction or deletion of your account information by emailing **jpss2004@gmail.com** from your registered address. We may need to verify that the request belongs to the account holder. Account deletion is currently assisted by the operator; there is no self-service account deletion button.
- Do not upload passwords, identity documents or unrelated sensitive material. Only connect a Moodle account you are authorized to use.

SchoolVault is designed for university students and is not directed at children. If the beta's data practices change, this notice will be updated with a new date. Contact the address above with any privacy questions.
