# Law
`Updated on March 16th, 2021`

If a document allegadely signed by the empire isn't on this page, it wasn't signed or it's been voided.
## Laws in force
A list of all laws active in the Berry Empire
<ul class="law">
  <li>
    <span><a href="./constitution">Constitution</a></span>
    <span><a href="./constitution.md" download>Source</a> | <a href="./constitution.bin" download>Cryptographic signature</a></span>
  </li>
  <li>
    <span><a href="./territory">Subterritory governance</a></span>
    <span><a href="./territory.md" download>Source</a> | <a href="./territory.bin" download>Cryptographic signature</a></span>
  </li>
  <li>
    <span><a href="./privacy">Privacy</a></span>
    <span><a href="./privacy.md" download>Source</a> | <a href="./privacy.bin" download>Cryptographic signature</a></span>
  </li>
</ul>

### Treaties
A list of all signed treaties
<ul class="law">
  <li>
    <span><a href="./treaty/1_iac_charter.html">International Aerospace Community Charter</a></span>
    <span><a href="./treaty/1_iac_charter.md" download>Source</a> | <a href="./treaty/1_iac_charter.bin" download>Cryptographic signature</a></span>
  </li>
  <li>
    <span><a href="./treaty/2_ca_charter.html">Cupertino Alliance Charter</a></span>
    <span><a href="./treaty/2_ca_charter.md" download>Source</a> | <a href="./treaty/2_ca_charter.bin" download>Cryptographic signature</a></span>
  </li>
  <li>
    <span><a href="./treaty/3_peto_charter.html">Pan European Trade Organization Charter</a></span>
    <span><a href="./treaty/3_peto_charter.md" download>Source</a> | <a href="./treaty/3_peto_charter.bin" download>Cryptographic signature</a></span>
  </li>
  <li>
    <span><a href="./treaty/4_hamburg.html">Hamburg Treaty</a></span>
    <span><a href="./treaty/4_hamburg.md" download>Source</a> | <a href="./treaty/4_hamburg.bin" download>Cryptographic signature</a></span>
  </li>
</ul>

### Recognition treaties
<ul class="law">
  <li>
    <span><a href="./recognition/aarland.html">Republic of Aarland</a></span>
    <span><a href="./recognition/aarland.md" download>Source</a> | <a href="./recognition/aarland.bin" download>Cryptographic signature</a></span>
  </li>
</ul>

### Decrees
A list of all imperial decrees
<ul class="law">
  <li>
    <span><a href="./decree/tax.html">Tax decree</a></span>
    <span><a href="./decree/tax.md" download>Source</a> | <a href="./decree/tax.bin" download>Cryptographic signature</a></span>
</ul>

## Verify the signatures
You are free to verify the signatures against our <a href="./public_key.pem">Public Key</a>.
We also encourage you to backup our public key.

### How to verify?

- Log into a Windows, macOS or Linux machine with <a href="https://www.openssl.org/">OpenSSL</a> installed.
- Download the imperial <a href="./public_key.pem">Public Key</a>.
- Download the `.bin` signature you'd like to verify as well as the signed file (treaty, etc).
- Run `openssl dgst -sha256 -verify public_key.pem -signature signature.bin treaty.md` to verify the signature against the treaty and our public key (replace filenames with actual filenames if they differ.)
- See "Verified OK" or "Verification Failure".
