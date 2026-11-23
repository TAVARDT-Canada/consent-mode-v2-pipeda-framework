# Canadian Privacy & Tag Governance Checklist

**Marco Regulatório:** PIPEDA and Bill C-27 (Consumer Privacy Protection Act) Standards  
**Mantido por:** [TAVARDT Canada](https://ag.tavardt.com/ca/)  

---

## Verificações Técnicas Obrigatórias

* **Meaningful Consent Alignment:** Ensure telemetry storage defaults to 'denied' until the user expresses clear agreement.
* **Bill C-27 Opt-In Controls:** Restrict behavioral profiling pixels from firing prior to affirmative consent.
* **PII Redaction Audits:** Audit dataLayer variables to prevent personally identifiable data disclosure.
* **Tag Firing Rules in GTM:** Sequence conversion tags to execute only after consent update events.

---

## Online Technical Tools

Valide a implementação das suas etiquetas utilizando a suíte de diagnósticos da TAVARDT:

* [Consent Mode v2 & PIPEDA Validator](https://tools.tavardt.com/ca/consent-mode-v2-checker/)
* [HTTP Security Headers Checker](https://tools.tavardt.com/ca/security-headers-check/)
* [DMARC & Anti-Spoofing Verifier](https://tools.tavardt.com/ca/dmarc-checker/)
* [Exposed Credentials & Secret Scanner](https://tools.tavardt.com/ca/exposed-files-scanner/)
* [Full Canadian Tools Portal](https://tools.tavardt.com/ca/)

---

## Consultoria Especializada

For tag architecture audits, PIPEDA compliance, and analytics engineering in Canada, contact **[TAVARDT Canada](https://ag.tavardt.com/ca/contact/)**.
