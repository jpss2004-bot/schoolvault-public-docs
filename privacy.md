# Neyvu privacy notice

Last updated: October 8, 2026

Neyvu is an independent, invitation-only student beta operated by Jose Pablo Samano (Microsoft Store publisher: jpss2004-bot). This notice covers Neyvu Companion and its connected Neyvu web app. Support and privacy contact: **jpss2004@gmail.com**. Neyvu is not affiliated with or endorsed by Acadia University, Google or Microsoft.

## Information we process

- **Account:** Google account identifier, verified email address and name, plus your chosen time zone. Google sign-in requests identity scopes only (`openid`, `email`, `profile`). This beta does not request Gmail mailbox access or retain Google's provider access token for mail.
- **Moodle connection:** the Moodle account label and account identifier you confirm, course titles and links, visible text from supported course and activity pages, capture times and coverage warnings. Collected text can include instructor and peer content visible to your Moodle account.
- **Your work:** notes and their versions, chat questions, drafts and assistant replies, selected course context, source references, personal study plans and progress, saved choices and corrections, and supported files you upload or choose to import. Supported documents include PDF, Word, PowerPoint and plain text. Some study-session history and appearance or accessibility preferences are saved in your browser; clearing browser storage can remove those local records.
- **Pilot access and feedback:** your access request, approval or invitation record, account access status and email delivery status. If you explicitly share pilot feedback, the operator can review the report and your account email. Your private chats, notes and course files are not attached automatically.
- **Operation:** session and device records, connection status, collection timestamps, jobs and audit records. Hosting providers may also process ordinary request metadata, such as IP addresses, for operating their services.

Neyvu Companion opens a separate Microsoft Edge profile for you to sign in directly to Acadia Moodle. It reads rendered course content after you confirm the Moodle identity. The companion does not capture your Moodle password or upload the Edge profile or its session cookies to Neyvu. Cookies and browser session data remain on your laptop. The capture reads supported visible pages and can acquire supported linked files. File collection and document reading are separate: saving an original does not guarantee readable text. Restricted or unloaded content, unsupported files, external media, grades and submission receipts may remain unavailable; check the named gaps and original Moodle sources.

## Why and where information is processed

We use this information to authenticate you, connect your own Moodle account, maintain your course vault, retrieve relevant material, save your work, generate requested assistant answers and operate and troubleshoot the beta.

The web service, database and uploaded files are hosted on Render. Google processes your sign-in through its own services. The operator uses an existing Gmail sender for sign-in and pilot access emails; this does not give Neyvu access to your Gmail mailbox. Microsoft distributes the companion through the Microsoft Store, and Acadia operates your Moodle sign-in. Those services also have their own privacy notices.

For assistant questions, selected excerpts from your own sources, recent chat, saved study work and relevant planning context, together with your question, are processed by a Neyvu worker on the operator's dedicated School Mac mini using a locally running language model. They are not sent to an external AI model provider in this beta. Assistant replies are saved in your account. AI replies may be inaccurate; check the original course source before relying on dates or requirements.

Each account has its own vault. Other students do not receive access to your vault through the app. The operator and authorized infrastructure providers can process information as needed to run the service and provide support. This beta does not sell personal information, serve advertising, or pool students' private course material into a shared student vault. Information may be disclosed when required by applicable law.

## Storage and safeguards

Connections to Neyvu use HTTPS. The database enforces account separation, and uploaded files are stored under account-specific private paths. Server session and companion tokens are stored as hashes. The Windows companion encrypts its local connection credential using Windows secure storage. Its separate Moodle browser profile remains on your device.

Course sources and notes retain versions, and the beta currently has no automatic deletion schedule. Data can remain until removed through an operator-assisted request; operational copies and backups may persist beyond removal from the active service. Archiving a chat, signing out, disconnecting a laptop or uninstalling the companion does not delete your cloud vault.

## Your choices and requests

- You can stop collection by closing the companion and revoke a laptop's Neyvu connection in the web app.
- Choosing **Disconnect this laptop** confirms revocation of a readable connection grant, then clears the local pairing and isolated Moodle browser sign-in. If Neyvu cannot confirm disconnection, the saved connection is retained so you can retry or revoke the laptop on the website first. On Windows the isolated profile uses the retained internal path `%APPDATA%\SchoolVault Companion Desktop\moodle-browser`; the old folder name does not mean a separate account.
- You can request access, correction or deletion of your account information by emailing **jpss2004@gmail.com** from your registered address. We may need to verify that the request belongs to the account holder. Account deletion is currently assisted by the operator; there is no self-service account deletion button.
- Do not upload passwords, identity documents or unrelated sensitive material. Only connect a Moodle account you are authorized to use.

Neyvu is designed for university students and is not directed at children. If the beta's data practices change, this notice will be updated with a new date. Contact the address above with any privacy questions.
