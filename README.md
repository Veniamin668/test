Setup & Secrets

To run this workflow test.yml in your own repository, you need to configure the following GitHub Secret:

    DISK_ENCRYPTION_KEY — Password used to encrypt and decrypt the compressed disk image during backup and restore steps.
The other workflows can be run as-is if you remove the username check.
