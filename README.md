Here are my scripts I like to use to manage SSL/TLS certs.

<h2>makePrivateKey.sh</h2>
Makes your private key. It only really needs to be called when you're first setting things up.

<h2>makeCSR.sh</h2>
Creates a CSR, using your private key

<h2>makeCombinedCrt.sh</h2>
Makes a combined crt from what's given by the SSL/TLS vendor I tend to use (optional)

