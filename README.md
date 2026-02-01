# Therapize

**Blazing-fast clinical documentation powered by your GPU.**

Record therapy sessions, transcribe in seconds, and generate polished clinical notes (DAP, SOAP, BIRP) — all running locally on your machine. No cloud uploads. No per-minute fees. No data ever leaves your computer.

<p align="center">
  <img src="screenshots/01_dashboard.png" alt="Therapize Dashboard" width="800">
</p>

---

## GPU-Powered AI

Therapize runs entirely on your GPU for lightning-fast transcription and note generation:

| Platform | Acceleration | Performance |
|----------|--------------|-------------|
| **Mac (Apple Silicon)** | Metal GPU | Transcribe 1-hour sessions in ~2 minutes |
| **Windows/Linux** | NVIDIA CUDA | Transcribe 1-hour sessions in ~90 seconds |

**GPU Required.** Your graphics card does the heavy lifting — no cloud APIs, no per-minute charges, no waiting. Just fast, private, local AI.

---

## Download

**[→ Download Latest Release](https://github.com/datanovaconsulting/therapize-releases/releases/latest)**

| Platform | Download | GPU |
|----------|----------|-----|
| **Windows** | `.exe` installer | NVIDIA CUDA |
| **macOS (Apple Silicon)** | `.dmg` installer | Metal (M-series) |
| **Linux** | `.AppImage` | NVIDIA CUDA |

> **Note:** macOS Intel is not supported. A GPU is required for transcription and note generation.

---

## macOS Installation

> **Important:** Therapize is an unsigned app. macOS will show a security warning the first time you open it.

### How to Open on macOS

1. Download and open the `.dmg` file
2. Drag `Therapize.app` to your Applications folder
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

### 4. GPU-Powered Transcription

Your GPU transcribes the entire session in seconds — not minutes. No waiting, no cloud uploads, no per-minute fees.

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

Choose your preferred note format: **DAP**, **SOAP**, or **BIRP**. AI generates a complete draft in seconds.

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

## Why Therapize?

### Privacy First
- All audio and transcripts stay on your device
- No cloud API calls (except one-time model downloads)
- No internet required after setup
- HIPAA-friendly local processing

### Save Time & Money
- **$49.99/month** — less than 30 minutes of your billable time
- No per-minute transcription fees or API charges
- Generate complete notes in under 5 minutes
- Unlimited sessions, unlimited notes

### Professional Quality
- State-of-the-art Whisper speech recognition
- Smart note generation with Mistral AI
- Export-ready PDF formatting

---

## Requirements

| Platform | Requirements |
|----------|--------------|
| **Windows** | Windows 10/11, NVIDIA GPU (GTX 1060+), 16GB RAM |
| **macOS** | macOS 11+, Apple Silicon (M-series), 16GB RAM |
| **Linux** | Ubuntu 20.04+, NVIDIA GPU with CUDA, 16GB RAM |
| **Disk Space** | ~8GB for AI models (SSD recommended) |

**GPU is required.** Therapize uses your graphics card for fast, local AI processing.

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
  <strong>Stop typing during sessions. Start documenting in seconds.</strong><br>
  <sub>Built with care for therapists who value privacy and their time.</sub>
</p>
