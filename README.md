# PoliteKey

PoliteKey serves one purpose and that is to generate random keys of length _n_
that are polite. What do I mean by polite? Well...let's a look at some keys
that certainly are not polite:

```
BSHITXY
OASSQ
PENIS
UDIKZ
MFAGJ
...
```

Do you notice anything? We've got some profanity in there, ruh oh! The last
thing we want is a potential user or customer support member reading off
"ASS" or "PENIS", etc.

Good news though! This is exactly what PoliteKey solves :)

PoliteKey will generate (as the name suggests) polite random keys that
exclude any profanity or slang.

### Usage
```go
PoliteKey.length(6) // "XAQMZY"
```
