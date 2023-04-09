# General information


### How do SSL certificates work?

When browsers attempt to establish an encrypted session with a website that's secured with SSL, the following sequence of operations occurs in the background:
-	The browser connects to a web server secured with SSL and requests the server to prove its identity.
-	The web server receives the request and sends back a copy of its SSL certificate along with its public key.
-	The browser receives the certificate and checks its legitimacy by comparing it with a predefined list of trusted CAs. If the browser trusts the certificate, it creates a symmetrical key called the session key, encrypts the key using the server's public key, and sends it back to the server.
-	The web server decrypts the message using its private key, sends an acknowledgement—that is encrypted using the session key—back to the browser to start the session.
-	The browser and server then begin the session afterwards, in which all exchanged information is encrypted using the session key.

### KubeEdge

- Need to learn

### ArgoCD

- Add examples

### 
