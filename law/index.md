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
Contents the imperial <a href="./public_key.pem">Public Key</a>:
```
-----BEGIN PUBLIC KEY-----
MIICIjANBgkqhkiG9w0BAQEFAAOCAg8AMIICCgKCAgEA2sJxY8hLsJ3026+4104p
cxd+B/SyAjmtBhk/O1BGw3kPRnz+MQ4BDjp5sWsY8/Qj8DdOL6nx5x68/B8sGJSO
qXFSg40/pndMUTz4SLVl09F2pys1GvFGwjj6TlL3JtzlBLDagnFoLiaM2A+CluWW
bg0Us9gZrfCOviBjr1/5OIlU/aerHQC54jHpZiMjNZZDJiE9msYsWfPUgZVi4p1p
2dYuf3qjQi2jR20Bnqq9srxj502SA3+UB/QeMsnGDVxIWtnuwQkZNAC6e4kI49ct
nkvJcH+PGw4obwx4mTK7lX0x8C7dIz1BJMZW59pmx3u4WkK12Qe3zv2xMH2PsWAM
vvS82Rkz9VKz5Vigr2nU8RNMRmBxFh/emTlwnM0+Vig08Xf3dbbf7InGzEC9J8aU
qugao/+SmKWM1AlbGBhPJksEU5Xo35CMDjjp5QlFBm8XGj32qwWvwqr/NmKcZR82
EwRF+GGBOJXx2aNWOPmowFSeZ7Oxqe2u01UqnQ9XTsHX/Q+aRd0CFTbQqgSR45jg
EjOSSCd/8zPFXsF1e+NMIohA4E1z8cLmjp8P2IhYaIl/k8hnYS0QVsAMsxqKs3+6
skG7qoI9bweOi7bHnWDissZ4VH7pjPxAK0zZEHToJLPgchqDXWyMHGSk0/LDAH8F
yPN7HYW5t60t216eWcvDfeMCAwEAAQ==
-----END PUBLIC KEY-----
```
### How to verify?

- Log into a Windows, macOS or Linux machine with <a href="https://www.openssl.org/">OpenSSL</a> installed.
- Download the imperial <a href="./public_key.pem">Public Key</a>.
- Download the `.bin` signature you'd like to verify as well as the signed file (treaty, etc).
- Run `openssl dgst -sha256 -verify public_key.pem -signature signature.bin treaty.md` to verify the signature against the treaty and our public key (replace filenames with actual filenames if they differ.)
- See "Verified OK" or "Verification Failure".
