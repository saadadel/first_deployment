# Flask webapp Deploy
This is the 6th project for udacity full stack nanodegree

##### IP Address of server:

18.185.59.214

##### hostname: 
ec2-18-185-59-214.eu-central-1.compute.amazonaws.com

##### private key of grader:
-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEA18iY89gmc51PZFa7mRFReOBpXdlBnr72yHul2z/Nj5EC5U11
S1TcHwqE/MfGjqEZJNpZ6EAN7zJQsSMSCAwfQq9JZK1/2yYdOoTdvdRKuG+UiFRN
DKWUcdcdhSsOgQHCaPKwyRidX3JIjwPWvgGgU2lknbU4NHexA2K/ZFb03k/QgN2t
go/FNFA8EX6J1idsOsZxTrq5ggKkG6d/KzRb9eLjWKk3VBTjR3D24Ax2/ZsSpQNF
Ck7+C/DfoLp1UX+B0ExU7pu4xOAOEw19zKw9AwMP+SI0pP063HD1gy3swn3Ry6p1
MQcFxC8Udd8Xz4IBztPb1S0fo5bb0QYEP4eBjwIDAQABAoIBACxCJq0NDoX0JA6O
g5fXp4BFdxcasoze2jswsUoRAhaKRa/GfWJgG236eGBokV87x655YqtyR+lhxo8u
hEpGQjspPMJ7m5fVb3VLPzfqTREbQbncoJkRdSsMVi+0Lxtiwv9Hl98HP3AOPrem
r+r05m91VH/MZaTNT+9D18G63Cqkj8bZXdFBhmaLSNqq8ahTxtKPrhqSeT42DaWI
MDBaUBQ5bsMYIudvLIGSF3cEmLv+sDGgiNbjlP7RqmrErsK6xXJxCF+GyRNSBq7F
LfPqHuvvnTJEXxU4ccV6QvU08QD6LL7V2RX3arsrJ8UpI5kXBp0cMFGcoM6PhmR0
H5FN8pECgYEA8qFBMavw8dd8yqpxhtLcpzQPjicbI923aMU2w/DmX7I6ZlvqsyR6
DQSc7eIuT4sTyxNm6tFMg/YuhQmtc3OrpNwO/ISPYpCmH4nxvpLqZ7PnzP86dNho
ruBZbN6zCSleZbF7S6TjHb5DgYEu6hrrkZ+dtqF6lcgWUhrJ89vQwuUCgYEA46yg
Km3ZOTZ5yqW2Ro8+cd7Jdl2810HOwf3/4JVUQxAEm61sszJYhi6+YWod/zapofzH
6wMa2z5tH7u/isWJDURBtcyaGDryecagK68SVrK9FSgdvAk6VPJg4s+F7ldIEbJN
e6wMvA5+FjTaEAd/K8+hJlkylnFDk5PUdcG6Z2MCf0vSGI1tLd5leJncqZ14R3v4
yOOjVNfgcXBMMNEKdvNwvs896hoRTBLFXkT4aYBx9b2AUqkOvtp+FAt++rUZcIoU
Opqu0h/7E+7HLMRhJN9DWSy2lY3uEsiTU16yOUCjrNwamm0JGfAxhObzd7Wws+zN
9Hsd+zDTViZSOMn750ECgYEAuz9iiwLFQPS4vh4EB4wQA38DmkIF6dPJxGquY3rt
TiqCX7cGS2sAu3r+QQgRm7DNWtiXY4WuNNrmzM6Q/gTwbuTQVkDsCzmP6u+dE9Bs
+LkQIbJYoinEu9CMNn4O3LMUJtnKOAiMgK46rPDS15QS12lwVCXQIUMOHPXcKu0l
7ZkCgYEAwK0UVltKIRXzl0Ci1LEtHeHC/ODkm6PSFOvBybrmUa06KYl35JLeEH5C
AnnR01FcP9p3cph0HXd0jYeoIOI/F1dWhmv/i+11uDZcnuAcOQ1xi6R5ipp9MMTQ
hw7pqRDTNdJnj5v7N+8+KHz2AI2qKpCCrilA3Rr4UUDpYaUzmu4=
-----END RSA PRIVATE KEY-----

# software installed
- Apache webserver using Flask framework and bootstrap formatting.

- Data is saved to a Postgresql database on the server.

# Configurations made

  -  Root access disabled

   - Postgresql user called 'catalog' added, with password 'x'

-    An additional superuser called 'grader' with password 'x' was added to allow Udacity grader to access the server

 -   Password access to the server disabled

  -  Access limited to private rsa key authentication

   - Enabled firewall to restrict ports to 2200 for ssh, 80 for webservice, 123 for NTP. All others ports have been blocked.

-    The ssh port is 2200 - a non-default port. The normal port (22) has been disabled.

# Third Party Resources

 -   https://github.com/mulligan121/Udacity-Linux-Configuration

  -  https://github.com/mulligan121/Udacity-Linux-Configuration

