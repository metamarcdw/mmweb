usage: mmcli.py [-h] [-e ENTITY] [-c CHAIN] [-p BTC_PORT]
                {checkinbox,processinbox,modbanuser,modbantag,modremoveoffer,showchan,showchanmsg,showmsglist,showmsg,createmsg,sendmsg,sendmarketoffer}
                ...

METAMARKET Command Line Interface

positional arguments:
  {checkinbox,processinbox,modbanuser,modbantag,modremoveoffer,showchan,showchanmsg,showmsglist,showmsg,createmsg,sendmsg,sendmarketoffer}
                        Program mode:
    checkinbox          Check your BM inbox for new MM Messages.
    processinbox        Parse your BM inbox for MM Messages.
    modbanuser          Moderator: Ban a User.
    modbantag           Moderator: Ban a Tag. (and all Offers bearing said
                        Tag)
    modremoveoffer      Moderator: Remove an Offer.
    showchan            Show a list of available chan messages.
    showchanmsg         Show a specific chan message.
    showmsglist         Show your current list of some type of MM Messages.
    showmsg             Show a specific MM Message in detail.
    createmsg           Create any new MM Message.
    sendmsg             Send any MM Message over BM.
    sendmarketoffer     As a Moderator, send your Market offer to the chan.

optional arguments:
  -h, --help            show this help message and exit
  -e ENTITY, --entity ENTITY
                        Choose which entity to act as: buyer, vendor, or mod.
  -c CHAIN, --chain CHAIN
                        Choose which blockchain to use: testnet or mainnet.
  -p BTC_PORT, --btcport BTC_PORT
                        Use a specific RPC port to connect to Bitcoin Core.
