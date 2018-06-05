# keys

My OpenPGP keys, in case they're needed, with instructions to use them with the [Keybase](https://keybase.io/) app.

## base

```
$ date -uI
2018-06-05

$ gpg --with-fingerprint pgp_keys.asc
pub  4096R/A79F7188 2014-12-31 keybase.io/fak3r <fak3r@keybase.io>
      Key fingerprint = A770 47C7 F6B6 2C9E B80F  326F 04A1 69CC A79F 7188
sub  2048R/13A6E30A 2014-12-31 [expires: 2022-12-29]
sub  2048R/DF3036DA 2014-12-31 [expires: 2022-12-29]
```

## details

* fingerprint:	`A77047C7F6B62C9EB80F326F04A169CCA79F7188`
* 64-bit:	`04A169CCA79F7188`
* curl/raw:	[this key](https://keybase.io/fak3r/pgp_keys.asc?fingerprint=a77047c7f6b62c9eb80f326f04a169cca79f7188) | [all PGP keys](https://keybase.io/fak3r/pgp_keys.asc)

## tips from keybase

* curl + gpg pro tip: import fak3r's keys
```curl https://keybase.io/fak3r/pgp_keys.asc | gpg --import```

* the Keybase app can push to gpg keychain, too
```keybase pgp pull fak3r```

### thanks

openpgp, keybase, github, and... you.
