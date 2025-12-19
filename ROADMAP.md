# Roadmap — Invizible Tracker Control Pro

⚠️ This project is experimental and under active design.
Security and correctness take priority over speed.

---

## Phase 0 — Foundation (CURRENT)
Status: 🟡 In progress

- [x] High-level architecture
- [x] Single VPNService design
- [x] Policy-based routing model
- [x] TrackerControl-style logic design
- [ ] Real packet parsing in VPNCore
- [ ] Buildable debug APK

Goal:
Establish a correct, conflict-free foundation.

---

## Phase 1 — MVP (v0.1)
Status: 🔜 Planned

Focus: **Tracker control + DNSCrypt only**

- [ ] Per-app tracker detection & blocking
- [ ] DNSCrypt integration (non-Tor apps)
- [ ] Per-app firewall rules
- [ ] Basic UI for app configuration
- [ ] Leak prevention tests

Out of scope:
- Tor
- I2P

---

## Phase 2 — Tor Integration (v0.2)
Status: 🔜 Planned

- [ ] Tor routing backend
- [ ] Tor DNS handling
- [ ] Per-app Tor routing
- [ ] Strict isolation from tracker filtering
- [ ] Threat model review

---

## Phase 3 — I2P Integration (v0.3)
Status: 🔜 Planned

- [ ] I2P daemon integration
- [ ] I2P routing backend
- [ ] Advanced routing policies

---

## Phase 4 — Hardening & Audit
Status: 🔜 Planned

- [ ] Security audit
- [ ] Performance optimization
- [ ] Battery usage review
- [ ] Leak prevention validation
- [ ] Documentation improvements

---

## Long-term Goals
- F-Droid compatibility
- Reproducible builds
- Strong community governance
- Privacy-focused UI/UX

---

## Non-Goals
- No telemetry
- No analytics
- No cloud services
- No advertising
- No data collection
