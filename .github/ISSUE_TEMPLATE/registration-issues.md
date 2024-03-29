---
name: Registration issues
about: Problems registrering as a TPP.
title: ''
labels: bug
assignees: ''

---

## Before opening an issue regarding registration problems please ensure that:

- [ ] You are following the documentation at https://developer.openbanking.prod.lunar.app/catalog/default/api/Registration
- [ ] Your certificate chain is valid
- [ ] Your intermediate certificate is on the EU Trusted List: https://eidas.ec.europa.eu/efda/tl-browser/#/screen/home

If all the above looks good you can open an issue.

## Required information

**Certificate chain used during registration:**

**Output of the registration call:**

**Time of the registration request:**

**Link to the intermediate certificate on the [EU Trusted list](https://eidas.ec.europa.eu/efda/tl-browser/#/screen/home):**

**Debug information**

* Call `https://debug.openbanking-sandbox.prod.lunar.tech` including your full certificate chain and private key (eg. `curl https://debug.openbanking-sandbox.prod.lunar.tech --cert your_full_certificate_chain.pem --key your_private_key.pem`)
* Note the time of the call:

---

Please ensure that all information has been checked and are valid!

Issues with missing information will be closed.
