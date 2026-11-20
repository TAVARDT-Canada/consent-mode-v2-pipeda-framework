# Consent Mode v2 & PIPEDA / Bill C-27 Framework | TAVARDT Canada

[![Validador de Consentimento](https://img.shields.io/badge/TAVARDT-Diagn%C3%B3stico%20T%C3%A9cnico-5b3cf5.svg)](https://tools.tavardt.com/ca/consent-mode-v2-checker/)
[![Conformidade](https://img.shields.io/badge/Jurisdi%C3%A7%C3%A3o-Canada-00C853.svg)](https://ag.tavardt.com/ca/cybersecurity/)

Google Consent Mode v2 implementation, tag governance, and PIPEDA / Bill C-27 (CPPA) compliance framework for Canadian enterprises.

Desenvolvido e mantido pela divisão de privacidade digital e engenharia de dados da **[TAVARDT Canada](https://ag.tavardt.com/ca/)**.

---

## 1. Execution Order & Architecture

Embed this script within the `<head>` of your website immediately prior to loading Google Tag Manager or analytics containers:

```html
<script src="consent-mode-v2.js"></script>
<!-- O contentor do Google Tag Manager ou scripts de medição seguem aqui -->
```

---

## 2. Technical Capabilities

* **Denied by Default:** Initializes ad and analytics storage parameters to 'denied' prior to user interaction.
* **Event-Driven Consent Update:** Provides window.tavardtUpdateConsent() to communicate consent signals via the dataLayer.
* **Data Redaction Enforcement:** Enforces ads_data_redaction to eliminate click parameters when marketing consent is absent.
* **URL Parameter Protection:** Enables url_passthrough to preserve measurement without persistent client storage.

---

## 3. Technical Audit Checklist

Consulte a lista detalhada de requisitos técnicos para este país:

* [Checklist Técnico de Conformidade](checklist.md)

---

## 4. Online Diagnostic Tools (Canada)

Audite a conformidade das suas etiquetas e proteja o seu domínio com ferramentas online verificadas:

* [Consent Mode v2 & PIPEDA Validator](https://tools.tavardt.com/ca/consent-mode-v2-checker/)
* [HTTP Security Headers Checker](https://tools.tavardt.com/ca/security-headers-check/)
* [DMARC & Anti-Spoofing Verifier](https://tools.tavardt.com/ca/dmarc-checker/)
* [Exposed Credentials & Secret Scanner](https://tools.tavardt.com/ca/exposed-files-scanner/)
* [Full Canadian Tools Portal](https://tools.tavardt.com/ca/)

---

## 5. Tag Governance & Privacy Advisory

For tag architecture audits, PIPEDA compliance, and analytics engineering in Canada, contact **[TAVARDT Canada](https://ag.tavardt.com/ca/contact/)**.
