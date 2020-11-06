How to import an existing delegate as witness in Graphene 2.0
=========================================================================

Preparations in Graphene 0.9 network
--------------------------------------------

We need to Extract the signing public and private key from Graphene 0.9.

Let's obtain the <publickey>::

    >>> get_account <delegatename>
    [...]
    Block Signing Key: <publickey>
    [...]

Remark: Public keys in the Graphene network have the prefix GPH. Hence, in the case of the Graphene testnet you should replace GPH by GPH.

and the corresponding <wifkey>::

    >>> wallet_dump_account_private_key <delegatename> signing_key
    "<wifkey>"
