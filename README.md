# Therapize

**Local-first clinical documentation for therapists.**

Record therapy sessions, transcribe speech-to-text, and generate clinical notes (DAP, SOAP, BIRP) — all on your device. No cloud. No data leaves your computer.

<p align="center">
  <img src="screenshots/01_dashboard.png" alt="Therapize Dashboard" width="800">
</p>

---

## Download

**[→ Download Latest Release](https://github.com/datanovaconsulting/therapize-releases/releases/latest)**

| Platform | Download |
|----------|----------|
| **Windows** | `.exe` installer |
| **macOS (Apple Silicon)** | `arm64.zip` |
| **macOS (Intel)** | `x64.zip` |
| **Linux** | `.AppImage` |

---

## macOS Installation

> **Important:** Therapize is an unsigned app. macOS will show a security warning the first time you open it.

### How to Open on macOS

1. Download and extract the `.zip` file
2. Move `Therapize.app` to your Applications folder
3. **Control-click** (or right-click) on Therapize
4. Select **"Open"** from the menu
5. Click **"Open"** in the security dialog

That's it! You only need to do this once. After the first time, Therapize opens normally.

*For troubleshooting, see [MAC_TRUST.md](./MAC_TRUST.md)*

---

## Complete Workflow

### 1. Start a New Session

Enter client initials or select from your existing clients.

<p align="center">
  <img src="screenshots/02_new_session.png" alt="New Session" width="700">
</p>

### 2. Client Session History

View all past sessions for each client with quick access to notes.

<p align="center">
  <img src="screenshots/03_client_sessions.png" alt="Client Sessions" width="700">
</p>

### 3. Record Your Session

One-click recording with live audio visualization. Works with any microphone.

<table>
<tr>
<td width="50%">
<p align="center"><strong>Ready to Record</strong></p>
<img src="screenshots/04_ready_to_record.png" alt="Ready to Record" width="100%">
</td>
<td width="50%">
<p align="center"><strong>Recording in Progress</strong></p>
<img src="screenshots/05_recording_in_progress.png" alt="Recording" width="100%">
</td>
</tr>
</table>

### 4. Automatic Transcription

Local AI transcribes your session. No audio ever leaves your device.

<table>
<tr>
<td width="50%">
<p align="center"><strong>Recording Complete</strong></p>
<img src="screenshots/06_recording_complete.png" alt="Recording Complete" width="100%">
</td>
<td width="50%">
<p align="center"><strong>Transcribing Audio</strong></p>
<img src="screenshots/07_transcribing_audio.png" alt="Transcribing" width="100%">
</td>
</tr>
</table>

### 5. Review Transcript

Review the full transcript with timestamps before generating notes.

<p align="center">
  <img src="screenshots/08_session_review.png" alt="Session Review" width="700">
</p>

### 6. Generate Clinical Notes

Choose your preferred note format: **DAP**, **SOAP**, or **BIRP**.

<p align="center">
  <img src="screenshots/09_summary_type_selection.png" alt="Summary Type Selection" width="500">
</p>

### 7. Edit & Refine

Edit generated notes with the source transcript alongside for reference.

<table>
<tr>
<td width="50%">
<p align="center"><strong>Edit DAP Note</strong></p>
<img src="screenshots/10_dap_note_editor.png" alt="DAP Editor" width="100%">
</td>
<td width="50%">
<p align="center"><strong>Side-by-Side with Transcript</strong></p>
<img src="screenshots/11_dap_with_transcript.png" alt="DAP with Transcript" width="100%">
</td>
</tr>
</table>

### 8. Export to PDF

Print-ready PDF export with professional formatting.

<p align="center">
  <img src="screenshots/12_pdf_preview.png" alt="PDF Preview" width="500">
</p>

---

## Privacy First

- All audio and transcripts stay on your device
- No cloud API calls (except one-time model downloads)
- No internet required after setup
- HIPAA-friendly local processing

---

## Requirements

- **Windows 10/11** — NVIDIA GPU optional for faster processing
- **macOS 11+** — Apple Silicon recommended
- **Linux** — AppImage format
- **Disk Space:** ~8GB for AI models

---

## Auto-Updates

Therapize checks for updates automatically:
- **Windows/Linux:** One-click updates
- **macOS:** Download notification (manual install)

See [UPDATE.md](./UPDATE.md) for details.

---

## Support

Having issues? [Open an issue](https://github.com/datanovaconsulting/therapize-releases/issues) on GitHub.

---

<p align="center">
  <sub>Built with care for therapists who value privacy.</sub>
</p>
