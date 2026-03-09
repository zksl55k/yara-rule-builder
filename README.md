# yara-rule-builder
YARA Rule Builder — Threat Collections Toolkit


An interactive web-based tool for writing, validating, and exporting YARA rules — built for threat analysts and security researchers.

Live Demo
https://lucent-bombolone-c32716.netlify.app

What is YARA?
YARA is a pattern-matching tool used by threat intelligence analysts to identify and classify malware, suspicious files, and attack indicators. YARA rules define strings and conditions that describe malicious behavior — widely used in SOC environments, malware analysis, and threat hunting.

Features

Rule Builder — Visual form-based interface for writing YARA rules with metadata, strings, and conditions
String Types — Supports text, hex, and regex string patterns with modifiers (nocase, wide, ascii)
Condition Shortcuts — Quick-fill buttons for common conditions (any of them, all of them, etc.)
Rule Validator — Real-time syntax validation with descriptive error messages
Live Preview — See your generated YARA rule update in real time
Export — Download rules as .yar files or copy to clipboard
Example Rules — 4 pre-built rules to learn from and customize:

Suspicious PowerShell Execution
Phishing Document Macro
Ransomware Indicator
Qushing Detection (QR code phishing)




Example Rules Included
RuleSeverityDescriptionSuspicious_PowerShellHIGHDetects obfuscated PowerShell executionPhishing_Doc_MacroMEDIUMDetects Office documents with suspicious macrosRansomware_IndicatorCRITICALDetects common ransomware stringsQushing_DetectionHIGHDetects QR code phishing indicators

Technical Details
ComponentDetailLanguageVanilla HTML, CSS, JavaScriptDeploymentNetlifyDependenciesNone — fully self-containedString TypesText, Hex, RegexModifiersnocase, wide, ascii, nocase wide, nocase ascii

How to Use

Visit the live demo link above
Fill in the Builder tab with your rule name, metadata, strings and condition
Click Validate Rule to check for errors
Switch to the Preview tab to see your generated rule
Click Download .YAR to export your rule file


Disclaimer
Built as a portfolio project to demonstrate threat intelligence tooling skills for a Threat Collections Engineer role at Anthropic.

Author
Amanda — linkedin.com/in/amanda01010
