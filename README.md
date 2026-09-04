# Sơn Hải Work — mockup (Mobile Field)

Interactive prototype of the field-crew half of an HR / attendance ERP: the worker's
day and the crew leader's approvals. React + Vite, static, no backend.

Served over HTTPS on purpose — the prototype is meant to be opened on a real phone, and
`navigator.geolocation` / `getUserMedia` are blocked on `file://` and on a plain
`http://` LAN address.

Demo data only. No keys, no personal data. Built from `mockup/mobile-field` in the
source repository by `.claude/skills/deploy-mockup/deploy.sh` — edits here are
overwritten by the next deploy.
