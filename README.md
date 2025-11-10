<!-- HERO -->
<p align="center">
  <img src="assets/header.svg" alt="Bajrang Solge — Android Automotive & AOSP Engineer" width="100%"/>
</p>

<h1 align="center">Android Automotive • AOSP • HAL • JNI • Binder</h1>
<p align="center">
  Building IVI & Cluster systems end-to-end — from HALs & services to real-time vehicle data on screen.
</p>

<p align="center">
  <a href="mailto:bajrangsolge07@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-bajrangsolge07%40gmail.com-222?style=for-the-badge&logo=gmail"></a>
  <a href="https://www.linkedin.com/in/bajrang-solge-811b2a212/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Bajrang%20Solge-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="docs/Bajrang_Solge_AOSP_Resume.pdf"><img alt="Resume" src="https://img.shields.io/badge/Resume-AAOS%20%2F%20AOSP-0e7490?style=for-the-badge&logo=adobeacrobatreader"></a>
  <img alt="Location" src="https://img.shields.io/badge/Pune%2C%20India-16a34a?style=for-the-badge">
</p>

---

## 🔧 Core Expertise
`AAOS/AOSP` • `HAL (C++)` • `JNI/NDK` • `Binder IPC` • `System Services` • `CarPropertyManager`  
`Java/Kotlin` • `Linux / init.rc` • `Raspberry Pi` • `CAN bus` • `Diagnostics` • `Jenkins/GitHub Actions`

---

## 🚀 Signature Projects (curated)
<table>
<tr>
<td width="50%">
  
### AAOS IVI on Raspberry Pi  
Minimal board bring-up + custom HALs + fast demo UX  
<p>
  <a href="https://github.com/bajrangsolge/aaos-ivi-rpi"><b>Code</b></a> • 
  <a href="https://github.com/bajrangsolge/aaos-ivi-rpi#demo"><b>Demo (video)</b></a> • 
  <a href="https://github.com/bajrangsolge/aaos-ivi-rpi/tree/main/docs"><b>Docs</b></a>
</p>
<p>
  <img src="https://img.shields.io/badge/AAOS-13/14-111?style=flat">&nbsp;
  <img src="https://img.shields.io/badge/HAL-JNI-111?style=flat">&nbsp;
  <img src="https://img.shields.io/badge/CAN-telemetry-111?style=flat">
</p>

**Case Study**  
- Goal: get end-to-end **vehicle data → HAL → app UI** in < 120 ms  
- Role: system + app + HAL  
- Result: stable 30/60 fps UI; deterministic property updates

</td>
<td width="50%">

### Cluster UI + CarProperty Realtime  
Automotive cluster UI hooked to VHAL with graceful fallbacks  
<p>
  <a href="https://github.com/bajrangsolge/aaos-cluster-demo"><b>Code</b></a> • 
  <a href="https://github.com/bajrangsolge/aaos-cluster-demo#video"><b>Demo (video)</b></a>
</p>
<p>
  <img src="https://img.shields.io/badge/CarPropertyManager-live-111?style=flat">&nbsp;
  <img src="https://img.shields.io/badge/Jetpack-Compose-111?style=flat">&nbsp;
  <img src="https://img.shields.io/badge/NDK-bridge-111?style=flat">
</p>

**Case Study**  
- Goal: clean UI **without dropped frames** under burst updates  
- Role: UI perf + data model  
- Result: consistent 60 fps; test harness for property storms

</td>
</tr>
<tr>
<td>

### JNI + HAL Playground (Interview-ready)
Tiny, commented labs for **Java ↔ C++ ↔ Binder**  
<p>
  <a href="https://github.com/bajrangsolge/jni-hal-playground"><b>Code</b></a> • 
  <a href="https://github.com/bajrangsolge/jni-hal-playground/tree/main/docs"><b>Docs</b></a>
</p>

**What’s inside:**  
- 60-line JNI bridge  
- Service registration + client call  
- Logging patterns: `logcat`, `dmesg`, ServiceManager

</td>
<td>

### Smart Fuel Pump Controller (R&D)
CAN/UDS telemetry → slope logic → controlled pump duty  
<p>
  <a href="https://github.com/bajrangsolge/smart-fuel-pump-controller"><b>Code</b></a> • 
  <a href="https://github.com/bajrangsolge/smart-fuel-pump-controller#ui"><b>UI</b></a>
</p>

**Case Study**  
- Goal: safe control policies with transparent UI  
- Role: firmware + Android client  
- Result: deterministic state machine + diagnostics panel

</td>
</tr>
</table>

---

## 🧭 How I work
- **DDF (Design–Drive–Fix):** design diagrams → drive a minimal demo → fix using logs/metrics  
- **Obsessive Docs:** every repo ships with a single-screen README (**diagram + run + demo**)  
- **Perf mind-set:** guardrails for latency, jank, and binder hops

<details>
<summary><b>Deep dives (open)</b></summary>

### 1) Boot & Services
- `init.rc` units, SELinux contexts, service crash loops  
- Service discovery & binder stability under load

### 2) Vehicle Data
- Property lifecycles, update rates, priority channels  
- Backpressure handling for bursty signals

### 3) JNI + HAL Craft
- Minimal, auditable bridges; predictable ownership  
- Log points that actually help during field issues
</details>

---

## 📊 Neat, minimal metrics
<p align="center">
  <img height="155" src="https://github-readme-stats.vercel.app/api?username=bajrangsolge&show_icons=true&hide_border=true&theme=tokyonight">
  <img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bajrangsolge&layout=compact&hide_border=true&theme=tokyonight">
</p>

---

## 🤝 Let’s build
If you’re shipping AAOS features, porting to new boards, or need HAL/JNI help, ping me:  
**bajrangsolge07@gmail.com** · Pune, India

---
