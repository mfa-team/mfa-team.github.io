

# Deutsche Bank

### Identity proofing

- Local branch


### Authenticators
- QR Code reader [O]
- Look-up secret
- SIM card
- SW Authenticator [O]
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
- SW Authenticator
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

- QR Code Reader
![IP-6](../../sequence-diagrams/ip/ip-6.png)

- Look-up secret

```mermaid
sequenceDiagram
    participant User
    participant Lookup secret
	participant Browser
    
    User->>Browser: username, password, operation
    Browser->>User: coordinates
    User->>Lookup secret: coordinates
    Lookup secret->>User: otp
    User->>Browser: otp
```

- SIM card

```mermaid
sequenceDiagram
    participant User
    participant SIM
	participant Browser
    
    User->>Browser: username, password, operation
    Browser->>SIM: otp, operation description
    User-->>SIM: open SMS
    SIM-->>User:operation description
    User-->>SIM: ok
    SIM->>User: otp
    User->>Browser: otp
```

- SW Authenticator

```mermaid
sequenceDiagram
    participant User
    participant App
	participant Browser
    
    User->>Browser: username, password, operation
    App-->>Browser: scan
    Browser->>App: QR code (opid)
    App->>User: operation description
    User->>App: ok
    App->>User: otp
    User->>Browser: otp
```

### Mobile payments

tbd


### Requirements 

|  RL1 | RL2 | RL3 | RL4 | RL5 | RL6 | RL7 | RL8 | RL9 |
|---|---|---|---|---|---|---|---|---|
| <i class="icon-star"></i> | <i class="icon-star"></i> | <i class="icon-star"></i> | <i class="icon-star-half-alt"></i> | <i class="icon-star-half-alt"></i> | <i class="icon-star-half-alt"></i> | <i class="icon-star"></i> | <i class="icon-star-half-alt"></i> | <i class="icon-star-half-alt"></i> |

### Best Practices

| BP1 | BP2 | BP3 | BP4 | BP5 | BP6 | BP7 | BP8 |
|---|---|---|---|---|---|---|---|
| <i class="icon-star-empty"></i> | <i class="icon-star-half-alt"></i> | <i class="icon-star"></i> | <i class="icon-star-half-alt"></i> |<i class="icon-star"></i> | <i class="icon-star-half-alt"></i> |<i class="icon-star-half-alt"></i> | <i class="icon-star"></i> |






