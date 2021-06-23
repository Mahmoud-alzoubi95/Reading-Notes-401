# What is SSH

- SSH, or Secure Shell, is a remote administration protocol that allows users to control and modify their remote servers over the Internet.

- The service was created as a secure replacement for the unencrypted Telnet and uses cryptographic techniques to ensure that all communication to and from the remote server happens in an encrypted manner.

## How Does SSH Work
The SSH key command instructs your system that you want to open an encrypted Secure Shell Connection. {user} represents the account you want to access. For example, you may want to access the root user, which is basically synonymous for system administrator with complete rights to modify anything on the system. {host} refers to the computer you want to access. This can be an IP Address (e.g. 244.235.23.19) or a domain name (e.g. www.xyzdomain.com).

When you hit enter, you will be prompted to enter the password for the requested account. When you type it in, nothing will appear on the screen, but your password is, in fact being transmitted. Once you’re done typing, hit enter once again. If your password is correct, you will be greeted with a remote terminal window.

* **Symmetric Encryption:** Symmetric encryption is a form of encryption where a secret key is used for both encryption and decryption of a message by both the client and the host. Effectively, any one possessing the key can decrypt the message being transferred.

* **Asymmetric Encryption**: Unlike symmetrical encryption, asymmetrical encryption uses two separate keys for encryption and decryption. These two keys are known as the public key and the private key. Together, both these keys form a public-private key pair.

### How Does SSH Work with These Encryption Techniques
The way SSH works is by making use of a client-server model to allow for authentication of two remote systems and encryption of the data that passes between them.
SSH operates on TCP port 22 by default (though this can be changed if needed). The host (server) listens on port 22 (or any other SSH assigned port) for incoming connections. It organizes the secure connection by authenticating the client and opening the correct shell environment if the verification is successful.

## Conclusion:
Gaining an in-depth understanding of the underlying how SSH works can help users understand the security aspects of this technology. Most people consider this process to be extremely complex and un-understandable, but it is much simpler than most people think. If you’re wondering how long it takes for a computer to calculate a hash and authenticate a user, well, it happens in less than a second. In fact, the maximum amount of time is spent in transferring data across the Internet.

Hopefully, this SSH tutorial has helped you see the way different technologies can be clubbed together to create a robust system in which each mechanism has a very important role to play. Also, now you know why Telnet became a thing of the past as soon as SSH came up.






