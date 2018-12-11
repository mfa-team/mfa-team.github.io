

# Deutsche Bank

## Sources
[Main Website](https://www.deutsche-bank.de/pk.html)	[Account Info](https://www.deutsche-bank.de/pfb/content/pk-digital-banking-uebersicht.html)	[FAQs](https://www.deutsche-bank.de/pk/digital-banking/weitere-themen/faq-s.html)	[HW Authenticator](https://www.deutsche-bank.de/pfb/data/docs/pk-digital-banking-photo-tan-bedienungsanleitung-lesegeraet.pdf)	[SW Authenticator](https://www.deutsche-bank.de/pk/digital-banking/sicherheit/phototan.html)	[SMS](https://www.deutsche-bank.de/pfb/content/pk-digital-banking-mobile-tan.html) [Mobile App](https://play.google.com/store/apps/details?id=com.db.pwcc.dbmobile)	[App Authenticator](https://play.google.com/store/apps/details?id=com.db.pbc.phototan.db)	[Interactive Demo](https://secure.deutsche-bank.de/pbc/trxmdemokonto/loginpin/goto.do)	[Video Tutorial](https://www.youtube.com/watch?v=UxXXrSWCRsc)	 [Video Overview](https://www.youtube.com/watch?v=iUlRmDM4opQ) 

## Implementation details

### Identity proofing

- Local branch


### Authenticators
- QR Code reader (Authenticator device) [O]
- Look-up secret
- SIM card
- Software Authenticator [O]
- Fingerprint (on smartphone)

### Binding and activation
- QR Code Reader
	 1. Request: consequent to enrollment
	 2. Delivery: at home (remote)
	 3. Activation: with activation letter (remote)
- Look-up secret
	1. Request: branch
	 2. Delivery: branch
	 3. Activation: branch - already active
- SIM card
	1. Request: remote
	 2. Delivery: --
	 3. Activation: remote
- Software Authenticator
	1. Request: remote
	2. Delivery: remote
	3. Activation: remote (leveraging SIM card)
- Fingerprint
	1. Request: remote
	2. Delivery: remote
	3. Activation: remote

### Exemptions
Login only

### Internet payments

- Credentials + QR Code Reader (Authenticator - HW device)

![IP-6](../../sequence-diagrams/ip/IP-6.png)

- Credentials + Look-up secret

![IP-11](../../sequence-diagrams/ip/IP-11.png)

- Credentials + SIM card

![IP-15](../../sequence-diagrams/ip/IP-15.png)

- Credentials + Software Device (App)

![IP-21](../../sequence-diagrams/ip/IP-21.png)

### Mobile payments

- Credentials + Look-up secret

![MP-10](../../sequence-diagrams/mp/MP-10.png)

- Credentials + Software Device (App)

![MP-19](../../sequence-diagrams/mp/MP-19.png)

- Fingerprint + Look-up secret

![MP-25](../../sequence-diagrams/mp/MP-25.png)

- Fingerprint + Software Device (App)

![MP-27](../../sequence-diagrams/mp/MP-27.png)

### Requirements 

|  RL1 | RL2 | RL3 | RL4 | RL5 | RL6 | RL7 | RL8 | RL9 |
|---|---|---|---|---|---|---|---|---|
| <i class="icon-star"></i> | <i class="icon-star"></i> | <i class="icon-star"></i> | <i class="icon-star-half-alt"></i> | <i class="icon-star-half-alt"></i> | <i class="icon-star-half-alt"></i> | <i class="icon-star"></i> | <i class="icon-star-half-alt"></i> | <i class="icon-star-half-alt"></i> |

### Best Practices

| BP1 | BP2 | BP3 | BP4 | BP5 | BP6 | BP7 | BP8 |
|---|---|---|---|---|---|---|---|
| <i class="icon-star-empty"></i> | <i class="icon-star-half-alt"></i> | <i class="icon-star"></i> | <i class="icon-star-half-alt"></i> |<i class="icon-star"></i> | <i class="icon-star-half-alt"></i> |<i class="icon-star-half-alt"></i> | <i class="icon-star"></i> |






