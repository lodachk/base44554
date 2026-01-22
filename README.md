# base44554
Detecting Wallets That Fund Others but Never Interact With Contracts
if sent_tx > 0 and contract_calls == 0:
    print("Pure funding wallet detected")
These wallets often act as upstream funders for bots or disposable addresses.
Tracking them helps identify wallet hierarchies, sybil setups, and automation patterns on Base.
