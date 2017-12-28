# Hello!

This is a test repo to make sure I 've got signed commits and stuff set up correctly!

The SHA256 fingerprint of the public key is `0448 F8EA A55E 7DC5 2F93  019F B7E1 258B 1896 B531`

[npiperelay](https://github.com/jstarks/npiperelay) is a tool written by jstarks to relay named pipes in Windows into WSL through socat.

Gpg4Win doesn't use named pipes, instead uses a [libassuan](https://github.com/gpg/libassuan) to emulate Unix domain sockets. I've added suport for this into npiperelay to enable use of smart cards in WSL!
