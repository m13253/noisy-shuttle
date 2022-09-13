# noisy-shuttle

A tunnel built upon the brilliant idea of [shadow-tls](https://github.com/ihciah/shadow-tls) with DH key exchange piggybacked by camouflage TLS handshakes.

Inspired by https://github.com/ihciah/shadow-tls.

## TODO
- [ ] M:N connection multiplex
- [ ] Connection reuse
- [ ] Embed `e, ee` into server-side CCS in TLS 1.2
- [x] Handle TLS1.3 response from camouflage server properly
- [ ] Elligator for public key
- [ ] Utilize Keyshare?
- [ ] Specify TLS fingerprint (JA3)
- [ ] Configurable actions for unauthenticated client
- [ ] Random packet padding and even packets
